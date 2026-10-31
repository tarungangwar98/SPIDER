Assignment 3 – Terminal Navigation Practice

In this assignment I practiced the basic terminal commands for moving around folders and handling files. I tried them in the VS Code terminal. The commands are for Git Bash / macOS / Linux, and in PowerShell a few of them are different.

Commands I practiced
#	What it does	Command	PowerShell
1	Shows the folder I am in	pwd	pwd
2	Lists files	ls	ls
3	Lists files with details and hidden files	ls -la	ls -Force
4	Makes a new folder	mkdir practice	mkdir practice
5	Goes inside the folder	cd practice	cd practice
6	Makes an empty file	touch index.html	ni index.html
7	Makes folder inside folder	mkdir -p css/images	mkdir css/images
8	Goes back one level	cd ..	cd ..
9	Goes to home directory	cd ~	cd ~
10	Copies a file	cp index.html backup.html	cp index.html backup.html
11	Renames or moves a file	mv backup.html old.html	mv backup.html old.html
12	Deletes a file	rm old.html	rm old.html
13	Deletes a folder	rm -r css	rm -r css
14	Shows what is inside a file	cat index.html	cat index.html
15	Clears the screen	clear	cls
16	Opens the folder in VS Code	code .	code .
Practice exercise

I started from my home directory and did these steps:

	1.	First I went to the home directory:
cd ~
	2.	Then I made the website folder with css and images folders inside it:
mkdir -p website/css website/images
	3.	Then I made the files:
touch website/index.html website/css/style.css
	4.	Then I went into the css folder:
cd website/css
	5.	To come back to the website folder I used:
cd ..
	6.	To see all files and folders together I used:
ls -R
	7.	I renamed index.html to home.html, then changed it back:
mv index.html home.html
mv home.html index.html
	8.	In the end I opened the folder in VS Code:
code .
