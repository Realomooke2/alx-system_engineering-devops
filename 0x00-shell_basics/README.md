# 0x00. Shell, basics

### The shell is a command-line interface (CLI) program that provides a way to interact with a computer's operating system through textual commands. The most popular shell is Bash (Bourne Again SHell), which is the default shell for most Linux distributions.

### When using the shell, commands are entered one at a time, and the shell executes each command and returns a result. Common shell commands include navigating the file system (cd, ls), creating and editing files (touch, nano), managing processes (ps, kill), and more.

### Shell commands can be combined and piped together to perform more complex operations. For example, the output of one command can be used as the input for another command using the pipe symbol (|).

### The shell also provides features like command-line completion, history, and tab completion to make it easier to use. These features can save time and make it easier to navigate the shell.

### Overall, understanding the basics of the shell is an important skill for anyone who wants to work with Linux or other Unix-like operating systems.

# Resources
## [Read or watch:

- [What Is “The Shell”?,(https://linuxcommand.org/lc3_lts0010.php)]
- [Navigation(https://linuxcommand.org/lc3_lts0020.php)]
- [Looking Around(https://linuxcommand.org/lc3_lts0030.php)]
- [A Guided Tour(https://linuxcommand.org/lc3_lts0040.php)]
- [Manipulating Files(https://linuxcommand.org/lc3_lts0050.php)]
- [Working With Commands(https://linuxcommand.org/lc3_lts0060.php)]
- [Reading Man pages(https://linuxcommand.org/lc3_man_pages/man1.html)]
- [Keyboard shortcuts for Bash(https://www.howtogeek.com/181/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/)]
- [LTS(https://wiki.ubuntu.com/LTS)]
- [Shebang(https://en.wikipedia.org/wiki/Shebang_%28Unix%29)]


## 0. Where am I
	
- Write a script that prints the absolute path name of the current working directory.

## 1. What's in there?

- Display the contents list of your current directory.

## 2. There is no place like home

- Write a script that changes the working directory to the user’s home directory.

- You are not allowed to use any shell variables.

## 3. The long format

- Display current directory contents in a long format.

## 4. Hidden files

- Display current directory contents, including hidden files (starting with .). Use the long format.

## 5. I love numbers.

- Display current directory contents.
- Long format
- with user and group IDs displayed numerically
- And hidden files (starting with .)

## 6. Welcome holberton

- Create a script that creates a directory named my_first_directory in the /tmp/ directory.

## 7. Betty in Holberton

-Move the file betty from /tmp/ to /tmp/my_first_directory.

## 8. Bye bye Betty

- Delete the file betty.
-The file betty is in /tmp/my_first_directory.

## 9. Bye bye Holberton.

- Delete the directory my_first_directory that is in the /tmp directory.

## 10. Back to the future.

- Write a script that changes the working directory to the previous one.

## 11. Lists.

- Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

## 12. File type.

- Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory 	when we will run your script.

## 13. We are symbols, and inhabit symbol.

- Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working dire	ctory.

## 14. Copy HTML files.

- Create a script that copies all the HTML files from the current working directory to the parent of the working directory, butonly copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
- You can consider that all HTML files have the extension .html

## 15. Let’s move.

- Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
- You can assume that the directory /tmp/u will exist when we will run your script.

## 16. Clean Emacs.

- Create a script that deletes all files in the current working directory that end with the character ~.

## 17. Tree

- Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
- You are only allowed to use two spaces (and lines) in your script, not more.

## 18. Life is a series of commas, not periods

- Write a command that lists all the files and directories of the current directory, separated by commas (,).
- Directory names should end with a slash (/)
- Files and directories starting with a dot (.) should be listed
- The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
- Only digits and letters are used to sort; Digits should come first
- You can assume that all the files we will test with will have at least one letter or one digit
- The listing should end with a new line.

## 19. File type: Schoo

- Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
