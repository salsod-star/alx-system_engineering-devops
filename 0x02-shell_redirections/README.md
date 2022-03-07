# Shell Redirections Commands
This is the continuation of the basic shell command and shell permissions in the previous project. Today, we will be treating some of the various way in which we can manipulate files using the knowledge of standard input and standard output provided in the command line, creating a script for the command line and making it executable. This script will then be examined and validated by Ubuntu 20.04 LTS
## Let's begin - some of the commands is as shown below.
| Files | Descriptions |
| ----- | ------------ |
| **0-hello\_world** | This file uses the command `echo 'Hello, World'`to the standard output.
| **1-confused_smiley** | This uses `echo` command to display a confused image to the output.
| **2-hellofile** | This uses the `cat` command to display the content of `/etc/passwd`.
| **3-twofiles** | The `cat` command can also be used to display the content of multiple of files. It displays the content of both files located in the `/etc/passwd` and `/etc/hosts`.
| **4-lastlines** | Using the `tail -n number filename` to display the last specified `number` of last lines.
| **5-firstlines** | This uses the `head` command and it works exactly like the `tail` command but instead of displaying the last number of lines, it displays the first number of lines.
| **6-third_line** | This script displays the third line of the file
| **7-file** | This creates named file with string of special character.
| **8-cwd_state** | This takes the output of the command `ls -la` and input it into the `ls_cwd_content` file.
| **9-duplicate_last_line** | The command `tail` is used again with `>>` to take the last line of text and append it to the same filename.
| **10-no_more_js** | This script delete all the `.js` files in the current directory and all its sub-directories.
| **11-directories** | This counts the directories and all the sub-directories in the current directory
| **12-newest_files** | This is a script that display the 10 newest files in the current directory.

