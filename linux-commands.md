# Linux Commands Learning

I am learning Linux commands for cybersecurity and SOC Analyst practice.

## Basic Commands

- pwd — Shows the current working directory.
- ls — Lists files and directories.
- cd — Changes the current directory.
- mkdir — Creates a new directory.
- rmdir — Deletes an empty directory.
- touch — Creates an empty file.
- cat — Displays the contents of a file.
- cp — Copies a file or directory.
- mv — Moves or renames a file.
- rm — Deletes a file.

## File and Text Commands

- echo — Displays text or writes text to a file.
- head — Shows the beginning of a file.
- tail — Shows the end of a file.
- grep — Searches for specific text in a file.
- sort — Sorts lines.
- uniq — Finds/removes repeated lines.
- wc -l — Counts the number of lines.

## System Commands

- id — Shows user and group information.
- ps — Shows running processes.
- uname -a — Shows Linux system/kernel information.
- history — Shows previously executed commands.
- df — Shows filesystem/disk usage.
- free — Shows memory information.

## Network Command

- ip a — Shows network interfaces and IP addresses.

## Permissions

- ls -l — Shows detailed file information and permissions.
- chmod — Changes file permissions.

## Basic SOC Log Practice

I created a sample login log and practiced searching for failed login attempts.

Example:

Login failed from 192.168.1.10

Command used:

grep "failed" login.log

I also practiced counting failed login entries using:

grep -c "failed" login.log
