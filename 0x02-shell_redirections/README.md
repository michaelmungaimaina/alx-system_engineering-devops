# Task 0
 - A script that prints hello world followed by a new line to the standard output. '0-hello_world'
# Task 1
 - A  script that displays a confused smiley "(Ôo)'.
# Task 2
 - A script that displays the content of the /etc/passwd file.
# Task 3
 - A script that displays the content of /etc/passwd and /etc/hosts.
# Task 4
 - A script that displays the last 10 lines of /etc/passwd
# Task 5
 - A script that displays the first 10 lines of /etc/passwd
# Task 6
 - A script that displays the third line of the file iacta.

The file iacta will be in the working directory

    You’re not allowed to use sed
# Task 7
 - A script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
# Task 8
 - A script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
# Task 9
 - A script that duplicates the last line of the file iacta

    The file iacta will be in the working directory
# Task 10 
 - A script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
# Task 11
 - A script that counts the number of directories and sub-directories in the current directory.

    The current and parent directories should not be taken into account
    Hidden directories should be counted
# Task 12
 - A script that displays the 10 newest files in the current directory.

Requirements:

    One file per line
    Sorted from the newest to the oldest
# Task 13
 - A script that takes a list of words as input and prints only words that appear exactly once.

    Input format: One line, one word
    Output format: One line, one word
    Words should be sorted
# Task 14
 - A script that displays lines containing the pattern “root” from the file /etc/passwd
# Task 15
 - A script that displays the number of lines that contain the pattern “bin” in the file /etc/passwd
# Task 16 
 - A script that displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
# Task 17
 - A script that displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.
# Task 18
 - Ascript that displays all lines of the file /etc/ssh/sshd_config starting with a letter.

    include capital letters as well
# Task 19 
 - A script that replaces all characters A and c from input to Z and e respectively.
# Task 20
 - A script that removes all letters c and C from input.
# Task 21 
 - A script that  reverses its input
# TAsk 22 
 - A script that displays all users and their home directories, sorted by users.

    Based on the the /etc/passwd file
# ADVANCED TASKS #
# Task 23
 - A script that  finds all empty files and directories in the current directory and all sub-directories.

    Only the names of the files and directories should be displayed (not the entire path)
    Hidden files should be listed
    One file name per line
    The listing should end with a new line
    You are not allowed to use basename, grep, egrep, fgrep or rgrep
# Task 24 
 - A script that lists all the files with a .gif extension in the current directory and all its sub-directories.

    Hidden files should be listed
    Only regular files (not directories) should be listed
    The names of the files should be displayed without their extensions
    The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
    One file name per line
    The listing should end with a new line
    You are not allowed to use basename, grep, egrep, fgrep or rgrep
# Task 25
 - An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. Read more.

Create a script that decodes acrostics that use the first letter of each line.

    The ‘decoded’ message has to end with a new line
    You are not allowed to use grep, egrep, fgrep or rgrep
# Task 26
 - A script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

    Order by number of requests, most active host or IP at the top
    You are not allowed to use grep, egrep, fgrep or rgrep
   
