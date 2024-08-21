# Week0_DevOps
1.touch file1 #create file file1
2.ls   #list files and directories
3.ls -ltr  # list files and directories in a sorted order providing some details
4.mkdir dir1  # create a new directory dir1
5.pwd  # display present working directory
6.cd dir1  # change directory to dir1
7.echo #to print text
8.man # to give info about a command
9.free -g  #to know the memory
10.nproc #to know no of cpu
11.df -h   #disc size
12.top   #combination of free-g ,nproc and df -h
13.vi # to create and edit file
14.vim #to create and edit file ,add .sh to create a bash script
           to write in file enter i(i for insert)
            wq!--to save and exit from file
             q!--does not save the file but exits
15.cat  #display contents of the file
16.  ./file1.sh  #display contents in the bash file
17. sebang: #!/bin
18.chmod #to change the permissions of files and directories. It allows you to define who can read, write, or execute a file
   chmod 777 file1.sh #gives all permissions

19.mv  #rename file or directory name
20.rm -rf  # delete file or directory 
21.ps -ef  #shows all the processes running
22. grep  #search texts in file based on specific patterns
23.| is pipe command #pass he output of one command as input to another command. 
ps -ef | grep processname  #to get all the processes named processname use grep command,| pipe parameter sends the output of the 1st parameter to 2nd
24.awk  #specifies a particular column
25.set -x #print commands in debug mode
26.set -e #exists the script when there is an error but fails when there is a pipe
27.set -o pipefail #to handle above command when there is a pipe
28.curl urlname  #used in the command line to transfer data from or to a server using various protocols like HTTP, HTTPS, FTP, and more  
29.curl -X GET apiname  #to get api data
30.Wget logfilename    #download logfile
31.we can also use ifelse ,loop in shell scripting



