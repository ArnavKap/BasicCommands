# 🐧 Basic Linux Commands — With Uses and Examples

| Command        | Description                            | Example                         |
|----------------|----------------------------------------|---------------------------------|
| `ls`           | List files and directories             | `ls`                            |
| `ls -l`        | List with detailed info                | `ls -l`                         |
| `cd`           | Change directory                       | `cd Documents`                  |
| `cd ..`        | Go up one directory                    | `cd ..`                         |
| `cd /path`     | Go to specific directory path          | `cd /home/user/Desktop`         |
| `pwd`          | Print current working directory        | `pwd`                           |
| `mkdir`        | Create a new directory                 | `mkdir new_folder`              |
| `rmdir`        | Remove an empty directory              | `rmdir old_folder`              |
| `rm`           | Remove a file                          | `rm file.txt`                   |
| `rm -r`        | Remove directory and contents          | `rm -r project_folder`          |
| `cp`           | Copy a file                            | `cp file.txt backup.txt`        |
| `cp -r`        | Copy a directory recursively           | `cp -r folder backup_folder`    |
| `mv`           | Move or rename a file/folder           | `mv a.txt b.txt`                |
| `touch`        | Create an empty file                   | `touch notes.txt`               |
| `echo`         | Print text / write to file             | `echo "Hello" >> file.txt`      |
| `cat`          | Show contents of a file                | `cat file.txt`                  |
| `nano`         | Edit a file in nano editor             | `nano file.txt`                 |
| `clear`        | Clear terminal screen                  | `clear`                         |
| `man`          | View manual/help for a command         | `man ls`                        |
| `history`      | View command history                   | `history`                       |
| `chmod`        | Change file permissions (see below)    | `chmod u+x script.sh`           |
|-------------------------------------------------------------------------------------------|

### Variation of chmod
| Command                     | Meaning                                 | Example File Permissions   |
| --------------------------- | --------------------------------------- | -------------------------- |
| `chmod u+x file`            | Add execute permission for user         | `rwx------`                |
| `chmod g-w file`            | Remove write permission for group       | `rw-r--r--` → `rw--r--r--` |
| `chmod o=r file`            | Set read-only for others                | `rw-r--r--` → `rw-r--r--`  |
| `chmod a+x file`            | Add execute for all (user/group/others) | `rwxr-xr-x`                |
| `chmod ug=rw file`          | User & group can read/write             | `rw-rw----`                |
| `chmod u=rwx,g=rx,o=r file` | Fine-grained permission control         | `rwxr-xr--`                |
| `chmod 755 file`            | Numeric: `rwxr-xr-x`                    | Execute for all            |
| `chmod 644 file`            | Numeric: `rw-r--r--`                    | Read/write for user only   |
| `chmod 700 file`            | Numeric: `rwx------`                    | Private executable file    |
