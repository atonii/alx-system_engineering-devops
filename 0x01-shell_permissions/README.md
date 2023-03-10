### Scripts for shell permissions

#### su betty 
script for switching user to betty
#### tail -1 0-iam_betty | wc -c 
script to check number of characters
#### whoami 
script to print current user
#### groups 
script for printing groups current user is in
#### sudo chown betty hello 
give file to betty
#### touch hello 
script to create empty file
#### chmod 744 hello 
script to give current user executable right
#### chmod 554 hello  
script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
#### chmod ugo+x hello 
gives executable permission to everybody
#### chmod 007 hello 
script to grant other users all permissions only
#### chmod --reference=olleh hello 
sets olleh to hello
#### find . -type d -exec chmod 755 {} + 
directories permissions excluding files
### mkdir -m 751 my_dir
Creates a dir with custom permissions
