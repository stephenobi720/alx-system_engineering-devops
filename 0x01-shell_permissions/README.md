Description of what each script is doing 
0. su betty-  change user to betty 
1.id -un - prints the name fo the current username
2. groups - prints all the group the current user is part of 
3. chown betty hello - changing hello file ownership to user betty 
4. touch hello - create an empty file called hello 
5. chmod u+x hello -add the execute permisssion to the ownr of the file hello
6. chmod u+x,g+x,o+r hello - add the execute permission for the owner and the group, and add read permission for the file hello 
7. chmod ugo+x hello - gives everyone permission to execute the program hello 
8. chmod 007 hello - gives no one else permission other than the user 
9. chmod 753 hello - gives all privilege to owner, read and execute to group, and write and execute to world
10. chmod --reference=olleh hello - set mode mode of the file hello the same as olleh mode 
11. chmod -R ugo+X - add execute permission to all subdirectories of the current dirrectory for everyone
12. mkdir -m 751 my_dir - create a directory with permission for the owner, read and execute for groups, and execute for exeryone
13. chgrp school hello - change the group owner to school for the file hello 
14. chown -hR vincent staff . - changes the owner to vincent and group owner to staff for working directory 
15. chown -h vincent staff _hello - changes the owner of the file _hello to vincent and the group owner to staff 
16 chown --fromguillame betty hello - change the owner of the file hello to betty only if stephen is the owner 
17. telnet towwl.blinkenlights.nl - watch star wars 4 episode  
