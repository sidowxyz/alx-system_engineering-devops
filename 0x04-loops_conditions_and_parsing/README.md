# Loops, Conditions, and Parsing

This project focuses on learning how to use loops, conditionals, and parsing techniques in Bash scripting. These are essential skills for automating tasks, managing files, and interacting with systems as a DevOps engineer.

## Project Overview

### Learning Objectives

By the end of this project, you should be able to:
- Create SSH keys and understand their importance.
- Explain the advantages of using `#!/usr/bin/env bash` over `#!/bin/bash`.
- Use `while`, `until`, and `for` loops in Bash scripts.
- Implement `if`, `else`, `elif`, and `case` conditional statements.
- Use the `cut` command for text processing.
- Understand file and comparison operators in Bash.

### Tasks

1. **Create an SSH RSA key pair**:
   - Generate an RSA key pair and share the public key.

2. **For Loop - Best School**:
   - Write a Bash script that displays "Best School" 10 times using a `for` loop.

3. **While Loop - Best School**:
   - Write a Bash script that displays "Best School" 10 times using a `while` loop.

4. **Until Loop - Best School**:
   - Write a Bash script that displays "Best School" 10 times using an `until` loop.

5. **If 9, Say Hi!**:
   - Write a Bash script that displays "Best School" 10 times, but on the 9th iteration, it also displays "Hi".

6. **4 Bad Luck, 8 Is Your Chance**:
   - Write a Bash script that loops from 1 to 10 and displays special messages on the 4th and 8th iterations.

7. **Superstitious Numbers**:
   - Write a Bash script that displays numbers from 1 to 20 and includes special messages for certain numbers using a `case` statement.

8. **Clock**:
   - Write a Bash script that displays the time for 12 hours and 59 minutes.

9. **For `ls`**:
   - Write a Bash script that lists the content of the current directory but only displays the part of the name after the first dash.

10. **To File, or Not to File**:
    - Write a Bash script that checks if a file exists, if it’s empty, and if it’s a regular file.

11. **FizzBuzz**:
    - Write a Bash script that displays numbers from 1 to 100, replacing multiples of 3 with "Fizz", multiples of 5 with "Buzz", and multiples of both with "FizzBuzz".

12. **Read and Cut**:
    - Write a Bash script that displays specific fields from the `/etc/passwd` file using the `while` loop and `cut` command.

13. **Tell the Story of `passwd`**:
    - Write a Bash script that formats the content of `/etc/passwd` into a narrative format using `while` and `IFS`.

14. **Let's Parse Apache Logs**:
    - Write a Bash script that parses Apache log files to display visitor IPs and their HTTP status codes.

15. **Dig the Data**:
    - Write a Bash script that groups visitors by IP and HTTP status code from Apache logs and displays the data sorted by the number of occurrences.

## Requirements

- **System**: Ubuntu 20.04 LTS
- **Shell**: Bash scripting
- **Shellcheck**: All scripts must pass Shellcheck without errors (version 0.7.0).
- **Editors**: `vi`, `vim`, `emacs`

## Repository Structure

- **GitHub Repository**: alx-system_engineering-devops
- **Directory**: `0x04-loops_conditions_and_parsing`

## How to Run the Scripts

1. Make sure all scripts are executable:
   ```bash
   chmod +x <script_name>
   ```

2. Run a script:
   ```bash
   ./<script_name>
   ```

## Author

- **GitHub**: [https://github.com/sidowxyz](https://github.com/sidowxyz)

