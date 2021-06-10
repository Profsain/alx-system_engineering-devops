Alx system engineering devops shell permissioins

Commands:         Function

su -l betty : command to switch user to betty with login option

whoami : Print the login user name

groups : Print all te groups a user is members of


chown : To change ownership of files or directory to different users

touch : To create an empty file in the current working directory

chmod : to change file or directory permission to r=read, w=write, x=execute.

chmod 744 : Add execute permission to the owner of the file

chmod 754 : Add execute permission to the group owner

chmod 751 : Add execute permission to the owner, group owner and others

chmod --reference = RRFILE file : To copy RRFILE permission to file

chmod -R 775 */ : To add permission to subdirectories only in the current directory

mkdir -m 751 dir_holberton : Create new directory and set the permission to 751