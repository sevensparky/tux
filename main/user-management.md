# User management commands of linux


### **To add a new user**

> sudo adduser username

_____________________________
### **To change the password of a user**

> sudo passwd -l 'username'

_____________________________
### **To remove a newly created user**

> sudo userdel -r 'username'

_____________________________
### **To add a user to a group**

> sudo usermod -a -G GROUPNAME USERNAME

_____________________________
### **To remove a user from a group**

> sudo deluser USER GROUPNAME
