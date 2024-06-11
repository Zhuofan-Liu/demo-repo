# basic operation
- ls #list the content of the directory
- more cobras #For example, to see the contents of the "cobras" file, you would type it
- mkdir dogs #short for "make directory"
- mv wovles dogs #to move a file called "wolves" into directory "dogs"
- mv wolves coyotes #Renaming files is simply a case of "moving" a file from one name to another. For example, to rename file "wolves" to "coyotes"
- cd primates #change directory 
- pwd #short for "print working directory"
- cd .. #To change to your previous directory (also known as the "parent" directory), you need to use a special "argument" to the "cd" command.

# remainder of the basic operation
## change pathname
### scenario 1: full pathname with root directory
mv /animals/cats/tigers /animals/cats/siberians
### scenario 2: relative pathname if current directory is parent directory("animal")
mv cats/tigers cats/siberians 
### scenario 3: relative pathname if current diretory is another subdictionary
mv ../cats/tigers ../cats/siberians #" .."stands for the parent dictionary

## copy and paste file and folder
cp reptiles/cobras snakes # similar to mv, copy a file
cp -r reptiles/cobras snakes #copy a folder

## remove a (non)-empty file and directory
rm reptiles/cobras #remove empty file
rmdir reptiles #remove empty dictionary
rmdir -r reptiles #remove non-empty directory and its content

## change file permissions
chmod ugo-rwx gorillas; chmod ugo+rwx gorillas # u(user); g(group); o(other); r(read); w(write); x(execute) 

## wildcard
- "*" The '*' matches any number of characters. For example, if you want to execute a command on all files in the current directory, you would specify '*' as the filename. If you want to be more selective and match only files which end in "ing", you would use "*ing". Note that the '*' can even match zero characters, so "*ing" would match "ing" as well as "sing".
- The other wildcard, '?', is not used very often, but it can be useful. It matches exactly one character. For example, if you want to match "sport", but not "spat", you would use "sp??t". The first '?' matches the 'a' in "spat", but the second '?' can't match anything, so "spat" fails.

## list the groups you are in
groups

## concatenate(Read/Display)
cat filel.txt #quickly view a file

## clear
clear #clear the terminal screen

# vs code & git
git stauts #check the file is untracked, changed and so on.
git add "filename" #save a certain file, "" is needed
git add . #save all of the changes just made, including track the new file, modified section and etc.
git commit -m "Create a file" -m "file description" #this option is like what we do in github, you need to add these two piece of info to commit the creation of a new file.
