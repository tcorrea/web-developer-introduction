# LINUX - BASIC TERMINAL COMMANDS

### `man`
Manual.
- exemple
    - `man touch`

### `touch`

### `ls`
List directories and files.
*syntax* *`$ ls [options] [file|dir]`*
- options
    - `ls -a` *list all files (including hidden file)*
    - `ls -l` *list with long format - show permissions*
    - `ls -la` *list long format including hidden files*


### `cd`
Change Directory.
*syntax* *`$ cd [directory]`*
- exemples
    - `$ cd` - *Change to home directory*
    - `$ cd ~` - *Also change to home directory (~ Tilde expansion)*
    - `$ cd /` - *Change to root directory*
    - `$ cd ..` - *Change to parente directory*
    - `$ cd Documents/Exemple` - *Change to subdirectory*

### `mkdir`
Make Directories.
*syntax* *`$ mkdir [options] [directory]`*

### `rm`
Remove - Removes each file specified on the command line. By default, it does not remove directories.
*syntax* *`$ rm [options] [file | directory]`*
- exemple
    - `$ rm file` - *Remove the file*
    - `$ rm -Rf directory` - *Remove the diretory and their cotents* 
    - `-RF = --recursive --force`

### `mv`
mv command moves and renames files and directories.
*syntax* *`mv [options] source destination`* 
- options
    - `-f` *force move by overwriting destination file without prompt*
    - `-i` *interactive prompt before overwrite* 
    - `-u` *update - move when source is newer than destination*
    - `-v` *verbose - print source and destination files*

### `chown`
change owner

### `pwd` 
print working directory

### `whoami` 
who am i?

### `df` 
reporting file system disk.
- options
    - `-h` *human readable format*

### `ln -s` 
creates a symbolic link to file target with the name LINKNAME.
- exemple
    - `$ ln -s file.txt file2.txt`

### `which` 
is used to locate the executable file.
- exemple
    - `$ which python` output `/usr/bin/python`

### `tail`
output the last part of file given.
*syntax* *`tail [options] file`*
- options
    - `-f` *watch a file changes*

## Environment Variable
`$HOME`
`$PATH` 

## Read Files
`less` *is a command that displays file contents*

## Pipe |
ps aux | ag palavra
ps aux | ag palavra | awk '{print $2}'

## Grep
globally search a regular expression and print.

- silversearcher-ag
    - do the same of grep

## Terminal - tmux
- exemple
    - `$ tmux ls` *list sessions*
    - `$ tmux attach-session -t session-number` *recupera session*
    - `$ tmux kill-session -t session-number` *destroy sessions*
    - more [about tmux](https://gist.github.com/MohamedAlaa/2961058) 

//TODO
echo "texto" > file.txt - sobre escreve o arquivo
echo "texto" >> file.txt - append no final do arquivo

bash scripting cheatsheet
sudo service redis-server stop / start / status
sudo service postgresql stop / start / status