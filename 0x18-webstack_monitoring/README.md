# Webstack Monitoring

This project involves setting up monitoring for a web stack using Datadog. Monitoring is essential for understanding the performance of both the server and the applications running on it. This project covers the installation of the Datadog agent, setting up monitors for specific metrics, and creating a dashboard to visualize these metrics.

## Project Overview

### Tasks

1. **Sign Up and Install Datadog Agent**:
   - Sign up for a free Datadog account.
   - Install the Datadog agent on `web-01`.
   - Set up your Datadog API key and application key.
   - Ensure that the `web-01` server is visible in Datadog.

2. **Monitor Some Metrics**:
   - Set up monitors in Datadog to track system metrics, such as:
     - The number of read requests per second.
     - The number of write requests per second.

3. **Create a Dashboard**:
   - Create a Datadog dashboard.
   - Add at least 4 widgets to visualize different metrics.
   - Record the `dashboard_id` in the `2-setup_datadog` file.

## Requirements

- **System**: Ubuntu 16.04 LTS
- **Tools**: Datadog, Bash
- **Scripts**: All Bash scripts must be executable and pass Shellcheck (version 0.3.7) without errors.
- **Editors**: `vi`, `vim`, `emacs`

## Files

- `2-setup_datadog`: Contains the `dashboard_id` of the created Datadog dashboard.

## Installation

1. **Datadog Agent**:
   - Follow the instructions on the Datadog website to install the agent on your `web-01` server.
   - Ensure that the agent is properly configured with your Datadog API and application keys.

2. **Monitors and Dashboard**:
   - Log in to your Datadog account.
   - Set up the required monitors and create a dashboard with at least 4 widgets.

## Author

- **GitHub**: [https://github.com/sidowxyz](https://github.com/sidowxyz)
