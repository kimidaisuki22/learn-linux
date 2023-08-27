#Add
adduser @username@

#Delete
deluser @username@
options:
+ --remove-home



#Sudo
echo "@username@  ALL=(ALL) ALL" >> /etc/sudoers

use sudo without password
echo "@username@  ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers
