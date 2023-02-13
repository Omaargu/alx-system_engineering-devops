*echo "Hello, World":print whats written
*echo "\"(Ôo)'" : display confused smiley
*cat /etc/passwd : display content
*cat file file : dispaly content of two files
*tail -n number of lines: display last lines of indicated number
*head -n number : displays first lines of indicated number
*head -n number | tail -n number : dispalys a specific line depending on the number written in head command
*echo Best school > '\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)':to create a file that has weird name
*ls -la >> file : Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it
*tail -n 1 iacta >> iacta:Write a script that duplicates the last line of the file iacta
find . -type f -name '*.js' -delete : delete all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders
*find . -type d -not -name . | wc -l : Write a script that counts the number of directories and sub-directories in the current directory.

    The current and parent directories should not be taken into account
    Hidden directories should be counted
*ls -t1 | head -n number : Create a script that displays the 10 newest files in the current directory.

Requirements:

    One file per line
    Sorted from the newest to the oldest
*sort | uniq -u :Create a script that takes a list of words as input and prints only words that appear exactly once.

    Input format: One line, one word
    Output format: One line, one word
    Words should be sorted
*grep -E :Display lines containing the pattern “root” from the file /etc/passwd
*grep -E "bin" /etc/passwd | wc -l : Display the number of lines that contain the pattern “bin” in the file /etc/passwd
*grep -EA 3 "root" /etc/passwd:Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
*grep -v "bin" /etc/passwd: Display all the lines in the file /etc/passwd that do not contain the pattern “bin”
grep -E "^[[:alpha:]]" /etc/ssh/sshd_config: Display all lines of the file /etc/ssh/sshd_config starting with a letter.

    include capital letters as well
 
