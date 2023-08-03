su betty change the current user to the user betty
id -un show the user name of the current user
id -Gn show all the groups that your part of
chown betty hello changes the owner of hello to user betty
touch hello create the file hello empty
chmod u+x hello make hello executable for it owner
chmod ug+x,o+r hello add multiple permissions to the file hello
chmod ugo+x hello add all permissions to the file hello
chmod 007 hello add permissions to all users apart from owner and group
chmod 753 hello give owner all permissions, read and execute to group and write and execute to others
chmod --reference=olleh hello give the same mode to the file  hello and olleh
chmod -R +X give permission to execute all the subdirectories of the current directory, without touching at the regular files
mkdir -m 751 my_dir give the permission 751 to the directory my_dir
chgrp school hello change the group owner to school for the file hello
chown vincent:staff * change the owner to vincent and the group owner to staff in the working directory
chown -h vincent:staff _hello change the owner and the group owner of hello to vincent and staff
chown --from=guillaume betty hello change the owner the file hello to betty, only if betty is own by guillaume
telnet towel.blinkenlights.nl play the StarWars IV episode in the terminal   
