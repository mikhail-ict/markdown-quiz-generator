# Linux Quiz: File Permissions & Software Updates

---

1. Which command is used to switch to another user's account in Linux?
    - [ ] `chown user1`
    - [x] `su user1`
    - [ ] `sudo user1`
    - [ ] `mv user1`

2. How can you install multiple software packages in one command using `apt-get`?
    - [ ] `apt-get install cowsay & fortune-mod`
    - [ ] `apt-get install cowsay; fortune-mod`
    - [x] `apt-get install cowsay fortune-mod`
    - [ ] `apt-get install (cowsay fortune-mod)`

3. To randomly display a quote or saying after installing the `fortune-mod` package, which command do you use?
    - R:= fortune

4. If you want a command or series of commands to execute every time you log out of your shell session, where should you add those commands?
    - [ ] `~/.bashrc`
    - [ ] `~/.bash_profile`
    - [x] `~/.bash_logout`
    - [ ] `~/.logout_cmds`

5. If you want to install the `mini-httpd` package using `apt-get`, which command would you use?
    - R:= sudo apt-get install mini-httpd

6. To start the `mini-httpd` service in Linux, which command would you typically use?
    - [x] `sudo systemctl start mini-httpd`
    - [ ] `sudo start mini-httpd`
    - [ ] `sudo service start mini-httpd`
    - [ ] `sudo run mini-httpd`

7. To check the status of a service in Linux, such as `httpd`, what command would you use (starts with `sudo`)?
    - R:= sudo systemctl status httpd

8. If you wish to stop the `mini-httpd` service, which command would you use (starts with `sudo`)?
    - R:= sudo systemctl stop mini-httpd

9. How can you exit from the current user's session or from a user you've switched to?
    - [x] `exit`
    - [ ] `leave`
    - [ ] `logout`
    - [ ] `end`