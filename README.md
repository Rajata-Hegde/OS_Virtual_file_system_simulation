
# Virtual File System Terminal

This project is a graphical terminal application simulating a Virtual File System (VFS) using Python's Tkinter library. The VFS provides users with the ability to interact with a simulated file system through familiar terminal commands like `ls`, `cd`, `touch`, `mkdir`, and more.

---

## Features

- **Command Line Interface:** A terminal-like interface where users can execute file system commands.
- **Simulated File System:** Create, delete, rename, and manipulate files and directories without affecting the real file system.
- **Command Help:** Each command has detailed descriptions and usage examples for beginners.
- **Interactive GUI:** Built with Tkinter for an intuitive and simple graphical interface.

---

## Supported Commands

### File and Directory Operations
- `ls` - List the contents of the current directory.
- `cd <folder_name>` - Change the current directory.
- `pwd` - Display the current directory path.
- `touch <file_name>` - Create an empty file.
- `mkdir <folder_name>` - Create a new directory.
- `rm <file_name>` - Remove a file.
- `mv <source> <destination>` - Move or rename files and directories.
- `cp <source> <destination>` - Copy files or directories.
- `rename <old_name> <new_name>` - Rename a file or directory.
- `rmdir <folder_name>` - Remove an empty directory.

### Utility Commands
- `cat <file_name>` - Display the contents of a file.
- `clear` - Clear the terminal screen.
- `help <command>` - Show detailed information about a specific command.

---

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Rajata-Hegde/os_virtual_file_system_simulation.git
   cd virtual-file-system-terminal

