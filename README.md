# Linux Commands

<h3>List of common commands for Linux</h3>


1. **ls**: List files and directories in the current directory.
   - Example: `ls`

2. **cd**: Change directory.
   - Example: `cd /path/to/directory`

3. **pwd**: Print the current working directory.
   - Example: `pwd`

4. **mkdir**: Create a new directory.
   - Example: `mkdir directory_name`

5. **rm**: Remove files or directories.
   - Example: `rm file.txt` (removes a file)
   - Example: `rm -r directory` (removes a directory and its contents recursively)

6. **cp**: Copy files and directories.
   - Example: `cp file.txt destination_directory`

7. **mv**: Move or rename files and directories.
   - Example: `mv file.txt new_location` (moves a file)
   - Example: `mv file.txt new_name.txt` (renames a file)

8. **cat**: View the contents of a file.
   - Example: `cat file.txt`

9. **grep**: Search for a pattern in a file.
   - Example: `grep "pattern" file.txt`

10. **chmod**: Change permissions of a file or directory.
    - Example: `chmod +x script.sh` (gives execute permission to a script)

11. **sudo**: Execute a command with administrative privileges.
    - Example: `sudo command`

12. **apt-get**: Package management command (Ubuntu/Debian).
    - Example: `sudo apt-get install package_name`

13. **yum**: Package management command (CentOS/RHEL).
    - Example: `sudo yum install package_name`

These are just a few examples of Linux commands. There are many more available, each serving different purposes. Remember to consult the relevant documentation or use the `man` command for more information on specific commands.


# Wifi Icon Missing
Run Command to turn **off** and then turn **on** NetworkManager Command Line Interface.

Step 1 :

`sudo nmcli networking off`

Step 2 : 

`sudo nmcli networking on`

Step 3 : 

Turn on airplane mode and then turn off.

WoW ! It's working.
