# LINUX - BASIC COMMANDS

## man 
`man` manual command.

Shows you the manual for the following command. This is very helpful when trying to figure out how an unfamiliar command works. For example, type `man ls` for everything you need to know about the ls command. Type `q` to exit.
Manual.

## touch
`touch` creates file.

The touch command is used to create a file. It can be anything, from an empty txt file to an empty zip file. `touch new.txt` will create a new file with name new.

## ls
`ls` list command.

Type `ls` and the contents of the current directory will be displayed.

## cd
`cd` change directory.

`cd` followed by a directory or file path will take you inside that directory(folder).

`$ cd` - *Change to home directory*

`$ cd ~` - *Also change to home directory (~ Tilde expansion)*

`$ cd /` - *Change to root directory*

`$ cd ..` - *Change to parente directory*

`$ cd Documents/Exemple` - *Change to subdirectory*

## mkdir 
`mkdir` make directory.

This command, followed by the name you wish to name your directory, creates a new directory. `mkdir folder1` will make a new directory called folder1.

## rm 
`rm` remove.

This command removes files, not directories. `rm file.txt` will remove the file named file.txt as long as it exists and is in the current directory.

`$ rm file` - *Remove the file*

`$ rm -Rf directory` - *Remove the diretory and their cotents* 

`-Rf --recursive --force`

## mv
`mv` move

Use the mv command to move files through the command line. We can also use the `mv` command to *rename* a file. For example, if we want to rename the file “text” to “new”, we can use `mv text new`.

`-f` *force move by overwriting destination file without prompt*

`-i` *interactive prompt before overwrite* 

`-u` *update - move when source is newer than destination*

`-v` *verbose - print source and destination files*

## chown
`chown` change owner.

## pwd 
`pwd` print working directory

Type `pwd` to display the path to your current directory.

## whoami
`whoami` who am i?

## df
`df` reporting file system disk.

`-h` flag *human readable format*

## ln 
`ln -s` creates a symbolic link to file target with the name LINKNAME.

```
$ ln -s file.txt file2.txt
```

## which
`which` is used to locate the executable file.
```
$ which python` output `/usr/bin/python
```
## tail
`tail` output the last part of file given.

```
$ tail [options] file
```
`-f` flag *watch a file changes*

## less 
`less` view file content

Use `less filename.txt` to view contents of a file and navigate through them. By default, less will go through the file page by page.

## pipe 
```
ps aux | ag palavra
ps aux | ag palavra | awk '{print $2}'
```

## grep
`grep` globally search a regular expression and print.

## silversearcher-ag
Do the same of grep

## Terminal - tmux

`$ tmux ls` *list sessions*

`$ tmux attach-session -t session-number` *get session*

`$ tmux kill-session -t session-number` *destroy sessions*

more [about tmux](https://gist.github.com/MohamedAlaa/2961058) 


## Linux Resources

[Free Code Camp](https://guide.freecodecamp.org/linux)



[bash scripting cheatsheet](https://devhints.io/bash)
