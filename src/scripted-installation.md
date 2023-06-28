# Scripted Installation

To install SwapDEX, you can use the provided installation script. This guide will walk you through the process step by step.

## Prerequisites

- Make sure you have root access to the system.

## Instructions

1. Run the following command as root to download the installation script:


> ````
> wget https://raw.githubusercontent.com/starkleytech/swapdex-install-script/main/install_swapdex.sh && chmod +x install_swapdex.sh && ./install_swapdex.sh


This command will download the script, make it executable, and execute it.

2. The script will perform several tasks, such as checking the OS compatibility, installing required packages, configuring the firewall, downloading the SwapDEX binary, creating a service file, and starting the service.

You will see the script's output during the installation process, which may include prompts for user input.

Here is an example output of the script:

> ```
> # Check if the script is executed as root
> ...
> # Check if the OS is Ubuntu 22.04 or Rocky Linux 8
> ...
> # Prompt user if they want to install Kusari or SwapDEX
> ...
> # Check if previous SwapDEX or Kusari was active and prompt user if they want to delete the database
> ...
> # Create SwapDEX user if it doesn't exist
> ...
> # Install required packages
> ...
> # Configure and enable the time server
> ...
> # Configure the firewall
> ...
> # Install and configure fail2ban
> ...
> # Download the SwapDEX binary
> ...
> # Create SwapDEX service file
> ...
> # Prompt user for node name and replace placeholder in service file
> ...
> # Start and enable the service
> ...
> # Check if the node is syncing
> ...
> # Prompt the user if they want to generate a session key
> ...
> ```

The script will provide instructions and ask for user input at various stages. Please follow the prompts and provide the required information.

3. Once the installation process is complete, SwapDEX should be installed and running on your system. You can monitor the installation progress and check the logs for more information.

It's important to note that during the installation process, the script may prompt you for additional information or ask for confirmation before proceeding. Please read the prompts carefully and respond accordingly.

If you encounter any issues during the installation process, please refer to the script's output and logs for error messages or contact the support team for assistance.

**Note:** It's recommended to have basic knowledge of server administration and networking concepts before proceeding with the installation.
