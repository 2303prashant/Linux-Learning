# Linux Commands

- `sudo apt update`  
  Command to update the terminal

- `sudo apt install "application name and version"`  
  To install a particular application

- `mkdir <dir_name>`  
  To create a directory

- `cd`  
  This command is used to go inside a particular directory or folder

- `cd ..`  
  Is used to back out from a particular folder

- `ls`  
  This command will list out all the files and folders in the directory

- `ls -a`  
  This command will list out all the files and folders in the directory along with all hidden files of that particular location

- `ls -ltr` or `la`  
  This command can be used to see the permissions (read, write, execute - i.e., **rwx**) given to the (user, group, and others) of a file

- `chmod -R 777 <filename>`  
  To change or give permissions (read, write, or execute) of a file

- `chown -R 777 <filename>`  
  To change the ownership (user and group) of a file

- `unzip <zip_file_name>`  
  Used to unzip a file

- `touch <filename.extension>`  
  To create a file

- `echo <filename.extension>`  
  This command is also used to create a file

- `nano <filename>`  
  To create and/or edit or modify a file

- `vim <filename>`  
  Vim is an editor in Linux, so this command will allow to edit the file

- `sudo adduser <username>`  
  To create a new user

- `su <username>`  
  Switch to another user

- `ssh user@hostname`  
  To securely connect with a remote machine over the network  
  **user** is the username on the remote machine  
  **hostname** is the IP address of the remote machine

- `cat <filename>`  
  This command will display the content of a file

- `head <filename>`  
  This command will display the first or top 10 lines of the content of a file  
  Or we can also specify the number of lines we want to display, like if we want to display the top 20 lines from the content of a file we will write the command - `head -20 <filename>`

  **Navigation keys with the head command:**
  - `ENTER Key` ----> To scroll down to the page by lines
  - `SPACE Key` ----> To move to the next line
  - `'B' Key` ----> To move back to the previous line
  - `'/' Key` ----> To search for a particular keyword or string

- `tail <filename>`  
  This command will display the last 10 lines from the content of a file,  
  And to specify the number of lines to display, we will write the command - `tail -20 <filename>`

- `more <filename>`  
  This command is used to view the content of a file with forward navigation feature

- `less <filename>`  
  This command is similar to the `more` command. The only difference is that with the `less` command, we can view the content of a file with forward and backward navigation feature along with the search feature, i.e., we can also search for a particular string or keyword with the `less` command

- `cp <filename> <path>`  
  Command to copy a file or folder to a particular location or directory

- `mv <filename> <path>`  
  Command to move a file to a particular location  
  **Note:** The `mv` command can also be used to rename a file, for that the syntax is - `mv <old_filename> <new_filename>`

- `rm -rf <file>`  
  Command used to forcefully remove or delete a file

- `top`  
  This command displays the real-time information about the process running on the system, like CPU and memory usage

- `ps` (Process Status)  
  Used to provide information about currently running processes
  - `ps -e` --- Displays all processes
  - `ps -f` --- Gives full listing of processes
  - `ps -u` --- Filters by user

**Difference between the ps and top commands:**  
`ps` provides the static snapshots of the processes, while the `top` command updates its display continuously in real time.
