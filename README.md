# Linux commands 
# Linux Command Cheat Sheet

A quick reference for commonly used Linux commands.

## Basic Commands

- `ls` - List directory contents.
- `ls -l` - List directory contents in long format.
- `ls -R` - List directory contents recursively.
- `ls -a` - List all files, including hidden ones.
- `ls -r` - List directory contents in reverse order.
- `ls -t` - List directory contents sorted by modification time.
- `ls -lart` - List all files sorted by time in reverse order with details.
- `ll -la` - List all files, including hidden ones, in long format.
- `clear` - Clear the terminal screen.
- `whoami` - Show the current user.
- `pwd` - Print the current working directory.
- `cd` - Change directory.
- `cd ../` - Move to the parent directory.
- `cd -` - Switch to the previous directory.
- `chmod 777 index.html` - Change file permissions to read, write, execute for all.
- `mkdir xyz` - Create a new directory named `xyz`.
- `touch index.html` - Create a new file named `index.html`.
- `nano index.html` - Open `index.html` in the Nano editor.
- `vim index.html` - Open `index.html` in the Vim editor.
  - `i` - Insert mode in Vim.
  - `:w` - Save file in Vim.
  - `:q!` - Quit Vim without saving.
  - `:wq` - Save and quit Vim.

## System Commands

- `sudo apt install nginx` - Install the Nginx package.
- `sudo su` - Switch to the superuser.
- `systemctl status nginx` - Check the status of Nginx.
- `systemctl start nginx` - Start Nginx.
- `systemctl restart nginx` - Restart Nginx.
- `systemctl stop nginx` - Stop Nginx.
- `dpkg -l` - List all installed packages.
- `ip add` or `ifconfig` - Display network information.
- `df -h` - Display disk space usage in human-readable format.
- `du -sh [directory]` - Show disk usage of a specific directory.

## File and Directory Operations

- `rm index.html` - Remove a file.
- `rm -r xyz` - Remove a directory recursively.
- `rm -rf xyz` - Forcefully remove a directory recursively.
- `cp index.html /var/www/xyz` - Copy a file to a directory.
- `mv index.html index1.html` - Rename or move a file.

## Network and System Monitoring

- `history` - Show command history.
- `sudo -i` - Switch to the superuser interactively.
- `cat` - Display file content.
- `more` - Display file content page by page.
- `less` - Display file content with navigation.
- `ping [ip/hostname]` - Test connectivity.
- `curl [ip/hostname]` - Fetch data from a server.
- `curl -i -k` - Fetch data with headers and ignore SSL errors.
- `wget [url]` - Download files from the web.
- `top` - Display real-time system resource usage.
- `htop` - Display an enhanced real-time system resource usage (if installed).
- `free -h` - Display memory usage in human-readable format.
- `uptime` - Show how long the system has been running.
- `traceroute google.com` - Trace the route to a domain.
- `sudo find / -name "index.html"` - Search for a file from the root directory.
- `w` - Show who is logged in.
- `sudo last -f /var/log/btmp` - Show failed login attempts.

## User and Permission Management

- `useradd [username]` - Add a new user.
- `userdel [username]` - Delete a user.
- `usermod -aG [group] [username]` - Add a user to a group.
- `passwd [username]` - Change a user's password.
- `chown [user:group] [file]` - Change file owner and group.
- `chmod [permissions] [file]` - Change file permissions.

## Miscellaneous Commands

- `dd if=[input_file] of=[output_file]` - Convert and copy a file.
- `shutdown now` - Shut down the system immediately.
- `reboot` - Reboot the system.
- `alias ll='ls -la'` - Create an alias for a command.
- `unalias [alias_name]` - Remove an alias.
- `date` - Display the current date and time.
- `cal` - Display the calendar.
- `echo "text"` - Print text to the terminal.
- `uname -a` - Display system information.
- `man [command]` - Display the manual for a command.
- `exit` - Close the terminal or exit the current shell.

---

Feel free to use and customize this extended cheat sheet for your needs!
