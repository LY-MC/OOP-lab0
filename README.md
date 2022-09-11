# OOP-lab0

## Task 1 - Installing Ubuntu. 
I decided to install it as dual-boot. 
Here are some screenshots of installing it.
![photo_2022-09-11_12-01-39](https://user-images.githubusercontent.com/88684853/189519701-216dde11-6b62-4d95-9c25-9258bcfc1792.jpg)

![photo_2022-09-11_12-01-41](https://user-images.githubusercontent.com/88684853/189519722-38f3d27a-4f2d-48fc-9794-7f86eb2feb24.jpg)

I chose "Something else" because I shrink free space for Ubuntu.
![photo_2022-09-11_12-01-43](https://user-images.githubusercontent.com/88684853/189519725-233a9994-2198-48b6-a2f9-ece5633198ba.jpg)

Then I devided free space to 3 parts: main (for OS), home (for pictures, documents and more) and swap area (virtual memory)
![photo_2022-09-11_12-01-45](https://user-images.githubusercontent.com/88684853/189519930-3eeb03fe-4c4c-48f6-8ed4-7faa4e8bbd29.jpg)

![photo_2022-09-11_12-01-46](https://user-images.githubusercontent.com/88684853/189519931-7894d2be-8980-4052-a0c0-80dbfe7e784e.jpg)

![photo_2022-09-11_12-01-48](https://user-images.githubusercontent.com/88684853/189519932-00abc31a-bc7f-47bd-bee1-3a704dab92d2.jpg)

That's how I have installed Ubuntu.

## Task 2 - Installing essential tools. 

sudo, which is an acronym for superuser do or substitute user do, is a command that runs an elevated prompt without a need to change your identity. 

apt-get is a command line tool for interacting with the Advanced Package Tool (APT) library (a package management system for Linux distributions). It allows you to search for, install, manage, update, and remove software

I installed git: 
![Screenshot from 2022-09-08 21-47-33](https://user-images.githubusercontent.com/88684853/189520209-1415c7ab-b021-4c77-ba34-4d2a094ccefd.png)

zsh:
![Screenshot from 2022-09-08 21-51-18](https://user-images.githubusercontent.com/88684853/189520211-ba85b0a1-e584-4c04-a920-0a098892dabf.png)

oh-my-zsh:
![Screenshot from 2022-09-08 21-59-44](https://user-images.githubusercontent.com/88684853/189520212-0ab03c9e-9ec7-4a5f-a62f-f955016179b0.png)

theme and plugins for oh-my-zsh:
![Screenshot from 2022-09-10 17-13-37](https://user-images.githubusercontent.com/88684853/189520213-f542a3cc-08d2-4ddd-bc21-bca5597b33f5.png)

I chose Eastwood theme for it’s simplicity.
You see the git branch and the directory you’re in. That’s all I need.
![Screenshot from 2022-09-10 17-15-44](https://user-images.githubusercontent.com/88684853/189520214-3fbfaa62-b9de-4528-9404-c82e4b13c062.png)

My plugins:

1. zsh-autosuggestions
Fish-like fast/unobtrusive autosuggestions for zsh.
It suggests commands as you type based on history and completions.
This is the only plugin that requires you to actually install it first.

2. Dirhistory plugin
This plugin adds keyboard shortcuts for navigating directory history and hierarchy.

3. web-search plugin
This plugin adds aliases for searching with Google, Wiki, Bing, YouTube and other popular services.

4. sudo
Easily prefix your current or previous commands with sudo by pressing esc twice.

![Screenshot from 2022-09-10 17-33-56](https://user-images.githubusercontent.com/88684853/189520215-58bf90ef-858a-48ed-8531-3d10ab9e209b.png)

![Screenshot from 2022-09-10 17-34-24](https://user-images.githubusercontent.com/88684853/189520217-79b3e042-09f5-4b81-9bf0-80d1eef0fc32.png)

gcc, g++, make compiler:
![Screenshot from 2022-09-10 18-17-55](https://user-images.githubusercontent.com/88684853/189520218-830c2396-a06d-4839-b937-df52df8e2bc5.png)

![Screenshot from 2022-09-10 18-18-12](https://user-images.githubusercontent.com/88684853/189520219-8fa99fd6-bf39-4ee4-afff-b59fe7c027d4.png)

visual studio code:
![Screenshot from 2022-09-10 18-26-16](https://user-images.githubusercontent.com/88684853/189520220-2bd19f57-6a8e-4ec3-bff2-4981ab5e44e5.png)

## Task 3 - Create a Git repository. Write a small hello-world program in C. Compile it using GCC and Make. Commit your changes and push them to your remote repository. 

First of all I configured git by setting up username and email
![Screenshot from 2022-09-10 21-32-25](https://user-images.githubusercontent.com/88684853/189529500-bacd5b59-34c3-4fad-9450-4974f4cedb4d.png)

Then I created folders oop and lab0, there I created hello.c file. After that I compiled my c file with gcc.
![Screenshot from 2022-09-10 21-31-04](https://user-images.githubusercontent.com/88684853/189529513-610811d1-e041-4989-a18e-cd9e31156273.png)

![Screenshot from 2022-09-10 21-18-24](https://user-images.githubusercontent.com/88684853/189529509-f7d8ef0f-453e-4f64-8d4e-27d80e2ef3b1.png)

Also I created a Makefile to compile my file with make.
![Screenshot from 2022-09-10 21-31-31](https://user-images.githubusercontent.com/88684853/189529514-729a8227-2be6-4cb9-84e8-d6851ef3faf9.png)

![Screenshot from 2022-09-10 21-18-31](https://user-images.githubusercontent.com/88684853/189529511-2be70a0b-ab44-4ab4-82f9-3b0c7895bf6f.png)

I created a new repository on the github. I used the following commands in order to push my files on github:

git init - adds a local Git repository to the project;

git add . - adds all the files and folders in your project to the staging area;

git commit -m " " - commits the file with commit message;

git remote add origin [repository url] - points your local repository to the remote repository;

git branch -M main - changes your main branch's name to "main";

git pull - pulls the latest changes from the remote repository into the local repository;

git push - push all the code from the local repository into the remote repository.

![Screenshot from 2022-09-10 21-39-41](https://user-images.githubusercontent.com/88684853/189529527-d485ad84-dd2a-4690-878c-2ae3a226fe06.png)

![Screenshot from 2022-09-10 22-46-23](https://user-images.githubusercontent.com/88684853/189529537-22ef62af-d17a-441c-a954-507a9907e028.png)

![Screenshot from 2022-09-10 22-46-49](https://user-images.githubusercontent.com/88684853/189529538-1ef688ad-6035-4d40-9341-5df0eafd9d2e.png)

![Screenshot from 2022-09-11 11-26-32](https://user-images.githubusercontent.com/88684853/189529539-4bcae6b1-9ac2-4b81-a7c3-ccfa94c78b60.png)

Also I created .gitignore in order to ignored files which are build artifacts and machine generated files that can be derived from my repository source.
I want to ignore a file that I've committed in the past, then I need to delete the file from your repository and then add a .gitignore rule for it. Using the --cached option with git rm means that the file will be deleted from my repository, but will remain in my working directory as an ignored file.
![Screenshot from 2022-09-11 11-29-04](https://user-images.githubusercontent.com/88684853/189529540-f8142bc3-e730-412a-bca1-ae34389fa0d0.png)
