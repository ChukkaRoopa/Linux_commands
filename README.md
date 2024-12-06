Linux Commands
~~~~~~~~~~~~~~

*  cp <file1><file2>  -> copies the contents of file1 to file2

*  cd <path>  -> navigate between directories

*  chmod -> change the permissions of the files
   rwxrwxrwx -> user(u), group(g), others(o) permissions
   example - if a file has rw-r--r-- permissions; then to add write permission to group, we use the command - chmod g+w <file_name>

*  cat <file_name> -> To see the contents of the file

*  clear -> clears the entire screen

*  cal <month><year> -> displays the calender

*  curl -> used to transfer data from or to a sever using API
   curl -X "GET" -H "Authorization" -o <output_filename>
   -X indicates the http method; -H indicate the http header; -o indicate the output

*  df -> displays the available disk space of the file system

*  diff <file1><file2> -> displays the difference of the file1 and file2

*  du <directory> -> gets the size of the directories and subdirectories

*  echo "Hello" -> used to print something in the terminal

*  file <filename> -> tells the type of the file

*  grep -> used to find specific string in the file; cat <filename> | grep "string"

*  head <filename> -> returns the 1st ten lines; head -n 5 <filename> -> returns 1st five lines

*  hostname -> displays the host name

*  ifconfig -> gets the network interface configurations (ethernet)

*  kill <signal_option><process_id>-> terminates the process; signal_option = -9 indicates forces a process to stop immediately without cleanup

*  ls -> list all the files and directories
   ls -l ->long length format 
   ls -h -> human readable format
   ls -R -> recurssive listing - shows all the sub-directories listing
   ls -a -> list all the hidden files

*  mkdir <directory_name> -> creates a new directory

*  mv <file_name> <renamed_file> -> used to rename files

*  nano <filename> -> text editor

*  netstat -> show all the network configurations (tcp, udp)

*  ps -> check all the active processes in the terminal, unlike top, it doesn't update the information automatically

*  passwd <new_username> -> used to create a password for the new user

*  pwd - print the current working directory

*  ping <hostname or ip_address> -> used to send packets to a target server

*  rm <file> -> used to delete the file

*  rmdir <directory_name> -> used to delete the directory

*  sort <file> -> sorts the output of the file

*  sed -> stream editor
   sed "s/[[:space:]]*$//" -> removes trailing spaces
   sed "s/^[[:space:]]*//" -> removes leading spaces

*  top -> displays all the running processes and hardware consumption

*  tail <file_name> -> returns the last ten lines; top -n 5 <filename> -> returns last five lines

*  touch <file_name> -> creates an empty file

*  tar <tar_filename><file1><file1>.. -> bundles into tar file

*  traceroute <hostname or ip_address> -> tracks the packets path

*  uname -> gets the name of the Operating system

*  useradd <options><new_username> -> creates a new account in your linux system

*  userdel <username> -> deletes the user

*  vi <filename> -> used to edit the file

*  whoami -> gets the name of the user

*  wc <file_name> -> gets the number of lines, words, characters of a file
   wc -w <file_name> -> gets the number of words; wc -l <file> -> no. of lines; wc -c <file> -> no. of characters

*  zip <zip_file_name><file1><file2>... -> converts into zip file