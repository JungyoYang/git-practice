# Lab 5 201432360 YANGJUNGYO

# I/O Redirection: Standard Output

- By default, standard output is screen.
- You can redirect output using “>” after a command (e.g., ls) to create and save the output in a file
- Command “cat” displays the content of a text file.
- Using “>>” appends output to an extising file (if it already exitsts), or create and write to a new file if it doesn’t exist.

# I/O Redirection: Standard Input

- By default, standard input is from keyboard.
- You can redirecct input from a file using “<”.
- You can mix “<“ and “>” together in a single line.

# Pipelines “|”

- Pipeline feeds output of previous command to input of next command.
- command1 | command2 | command3 | …

# Expansion

- Special characters expand its meaning when given to shell commands.

# Tip: Backslash

- Backslah can be used to ignore line change in command (“enter”), to enter a long command in multiple lines.

# Permissions

- Linux is a multi-user system.
- Files and directories have a permission assigned differently to owner / group / others.

![-](https://linuxcommand.org/images/file_permissions.png)

# Changing Permissions

- “chmod” changes permissions.
- Change the permission of a file “word.txt” that only the owner (you) can read and write,
but all the others (including others in the group) can only read it. No execution is needed for all users.

# Superuser

- A superuser has all system administation authority.
- Some commands need superuser’s privilleges.
- Put “sudo” before the command if you are a superuser
- Type “exit” to get out of a superuser session.

# Text Editors

- In Linux, you can choose CLI-based or GUI-based text editors.
- Write and run a shell script
- Type “history” to see previous command history.
- Or, save it to a text file.