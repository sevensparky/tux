## There are hundreds – possibly thousands –  commands available in Linux. Remembering every command is not possible and it can be quite daunting for a novice user. The good news is that you don't need to remember each command. Only a very small subset of those commands are used on a day-to-day basis.
## This cheat sheet offers a set of commands that you can use for quick reference. I have prepared this Linux Commands Cheat Sheet as quick reference for both experienced and basic users.

<!-- ## Basic Commands -->
<!-- ### **** -->

# File Commands

### **List files in the directory**

> ls

#### **Example**: *show files in Downloads directory*

`ls Downloads/`
_____________________________


### **List all files with hidden files**

> ls -a

#### **Example**: *show all files in Documents directory*

`ls -a Documents/`
_____________________________


### **Show directory you are currently working in**

> pwd
_____________________________

### **Create a new directory**

> mkdir [directory-name]

#### **Example**: *create 'music' directory*

`mkdir music`

_____________________________

### **Remove a file**

> rm [file_name]

#### **Example**: *remove sample.txt file*

`rm sample.txt`
_____________________________


### **Remove a directory recursively**

>  rm -r [directory_name]

#### **Example**: *recursively remove 'music' directory*

`rm -r music/`
_____________________________


### **Recursively remove a directory without requiring confirmation**

> rm -rf [directory_name]

_____________________________

### **Copy the contents of one file to another file**

> cp [file1] [file2]

#### **Example**: *copy contents of file index.html to home.html*

`cp index.html home.html`

_____________________________

### **Recursively copy the contents of one file to a second file**

> cp -r [directory1] [directory2]

_____________________________
### **rename or move files and directories**

##### for rename
> mv old_file_or_directory_name new_file_or_directory_name

##### for move
> mv file_or_directory path/

#### **Example**: **

##### *rename music directory to images*
`mv music images`

##### *move 1.png directory to images directory*
`mv 1.png images/`
_____________________________
### **Create a symbolic link to a file**

> ln -s /path/to/[file_name] [link_name]

_____________________________

### **create new file**

> touch [file_name]

#### **Example**: *create index.html file*

`touch index.html`
_____________________________

### **Show the contents of a file**

> cat [file name]

#### **Example**: *display contents of index.html file*

`cat index.html`
_____________________________
### **Show the number of words, lines, and bytes in a file**

> wc

_____________________________
### **Compare two files and display differences**

> diff [file1] [file2]

#### **Example**: *compare index.html file with home.html*

`diff index.html home.html`
_____________________________
### **Read and execute the file content in the current shell**

> source [filename]

_____________________________
### **Sort file contents and print the result in standard output**

> sort [options] filename

