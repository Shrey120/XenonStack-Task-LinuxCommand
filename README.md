# XenonStack-Task-LinuxCommand

`internsctl` is a custom Linux command designed for managing intern-related operations.

## Table of Contents

- [Installation]
- [Usage]
  - [Options]
  - [Examples]
- [Contributing]
- [License]

## FlowChart

  Link: https://drive.google.com/file/d/1NDftWA0rGF8WXakFtdto9w_5DqFLIMUp/view?usp=drive_link

## Installation

To use `internsctl`, you need to have Bash installed on your system.

1. Clone the repository:

   ```bash
   git clone https://github.com/Shrey120/XenonStack-Task-LinuxCommand.git
   cd internsctl

2. To create a command internsctl We will use the command

   a) nano internsctl
   b) Make the script executable:
      chmod +x internsctl
   c) Run the command:
      ./internsctl --help

3. Usage

   Options

   -h, --help: Show help message and exit.

   ![WhatsApp Image 2024-01-10 at 16 32 01_c18767e4](https://github.com/Shrey120/XenonStack-Task-LinuxCommand/assets/86106616/328f6161-522e-42a2-926c-45df229a437e)

   -v, --version: Display version information.

   ![WhatsApp Image 2024-01-10 at 16 30 02_dd24acdf](https://github.com/Shrey120/XenonStack-Task-LinuxCommand/assets/86106616/2f076bf1-314c-4b8f-b759-775f04d70543)

   -l, man internsctl: List all interns.

   ![WhatsApp Image 2024-01-10 at 16 32 02_6b6b6e77](https://github.com/Shrey120/XenonStack-Task-LinuxCommand/assets/86106616/36ff36ed-78be-45e4-a90a-d499e66db860)

4. Getting info

   ![WhatsApp Image 2024-01-10 at 16 32 03_a0b93c8a](https://github.com/Shrey120/XenonStack-Task-LinuxCommand/assets/86106616/a9b94702-7718-4c4a-9e14-0c19744d3638)

   ![WhatsApp Image 2024-01-10 at 16 32 03_088f6dee](https://github.com/Shrey120/XenonStack-Task-LinuxCommand/assets/86106616/7b10eb7f-5956-45a1-934d-920ab399d964)

 
5. Creating User

   Creating User<br/>
   ![copy](https://github.com/Shrey120/XenonStack-Task-LinuxCommand/assets/86106616/1d6257d8-f908-45bc-9ff9-497d34a8e489)


   All User List<br/>
   ![WhatsApp Image 2024-01-10 at 16 32 03_8800f401](https://github.com/Shrey120/XenonStack-Task-LinuxCommand/assets/86106616/95ea80ba-19cb-4ad1-b330-b5db61a7635d)

   Sudo Permission Given to:<br/>
   ![WhatsApp Image 2024-01-10 at 16 32 03_b768577c](https://github.com/Shrey120/XenonStack-Task-LinuxCommand/assets/86106616/15f89920-eb15-4007-bfe7-26aa1ffc7843)
  

6. File Information Options
<br/>

   --size, -s: Print file size.<br/>
   --permissions, -p: Print file permissions.<br/>
   --owner, -o: Print file owner.<br/>
   --last-modified, -m: Print last modified time.<br/>
<br/>

7. Subcommands and Options
<br/>

   cpu getinfo: Display CPU information.<br/>
   memory getinfo: Display memory information.<br/>
   user create <username>: Create a new user.<br/>
   user list [--sudo-only]: List all users. Use --sudo-only to list users with sudo permissions only.<br/>
   file getinfo [options] <file-name>: Display information about a file. Options include --size, --permissions, --owner, and --last-modified.

   
