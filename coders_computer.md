# Coder's Computer Notes

## Classification of Editors

While all text editors get the job done, there are some things to keep in mind when chosing an editor.

**Text Editor:** software that you download to your computer, or can access online, that allows a user to write and build text such as a website

**IDE (Integrated Development Environment):** compilation of different softwares together such as a text editor, file manager, complier, and debugger. 
- Examples include: Microssoft Outlook

## What Should You Have in an Editor?

- Personal choice
- Make sure it can do what you want 
- Features to look for in a text editor:
-   Code Completion: suggest code based on what you are typing (saves lots of time!)
-   Syntax highlighting: color codes your text
-   Variety of themes: ability to change the background color of the text editor 
-   Extension selection: add-on features that will help you with your code

Some third party options include:
- NotePad++
- Atom
- Visual Studio Code

## Terminal Commands "Cheat Sheet"

**Command Line (Terminal):** text-based interface to the system that allows you to enter commands and recieve feedback

Structure of a Command Line: command + command line arguments (separated by spaces)
Options: modify the behavior of a command (typically started with a dash (-))

**Shell:** defines how the terminal will behave and look
- Most common shell is **bash (Bourne Again Shell)**
`touch` create new file

`echo` displays messages 

`pwd` (Present Working Directory):** tells you what your current working directory is

`ls` (List):** lists the contents of current directory
`- ls` (options)(location)

`-l` (Line):** indicates a long listing
- (-): normal file
- (d): directory

`/etc` tells ls to list directory's contents

### Paths

**Paths:** The means to get to a file or directory. File systems are hierarchical structures.

**root directory:** main structure at the time. Can have subdirectories. 

2 Types of paths:
 - **absolute `/`:** file or directory location in relation to the root
 - **relative:** file or directory location relative to where the user is in the system

`~` (tilde):** shortcut for home directory
`.` (dot):** references current directory
`..` (dotdot):** references the parent directory 

### Moving Around

`cd` [location]:** move around the system to another directory (change directory).
`cd ..` move back one file

### Tab Completion

Tab key = auto compete action 

## More about files

**Extensions**

file.exe - executable file
file.txt - plain text file
file.png, file.gif, file.jpg - image

`file` [path]:** used to find out what type of file it is

### Linux is case sensitve!!!

### Spaces in names

- Can have spaces in names
- Need to distinguish them from commands
-   Use Quotes ('')
-   Use Escape in between (\)

### Hidden Files and Directories

- If file or directory name begins with a (.), then it is hidden

`ls -a` make a file or directory hidden

[HOME](README.md)
