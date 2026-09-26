# Bash Quiz: Aliases, Functions and Scripts

---

1. What is an alias in the context of bash?
    - [x] A shortcut for a command or a series of commands
    - [ ] A program or script that you can execute
    - [ ] A function without any body or logic
    - [ ] A type of file permission

2. Which of the following commands will create an alias named `l` to list files in long format?
    - [ ] `function l { ls -l; }`
    - [x] `alias l='ls -l'`
    - [ ] `l() { 'ls -l'; }`
    - [ ] `set alias l 'ls -l'`

3. How can you define a function named `myfunction` using the `function` keyword in bash?
    - [x] `function myfunction { echo "Hello from myfunction!"; }`
    - [ ] `alias myfunction { echo "Hello from myfunction!"; }`
    - [ ] `alias myfunction='echo "Hello from myfunction!"'`
    - [ ] `myfunction { 'echo "Hello from myfunction!"'; }`

4. How can you pass multiple arguments to a function or script in bash?
    - [x] Using `$1`, `$2`, `$3`, etc.
    - [ ] Using `%1 %2 %3…`
    - [ ] Using `${1:2:3}`
    - [ ] Using `&1 &2 &3...`

5. If you wanted to pass arguments to a bash script, which special variable would you use to access the first argument?
    - R:= $1

6. In bash, what does a function allow you to do?
    - [x] Group commands for later execution using a single name for the group
    - [ ] Rename commands with a different name
    - [ ] Change file permissions of multiple files at once
    - [ ] Execute a command as the root user

7. What is the primary difference between an alias and a function in bash?
    - [x] A function can execute multiple lines of code, while an alias maps to a specific command.
    - [ ] Aliases can accept parameters, but functions cannot.
    - [ ] Functions can be made persistent across sessions, but aliases cannot.
    - [ ] Aliases are scripts, whereas functions are built-in commands.

8. When creating a bash script, what file extension is commonly used (your answer should start with `.`)?
    - R:= .sh

9. If you wanted to make an alias persistent across sessions, where should you ideally place it (your answer should start with `~/.`)?
    - R:= ~/.bashrc

10. What command in bash is typically used to print messages to the terminal?
    - R:= echo