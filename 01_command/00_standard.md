# Standard

## Directories & Files

* `ls <dir | file>`: *list* files 

* `cd [dir]`: *change directory*
* `pwd`: *print working directory*
* `rm <file>` `: *remove* a file
  * `rm -f <file>`: force remove with out ask
  * `rm -r <dir | file>`: remove directories and their contents recursively
  * `rm -i <file>`: prompt before every removal
* `mv <dir | file> <destination>`: move file or directory to a destination file or directory
* `cp <source_file> <dest_file>`: copy file from source to destination.
  
  * `cp -r <source_dir | source_file> <dest_dir | dest_file>`: copy recursively

## Print

* `cat <file>`:  concatenate files and print on the standard output
  * `cat -n <file>`: number all output lines

* `echo <text>`: display a line of code
  * `echo -e <text>`: enable interpretation of backslash escapes
  * `echo -n <text>`:  do not output the trailing newline


## Search

* `grep`: *global regular expressions print*
  * `grep -E` == `egrep`
* `egrep`: *extended global regular expressions print*
  * `egrep -v '^#|^$'`: delete comments (#) and new lines

## Package

*  `tar`:
  * `tar xvzf <file.tar.gz>`: extract all the files under the current directory
    * `x`: extract
    * `v`: verbose
    * `z`: gzip
    * `f`: file

