[Home](README.md) || [My GitHub](https://github.com/leahgrace555) || [The Growth Mindset](thegrowthmindset.md) || [Learning Markdown](blogpost1.md) || [Text Editors](blogpost2.md)|| [Terminal Cheatsheet](terminalcheatsheet.md) || [Guide to Git](blogpost3.md) || [Structure & HTML](blogpost4.md) || [Styling Webpages](blogpost5.md) || [Javascript](blogpost6.md) || [How Computers Work](blogpost6b.md)

# Terminal Cheat Sheet

### 1. Paths
- Two types of paths: absolute and relative
- Absolute paths specify a file location with respect to the root directory.
- Relative paths specify a file in relation to where you are currently located in the file system. 

Some examples are as follows:

1.  ~(tilde) shortcut for the home directory eg. /home/me/documents = ~/documents
2.  .(dot) refers to the current location eg ./documents
3.  ..(dot dot) references a parent directory



### Useful Commands

- **Shortcut History:** Tapping the up arrow in some terminals can cycle through a list of commands you have previously used. 
- **pwd:** Print working directory. This shows you your current location in the file system. This is important since certain commands will only work if you are in the correct location. It can run without any arguments.
- **ls:** Short for list. Use argument -a to show hidden files. 
- **cd:** Is used to move locations. (short for change directory). When run without arguments it will take you to the home directory. For example, cd ~/Documents will take you to /Home/Me/Documents

### About Files

 - Linux is an extensionless system, while Windows uses file extensiosn to determine file types. 
  - The command ` File [path] ` will tell you what type a file is in Linux.
- Linux is case sensitive when refering to files, while Windows is not.
- Spaces in file names can sometime cause "confusion". To ensure that spaces in file and directory names are interpreted correctly, place a backslash before it, or place quotes around the file name. 

for example, my home folder is called 'NyanCat Leah"
to refer to it, I would use: /Users/NyanCat\ Leah OR "NyanCat Leah"

- Hidden files begin with a . (full stop). These are usually located in a user's home directory and are hidden to avoid getting in the way of regular user tasks. 

