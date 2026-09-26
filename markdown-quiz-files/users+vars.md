# Linux User Management and BASH Variables Quiz

---

1. In Linux, there are primarily two types of accounts. They are:
    - (x) User accounts and System accounts
    - ( ) Root accounts and Guest accounts
    - ( ) Admin accounts and Normal accounts
    - ( ) Read accounts and Write accounts

2. The `sudo` command allows a permitted user to:
    - [x] Execute a command as the superuser
    - [ ] Create a new user
    - [ ] List all the files in the current directory
    - [ ] Display all environment variables

3. Which file determines who can run commands using `sudo`?
    - [ ] /etc/users
    - [ ] /etc/group
    - [x] /etc/sudoers
    - [ ] /etc/passwd

4. When creating a new user in Linux, which of the following commands can be used?
    - [x] `useradd`
    - [ ] `usermod`
    - [ ] `userrm`
    - [ ] `usershow`

5. To temporarily assume another user's identity, you would use the ______ command.
    - R:= su

6. The default shell assigned to a new user in most Linux systems is:
    - [ ] /bin/dash
    - [x] /bin/bash
    - [ ] /bin/csh
    - [ ] /bin/zsh

7. Which of the following commands will display the value of the `HOME` bash variable?
    - [x] `echo $HOME`
    - [ ] `print $HOME`
    - [ ] `cat $HOME`
    - [ ] `ls $HOME`

8. Which command appends a user named "john" to sudoers group?
    - [x] `usermod -aG sudo john`
    - [ ] `useradd -G sudo john`
    - [ ] `chmod sudo john`
    - [ ] `chown sudo john`

9. Environment variables in bash typically:
    - [x] Are written in ALL UPPERCASE
    - [ ] Are written in all lowercase
    - [ ] End with the extension .sh
    - [ ] Start with the $ symbol

10. In Linux file permissions, which of the following represents read, write, and execute permissions for the owner, read and execute permissions for the group, and only execute permissions for others?
    - [ ] `rw-r--r--`
    - [x] `rwxr-x--x`
    - [ ] `rw-rw-rw-`
    - [ ] `r--r-xr-x`