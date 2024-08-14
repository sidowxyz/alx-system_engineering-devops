# Web Stack Debugging #3

This project focuses on debugging a WordPress website running on a LAMP stack (Linux, Apache, MySQL, PHP). The goal is to identify and fix a `500 Internal Server Error` using `strace` and automate the fix with a Puppet manifest.

## Project Details

- **Author**: [Sidow Adan](https://github.com/sidowxyz)
- **Date**: August 2024

## Project Description

In this project, we use `strace` to trace system calls and signals, allowing us to diagnose why Apache is returning a `500 Internal Server Error`. After identifying the issue, we create a Puppet manifest to automate the fix.

## Requirements

- Ubuntu 14.04 LTS
- Puppet 3.4
- Puppet-lint 2.1.1
- `strace` command-line utility

## Files

- `0-strace_is_your_friend.pp`: Puppet manifest that fixes the issue causing the `500 Internal Server Error`.

## How to Use

1. **Run `strace`** on the Apache process to identify the error:
   ```bash
   sudo strace -p $(pgrep apache2) -o strace_output.txt
   ```
2. **Fix the issue** by modifying the necessary file permissions or restoring missing files.
3. **Automate the fix** using the provided Puppet manifest:
   ```bash
   sudo puppet apply 0-strace_is_your_friend.pp
   ```
4. **Verify** that the issue is resolved by sending a request to the server:
   ```bash
   curl -sI http://127.0.0.1
   ```

## Example Output

Before applying the Puppet manifest:
```bash
HTTP/1.0 500 Internal Server Error
```

After applying the Puppet manifest:
```bash
HTTP/1.1 200 OK
```


