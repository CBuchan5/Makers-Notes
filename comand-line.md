Create a new directory – mkdir directory name 

Add files to the new directory – touch filename  

Move a file into a different directory- mv … filetomove directorytomove 

Rename a file-  mv newFile newerFile 

Remove a single file rm file name 

Remove a directory - rmdir directory name 

To copy a file – copy filename destination of new file if needed 

Remove a directory that contains files (be very careful doing this!) -  rm -r directory name 

Use less, cat, head and tail to view the contents of files 

head- top section of text 
tail- last few lines of text 
less- scroll through large volumes of text 
cat-combining text files (concatenate) 

man ls – gives me a list of information on the ls command 

ls- a list 

wc- word count 

| - pipe merges commands (passes the output stream (what would normally be printed on the screen) of the command to the left of the pipe to the input stream of the command on the right). ls -lA | less 

Changing permissions - chmod u+w readme.txt  
Code Order- chmod (the command) u+w (user give writing permission) file permission to write in 

U, g and o – u= user, g=group and o=others 

Wildcards- find ~ -name "*.txt" -print | grep README 
find ~ -name "*.txt" -print  
Order meaning- command then name file style print to screen 

command then name file style print to screen and grep(find within a file) and the file you want to look in  

Shebang – make command line read ruby 

Find any env variable (environmental variables) - echo $ENV_VAR (eg echo $HOME) 

Echo- can also be used to save short strings to a file echo "Hello, world" > hello.txt 

echo $PATH - colon-separated list of directories where the shell will be looking for the programs you ask it to run 
 
export SEASON=winter – setting environment variables 
echo $SEASON to call it back and check env variable  

ps- processes I’ve launched  