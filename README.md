# Linux Developer Notes

Welcome to the Linux Developer Notes repository! This is a collection of useful information, tips, and commands related to Linux development. Whether you're a beginner or an experienced developer, you'll find valuable resources to enhance your Linux skills.

## Table of Contents

- [Getting Started](#getting-started)
- [Linux Basics](#linux-basics)
- [Package Management](#package-management)
- [Shell Scripting](#shell-scripting)
- [Version Control](#version-control)
- [Networking](#networking)
- [System Administration](#system-administration)
- [Troubleshooting](#troubleshooting)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

If you're new to Linux development, start here to learn the basics of working with Linux systems and commands.

## Linux Basics

Explore essential Linux commands, file system navigation, permissions, and more.



`whoami` Displays the current user's username.

`pwd` Prints the current working directory (i.e., the path to the directory you're in).

`ls` Lists files and directories in the current directory.

`ls -a` Lists all files and directories, including hidden ones (those starting with `.`).

`ls -la` Lists all files and directories in a detailed, long format, including hidden ones.

`mkdir folderName` Creates a new directory with the specified name.

`cd folderName` Changes the current directory to the specified folder.

`cd ..` Moves up one directory level.

`cd` Changes to the user's home directory.

`touch fileName.txt` Creates a new empty file with the specified name.

`echo "Hello world"` Prints the text "Hello world" to the terminal.

`mv fileName.txt folderName2` Moves the file `fileName.txt` to `folderName2`.

`nano` Opens the Nano text editor to create or edit files.

`cat fileName.txt` Displays the content of the file `fileName.txt` in the terminal.

`history` Displays a list of recently executed commands.

`rm fileName.txt` Deletes the file `fileName.txt`.

- System Management:

`sudo apt install nodejs` Installs the Node.js package using the APT package manager with superuser privileges.

`sudo apt update` Updates the package list and information for available software packages.

**Note:** It is recommended to use `apt` commands on the terminal and `apt-get` in bash scripts. This is because `apt` is the newer version and is constantly evolving, which can sometimes break backward compatibility. Using `apt-get` commands ensures guaranteed backward compatibility and provides more functionality for script usage.

`man <topic>` Displays the manual page for the specified topic, providing detailed information about commands and concepts.


## SSH & How to Connect to SSH

Connecting to an Amazon Web Services (AWS) EC2 instance using SSH on Ubuntu is a fundamental task for managing your cloud resources. SSH provides a secure way to remotely access your EC2 instances. In this guide, we'll walk you through the process.

## Prerequisites

- An AWS EC2 instance with SSH access enabled.
- Your EC2 instance's public IP address or DNS name.
- An SSH key pair (if not already created).

## Steps

### 1. Open a Terminal

On your Ubuntu system, open a terminal window. You can do this by pressing `Ctrl + Alt + T` or searching for "Terminal" in the applications.

### 2. Navigate to the Directory with Your SSH Key

If you have an SSH key pair already, navigate to the directory where your private key is stored. If you don't have an SSH key pair, you can generate one using the following command:

```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

## Package Management

Learn how to manage software packages using package managers like `apt` and `yum`.

## Shell Scripting

Discover the power of shell scripting to automate tasks and enhance your workflow.

## Version Control

Get familiar with version control systems like Git for efficient code management.

## Networking

Learn about networking concepts, tools, and how to troubleshoot network issues.

## System Administration

Dig into system administration topics, including user management, system monitoring, and security.

## Troubleshooting

Find solutions to common problems and learn effective troubleshooting techniques.

## Resources

Explore additional resources, books, tutorials, and online courses to deepen your Linux knowledge.

## Contributing

If you'd like to contribute to this repository, feel free to fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Note:** This is an open-source Repo, feel free to contribute!!!
