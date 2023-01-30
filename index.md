# Lab Report 1
## 1. Part 1 
* Click the link: [How to Download Vscode](https://code.visualstudio.com/). The image of the link will be like that.

 ![Image](VScodeDownload.png)


 ![Image](123.png)

* After you open a file, you should click the second button circled with red in the top right corner to open terminal.

 ![Image](12345.png)

* Next, you should click the "terminal", and put your commands at the red arrow.

 ![Image](1234567.png)

* Congraduation! You can put your commands in the right way.

 ![Image](VScode.png)



## 2. Part 2
1. Look up your course-specific account for CSE15L here: [Your Specific Account](https://sdacs.ucsd.edu/~icc/index.php).
2. You need to follow the instructions and reset the password. Here is a tutorial: [How to Reset Your Password](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit).
3. You need to open the terminal in VScode and use `ssh` to connect remotely. Your command should be like `ssh cs15lwi23zz@ieng6.ucsd.edu` and `zz` should be replaced by the letters in your course-specific account.
4. After inputing your password, if your successfully log in, your terminal will be like the following page.

![Image](RemotelyConnecting.png)

## 3. Part3
After you success in remotely connecting, you can try some commands in your terminal. There are some following commands that you can put in the terminal.

* `cd ~`
* `cd`
* `ls -lat`
* `ls -a`
* `ls <directory>` where `<directory>` is `/home/linux/ieng6/cs15lwi23/cs15lwi23abc`, where the `abc` is the letters in your course-specific account
* `cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/`
* `cat /home/linux/ieng6/cs15lwi23/public/hello.txt`

The output will be like the following image.

![Image](Commands.png)

There are some key commands that you may be confused:
* `cat <path1> <path2>` Prints the contents of one or more files given by the paths.
* `ls <path>` "List" Used to list the files and folders the given path.
* `pwd` "Print working directory" Used to display the current working directory.
* `cd <path>` "Change Directory" Used to switch the current working directory to the given path.
* `cd ~` Used to change directory to the home directory.
* `cp /home/linux/ieng6/cs15lwi23/public/hello/txt ~/` Used to copy the hello.txt of original directory to home directory.
* `ls` Used to list the components of the current directory.
* `ls -a` Used to list the components of .file of current directory.
* `ls -lat` Used to show the modify information of each file.

### That is all for the report 
