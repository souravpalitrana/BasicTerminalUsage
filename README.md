# Basic Terminal Usage
Some basic terminal commands which you need or which is better to know as a good engineer.

## Commands for Navigationn
* `pwd` : pwd means path working directory. If you type and press enter in the terminal then it will shows your current directory path.

* `ls` : this command shows a list of all the files available in your current directory.

* `ls -lha` : Extended version of ls. It will do the same as ls but it will show other information with the list like file file size, create date, permission etc.

* `cat` : You can use this command to show the content of a file. For example, suppose in your working directory there is a file named **test.txt**. Now we want to see the content of this file. Then we will write `cat test.txt`. 

* `man` : This command is very helpfull to know the details of a command. For example we don't know what `cat` command does. So we want to know that. In that case we can write `man cat`. It is actually manual.

* `cd` : When we want to change the directory we will use this command. Suppose we have a directory which name is **test** in our current working directory. Now we want to go to this directory. In that case we can write `cd test`. Even you can specify file path here like `cd filePath`

* `cd ...` or `cd ../..` : To move two directory up
* `cd -` : It will move to the last path
* `~` : It will move you to the home directory
* `df -h` : It shows the free disk space 
* `du -sh` : It shows the disk usage of your current direcotry
* `du -sh *` : It displays the disk usage for every file and folder in that location
* arrow up or arrow down to show the last commands 


##Commands to Manage Files & Folders

* `mkdir` - To use this command you can create a new directory in your current directory. To do that write `mkdir directoryName`. For example `mkdir test`. It will create a new directory with name **test** in your current directory. To check that write `ls`. You will see your new test directory in that list.

* `touch` - To create a new file we will use this command. For example we want to create a test file named test.txt. So we will write `touch test.txt`. It will create the file with that name. To test that write `ls`. You will see the **test.txt** file in this list

* `echo` : Use to print line. For example `echo "Hello World`

* `>` : We can write line with this command. For example in the file **test.txt** we want to add a line **Hello World**. Then we can do that like this `echo "Hello World" > test.txt`. Now to check the content of the file write `cat test.txt`. **You will see our newly added line. But one important thing is if you do run the same command with different line it will overwrites the previous line. Something like replace string.**

* `>>` : It will end line at the end of the file. Something like append. Similar format than previous. As it is adding line at the end of the file so it will not overwrites previous lines.

* `nano` : Nano is one of the text editors. We can open a file like this `nano test.txt` and edit the content on the fly.
 
