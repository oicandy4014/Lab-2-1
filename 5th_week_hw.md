# Standard Output
> (command) : create and save the output in a file
>> (command) : appends output to an extising file, or create and write to a new file
< (command) : redirect input from a file(can mix < and >)

#  Pipeliens
| : feeds output of previous command to input of next command

# Expansion
echo : print out the text(그대로 출력)
echo * : print all files that working
echo ~ : print usr's home directory address

# tip
\ : can be used to ignore line change to enter a long command in multiple lines

# Permissions
-rwxrwxrwx
for file owner, group owner, all other users

# Changing Permissions
chmod : changes permissions
ex) 6 = 110 = rw-for owner
    0 = 000 = --- for group
    0 = 000 = --- for others
    777 = rwxrwxrwx 
    755 = rwx-xr-x

# Superuser
has all systme administation authority
put "sudo" before the command if you are a superuser

# Text Editors
vi, vim
Emacs
nano
gedit
kwrite
(source)[https://linuxcommand.org/lc3_wss0010.php]

# Tip
history : to see previous command history or save it to a text file

# Shell Commands
wget : download files from the internet directly to your active directory
curl : fetching, uploading and managing data over the internet
ex) curl [options][URL]
grep : (Global Regular Expression Print) for searching text within files
ex) grep "search_term"file.txt
    Searches for the exact "search_term" within "file.txt" and prints matching lines
