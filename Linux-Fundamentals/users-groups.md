#  users-groups.md — User and Group Management
 
Is file mein Linux users aur groups create aur manage karna seekhein.
# Command	                         Purpose
whoami	                             Current user
id	User and                         group IDs
groups	User                         groups
sudo adduser ali	                 New user create
sudo passwd ali	Password             set/change
sudo groupadd developers	         New group create
sudo usermod -aG developers ali	     User ko group mein add
getent passwd	                    User account entries
getent group	                    Group entries
sudo deluser ali	                User delete
