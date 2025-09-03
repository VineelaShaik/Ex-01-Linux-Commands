# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls<br>
 
 <img width="939" height="65" alt="Screenshot 2025-09-03 102938" src="https://github.com/user-attachments/assets/624ae863-335c-487d-9ebd-8b3a29f47d50" />



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd<br>

<img width="937" height="62" alt="Screenshot 2025-09-03 103249" src="https://github.com/user-attachments/assets/ddf259ca-45df-4a3f-81ef-7337ffbd638d" />


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name><br>

<img width="940" height="49" alt="Screenshot 2025-09-03 103318" src="https://github.com/user-attachments/assets/1db4be74-84c5-4aa2-adca-2cf281b69ce7" />



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name><br>

<img width="938" height="47" alt="Screenshot 2025-09-03 103347" src="https://github.com/user-attachments/assets/c3fd0dd9-138c-4c93-9783-06ee69e4a2cc" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name><br>

<img width="930" height="44" alt="Screenshot 2025-09-03 103421" src="https://github.com/user-attachments/assets/7e5ea6e5-d4a3-466a-9455-59bb54def954" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..<br>

<img width="934" height="60" alt="Screenshot 2025-09-03 103502" src="https://github.com/user-attachments/assets/8a3c4002-c106-434d-8499-07435c74c36d" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name><br>

<img width="929" height="95" alt="Screenshot 2025-09-03 103535" src="https://github.com/user-attachments/assets/88ef78b0-03ac-490d-931b-1151361c546c" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name<br>

<img width="800" height="42" alt="Screenshot 2025-09-03 142602" src="https://github.com/user-attachments/assets/b3851b60-3746-4e90-8de8-65adf330b101" />



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name><br>

<img width="827" height="58" alt="Screenshot 2025-09-03 142756" src="https://github.com/user-attachments/assets/d72c1657-4f6d-4818-b46a-6c7386b16aac" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path><br>

<img width="833" height="40" alt="Screenshot 2025-09-03 142852" src="https://github.com/user-attachments/assets/aa0d793b-eeb3-4074-b9f8-f9efe67c557f" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files<br>

<img width="804" height="110" alt="Screenshot 2025-09-03 143545" src="https://github.com/user-attachments/assets/0af62f57-9918-42ca-9923-411576320eb1" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name><br>

<img width="528" height="260" alt="Screenshot 2025-09-03 143816" src="https://github.com/user-attachments/assets/d49503bf-c676-4470-9111-df48c558a8fd" />



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name><br>

<img width="548" height="201" alt="Screenshot 2025-09-03 143902" src="https://github.com/user-attachments/assets/747e1e55-44a7-4ff2-b21b-d640ce0a57af" />

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id<br>

<img width="953" height="87" alt="Screenshot 2025-09-03 143948" src="https://github.com/user-attachments/assets/48828afc-5627-43dd-a5cb-afb1c14c526e" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word><br>

<img width="752" height="65" alt="Screenshot 2025-09-03 144042" src="https://github.com/user-attachments/assets/0bc34078-8cd1-414e-bd0b-9fb5b39f31c3" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'><br>

<img width="639" height="203" alt="Screenshot 2025-09-03 144145" src="https://github.com/user-attachments/assets/3c1cc3b8-0606-4865-b277-ac6939059950" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name><br>
<img width="721" height="113" alt="Screenshot 2025-09-03 144252" src="https://github.com/user-attachments/assets/f67450e3-4087-43af-b3c3-869cf9a745c0" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c<br>

<img width="547" height="153" alt="Screenshot 2025-09-03 144434" src="https://github.com/user-attachments/assets/7fd202ab-7795-490f-8820-a7e098ffba2e" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name<br>

<img width="833" height="107" alt="Screenshot 2025-09-03 144616" src="https://github.com/user-attachments/assets/79e11197-2e02-43a5-aad9-50fc6b9fb7c8" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….<br>

<img width="764" height="59" alt="Screenshot 2025-09-03 151249" src="https://github.com/user-attachments/assets/780bee79-f1e3-411e-beb3-c55ec88a2795" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]<br>

<img width="818" height="95" alt="Screenshot 2025-09-03 151332" src="https://github.com/user-attachments/assets/3882b106-64dc-4f12-8d3a-220c94f199fc" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder<br>
<img width="739" height="114" alt="Screenshot 2025-09-03 152435" src="https://github.com/user-attachments/assets/5dd1ed97-2f37-4357-ad60-65d6332acf8d" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address><br>

<img width="793" height="105" alt="Screenshot 2025-09-03 152703" src="https://github.com/user-attachments/assets/03d6331c-0d58-45ea-b589-9272a3964e40" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..<br>
<img width="916" height="159" alt="Screenshot 2025-09-03 152823" src="https://github.com/user-attachments/assets/1b169196-9819-4406-b034-dbc1b2ca65e7" />



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name><br>

<img width="777" height="219" alt="Screenshot 2025-09-03 153044" src="https://github.com/user-attachments/assets/8b3a3f03-e93e-4c58-a5f8-df80f5aaf09d" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal<br>

<img width="632" height="166" alt="Screenshot 2025-09-03 153135" src="https://github.com/user-attachments/assets/2cc2f72b-2a31-405d-9276-1fb690cebb15" />



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear<br>

<img width="753" height="57" alt="Screenshot 2025-09-03 153217" src="https://github.com/user-attachments/assets/f8297daf-b1c0-47af-a458-2cbb79f51b52" />
<img width="767" height="82" alt="Screenshot 2025-09-03 153238" src="https://github.com/user-attachments/assets/d77166ed-aba5-432d-93cf-5ac50b3d2b9d" />



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address><br>

<img width="772" height="103" alt="Screenshot 2025-09-03 153716" src="https://github.com/user-attachments/assets/aec687fc-f12c-4660-9731-826ac3217329" />


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df<br>

<img width="868" height="215" alt="Screenshot 2025-09-03 153747" src="https://github.com/user-attachments/assets/0b71a117-5957-4534-a949-4c219ec87938" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”<br>

<img width="747" height="244" alt="Screenshot 2025-09-03 153819" src="https://github.com/user-attachments/assets/b9d0a156-8d8c-400e-9bf7-9779f310d218" />





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
