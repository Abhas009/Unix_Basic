# Unix Commands

## Popular Commands

1. **ls**: List directory contents.
   - Syntax: `ls [options] [file]`
   - Example: `ls -l`

2. **cd**: Change the current directory.
   - Syntax: `cd [directory]`
   - Example: `cd Documents`

3. **pwd**: Print the current working directory.
   - Syntax: `pwd`

4. **mkdir**: Create a new directory.
   - Syntax: `mkdir [directory]`
   - Example: `mkdir new_folder`

5. **rm**: Remove files or directories.
   - Syntax: `rm [options] [file]`
   - Example: `rm file.txt`

6. **cp**: Copy files or directories.
   - Syntax: `cp [options] source destination`
   - Example: `cp file1.txt file2.txt`

7. **mv**: Move or rename files or directories.
   - Syntax: `mv [options] source destination`
   - Example: `mv file1.txt file2.txt`

8. **cat**: Concatenate and display files.
   - Syntax: `cat [file]`
   - Example: `cat file.txt`

9. **grep**: Search for a pattern in files.
   - Syntax: `grep [options] pattern [file]`
   - Example: `grep "pattern" file.txt`

10. **echo**: Display a line of text.
    - Syntax: `echo [text]`
    - Example: `echo "Hello, World!"`

11. **chmod**: Change file permissions.
    - Syntax: `chmod [options] mode file`
    - Example: `chmod 644 file.txt`

12. **chown**: Change file owner and group.
    - Syntax: `chown [options] owner:group file`
    - Example: `chown user:group file.txt`

13. **ps**: Display information about active processes.
    - Syntax: `ps [options]`
    - Example: `ps aux`

14. **top**: Display and update sorted information about processes.
    - Syntax: `top`

15. **kill**: Terminate processes by ID or name.
    - Syntax: `kill [options] pid`
    - Example: `kill 1234`

16. **ssh**: Connect to a remote machine.
    - Syntax: `ssh [user@]hostname`
    - Example: `ssh user@example.com`

17. **scp**: Copy files between hosts securely.
    - Syntax: `scp [options] source destination`
    - Example: `scp file.txt user@example.com:/path/to/destination`

18. **wget**: Download files from the web.
    - Syntax: `wget [options] URL`
    - Example: `wget https://example.com/file.txt`

19. **tar**: Archive files.
    - Syntax: `tar [options] [file]`
    - Example: `tar -czvf archive.tar.gz directory`

20. **man**: Display the manual page for a command.
    - Syntax: `man [command]`
    - Example: `man ls`

## Command Line Techniques

- **Alt + Command**: Use the Alt key in combination with other keys to access various functions in the terminal.
- **Ctrl + A**: Go to the start of the command line.
- **Ctrl + E**: Go to the end of the command line.
- **Ctrl + U**: Delete from the cursor to the beginning of the line.
- **Ctrl + K**: Delete from the cursor to the end of the line.
- **Ctrl + L**: Clear the screen.
- **Tab completion**: Press Tab to autocomplete commands, file names, or directories.
- **History navigation**: Use the up and down arrow keys to navigate through previously entered commands.
- **Command chaining**: Use operators like `|` (pipe), `&&` (logical AND), and `||` (logical OR) to chain multiple commands together.

## Monday Morning Mistake

- **Monday Morning Mistake**: A humorous term used to describe accidentally executing a destructive command, such as `rm -rf /`, which can result in deleting all files and directories on the system. Always be cautious when using powerful commands and double-check before executing them.
