
# Excercise 3
- Create 3 groups – admin, support & engineering and add the admin group to sudoers. 
- Create a user in each of the groups. 
- Generate SSH keys for the user in the admin group

# commands
groupadd admin ----- useradd admin adminuser
groupadd support ------- useradd support supportuser
groupadd engineering ---- useradd engineering engineeringuser

login adminuser --- to login to admin user
ssh-keygen 

/etc/passwd
![EtcPasswd](images/etc-passwd.png?raw=true "EtcPassWd")

/etc/group
![EtcGroup](images/etc-group.png?raw=true "EtcGroup")

/etc/passwd
![EtcSudoers](images/etc-sudoers.png?raw=true "EtcSudoers")