User Management

```bash
cat /etc/passwd or getent passwd #checking existing user

useradd username or adduser username #create user

passwd password #set password for user

id username #verify user creation

groupadd groupname #create groupname

usermod -aG groupname username #to assign group to user

cat /etc/group #list of groups

su - username #switch user

userdel username #delete user

groupdel groupname #delete group

```

