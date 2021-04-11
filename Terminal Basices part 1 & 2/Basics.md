# Terminal Basics Exercises PART II

1. It ask you the manual page you want to navigate to. (rm) removes each specified file. By default, it does not remove directories

2.ls command, we can pass in the -a flag to list "all" files (including hidden files and folders)

6.In order to change a directory, type cd followed by the directory or a path to the directory. If we want to move up a directory we use cd .. and if we want to move into a directory we specify the name of the directory we are moving into. For example, if you are in your home directory and type cd Desktop, you should move into your Desktop directory.

7.CTRL+a

8.CTRL+e.

9.CTRL+u Cut/delete 10. A terminal refers to a wrapper program which runs a shell. Decades ago, this was a physical device consisting of little more than a monitor and keyboard. As unix/linux systems added better multiprocessing and windowing systems, this terminal concept was abstracted into software.
While the shell is the program which actually processes commands and returns output. Most shells also manage foreground and background processes, command history and command line editing. These features (and many more) are standard in bash, the most common shell in modern linux systems. (We are using zsh).

10.A path is either relative or absolute.

11.An absolute path always contains the root element and the complete directory list required to locate the file

12.Flags are usually represented by single uppercase and lowercase letters. With the ls command, we can pass in the -a flag to list "all" files (including hidden files and folders).
1.ls
2.-l 2.
3.la.

13.For example if a file is unwritable, rm will prompt you whether to remove that file or not, to avoid this and simply execute the operation. When you combine the -r and -f flags, it means that recursively and forcibly remove a directory (and its contents) without prompting for confirmation
