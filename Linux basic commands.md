***Linux Commands***</br>
*sudo apt update* --- Command to update the terminal </br>
*sudo apt install "application name and version" --- To install a particular application </br>
*mkdir <dir_name>* --- To create a directory </br>
*cd* --- this command is used to go inside a particular directory or folder </br>
*cd ..* --- is used to back out from a particluar folder </br>
*ls* --- this command will list out all the files and folders in the directory </br>
*ls -a* --- this command will list out all the files and folders in the directory along with all hidden files of that particular location</br>
*ls -ltr* or *la* --- this command can be used to see th permissions(read, write, execute - i.e., **rwx**) given to the (user,group and others) of a file </br>
*chmod -R 777 <fielname>* --- To change or give permissions (read, write, or execute) of a  file </br>
*chown -R 777 <filename>* --- To change the ownership (user and group) of a  file </br>
*unzip <zip_fie_name>* --- Used to unzip a file
*touch <<filename.extension>* --- to create a file </br>
*echo <filename.extension>* --- this command is also used to create a file</br>
*nano <filename>* --- to create and/or edit or modify a file </br>
*vim <filename>* --- vim is an editor in linux, so this command will allow to edit the file.</br>
*sudo adduser <username>* --- To create a new user</br>
*su <username>* --- switch to another user</br>
*ssh user@hostname* --- To securely connect with a remote machine over the network,... </br>
here,</br> 
---------------------->**user is --** the username on the remote machine </br>
and </br>
---------------------->**hostname is --** the IP address of the remote machine</br>
*cat <filename>* --- This command will display the content of a file.</br>
*head <filename>* --- This command will display the first or top 10 lines of the content of a file,...or we cam also specify the no.s of lines we want to display, like if want to display top 20 lines from the content of a file we will write the command - **head -20 <filename>** </br>
**Navigation keys with the head command**</br>
-----------------------*ENTER Key ---->* To scroll down to the page by lines</br>
-----------------------*SPACE Key ---->* To move to the next line.</br>
-----------------------*'B' Key ---->* To move back to the previous line</br>
-----------------------*'/' Key ---->* To search for a particular keyword or string</br>
*tail <filename>* --- This command will display the last 10 lines from the content of a file,.... and to specify the no.s of lines to display them, we will write the command - **tail -20 <filename>** </br>
*more <filename>* --- This command is used to view the content of a file with forward navigation feature. </br>
*less <filename>* --- This command is similar to to the **more** command the only difference is that with less command, we can view the content of a file with forward and backward navigation feature along with the search feature, i.e, we can also search for a particular string or keyword with less command.</br>
*sudo adduser <username>* --- Command to create or add a user.</br>
*cp <filename> <path>* --- Command to copy a file or folder to a particular location or directory</br>
*mv <filename> <path>* ---- Command to move a file to a particular location </br>
**Note --- </br>
The *mv *command can also be used to rename a file, for that the syntax is -- ***mv <old_filename> <new_filename>*** **</br>
*rm -rf <file>* --- Command used to forcefully remove or delete a file. </br>
*top* --- This command displays the real time information about the process running on the system, like CPU and memory usage</br>
*ps* (Process  status) --- Used to provide the information about currently running processes.
-------------------------->*ps -e* --- displays all process</br>
-------------------------->*ps -f* --- give full listing of processes</br>
--------------------------->ps -u* --- filter by user</br>
***Difference between the ps and  top commmands -*</br>
ps - provides the static snapshots of the processes, whiile the top command updates its display continuously in real time</br>




