#   files-permissions.md — File Management and Permissions
 
File and directory commands:
#  Command	               Purpose
mkdir test	               Directory create
touch file.txt	           Empty file create
cat file.txt	           File content read
nano file.txt	           File edit
cp file.txt backup.txt	   File copy
mv file.txt new.txt	       File rename
rm file.txt	               File delete
rmdir test	               Empty directory delete
find . -name "*.txt"	   Files search
head file.txt	           First 10 lines
tail file.txt	          Last 10 lines
wc -l file.txt	          Lines count

Permissions commands:
# Command	             Purpose
ls -l	                 Permissions check
chmod 755 file.sh	     Permissions change
chmod +x script.sh	     Execute permission add
chmod 644 file.txt	     Read/write permissions set
chown user file.txt	     Owner change
chgrp group file.txt	 Group change



Important concepts to explain:
- Read (r) = 4
- Write (w) = 2
- Execute (x) = 1
- User (u), Group (g), Others (o)
- Permission 755 and 644 ka meaning.
