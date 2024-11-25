# Ansible User Management Automation

## Overview
Ansible User Management Automation is a simple yet powerful project that automates tasks related to user management. It allows you to check if a user exists on remote servers, create new users with specific user IDs, and set their passwords—all through Ansible playbooks. This project simplifies user administration tasks and improves efficiency in managing multiple systems.

## Features
- **Check if a user exists**: Verifies whether a user already exists on the system.
- **Display user details**: Retrieves and displays user account details like expiration and password status.
- **Create new users**: Automatically creates new users with a custom user ID and sets their password.
- **Interactive prompts**: The playbook asks for user input for various parameters (username, user ID, password).

## Requirements
- **Ansible**: Version 2.9 or higher.
- **Python**: Version 3.x.
- **Sudo privileges**: Required on the target machines to manage users.

## Installation
1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/ansible-user-management.git



