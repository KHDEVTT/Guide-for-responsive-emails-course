# Responsive HTML Emails Course
Getting up and running with the Responsive HTML Emails Course

## Table of Contents:
- [Prerequisites](#prerequisites)
- [Use with web developer starter kit](#use-with-starter-kit)
- [Use with VSCode](#use-with-vscode)
- [Install Node Version Manager](#install-node-version-manager)

## Prerequisites

 - [ ] Install the latest  Nodejs (__LTS - Long Term Support version__) from [Nodejs website](https://nodejs.org/en/) 
 - [ ] __(Optional - Windows only )__ Install [Python 2.7](https://www.python.org/downloads/release/python-2718/) and select add to path option.
 - [ ] Install vscode or your preferred text editor
 - [ ] Have your terminal of choice open. [ Terminal (mac); WSL (windows); GitBash (windows); powershell (windows) ]
 - [ ] Create a ```Projects``` folder. 
	 - [ ] You can create this folder on either desktop, documents, home folder etc. This folder will contain all your future projects.
 - [ ] In your ```Projects``` folder, create a new folder ```cp-email```. This is where you will build the project for this course.
 - [ ] Download the [project starter files](https://github.com/codingphasedotcom/courses-files/blob/master/email-course-starting-files.zip) by clicking on the ```download``` button.
 - [ ] Extract this zip file. 

 



 

## Use with starter kit

 - [ ] Install Gulp. Ensure you have Node installed and follow [these instructions](https://gulpjs.com/docs/en/getting-started/quick-start) from the documentation.
 - [ ] Download the [web developer starter kit](https://github.com/codingphasedotcom/Dev-Starter-Kit)
 - [ ] Extract the folder and copy it to your ```Projects``` folder
 - [ ] Rename the folder from ```Dev-Starter-Kit-master``` to ```cp-email```
 - [ ] In your file explorer, navigate to ```cp-email -> public -> img``` folder , delete all the images there and copy the images from the ```project-starter-files``` images folder to this location.
 - [ ] Downgrade your version of nodejs to ``` 10.24.1```  with the **Node Version Manager**. You can find [instructions here](#install-node-version-manager) on how to change your node version.
 - [ ] In your terminal, navigate to your cp-email folder.
 - [ ] ```npm install ``` run this command to install all the dependencies.
 - [ ] ```npm run watch``` run this command to start the web developer starter kit.
 - [ ] Follow the course.

## Use with VSCode

 - [ ] Create ```cp-email``` folder in your ```Projects``` folder
 - [ ] Copy ```images``` folder into ```cp-email``` folder
 - [ ] Open ```cp-email``` folder in vscode (or your preferred text editor)
 - [ ] Create ```index.html``` file and scaffold a basic html document. 
 ```html
 <!DOCTYPE  html>

	<html  lang="en">

	<head>

			<meta  charset="UTF-8">

			<meta  http-equiv="X-UA-Compatible"  content="IE=edge">

			<meta  name="viewport"  content="width=device-width, initial-scale=1.0">

			<title>Responsive Email</title>

	</head>

	<body>

	</body>

</html>
```
 - [ ] Install vscode ```live server``` extension by Ritwick Dey and run the live server
	 - [ ] Right inside the ```index.html``` file and select ```Open with Live Server``` option to get browser reload functionality with this extension.
 - [ ] Follow the course.


	 
## Install Node Version Manager

 - [ ] __Ensure you have Node (LTS) installed__.


### Method 1: Windows Only 

 - [ ] -   On  [this Github Repo](https://github.com/coreybutler/nvm-windows/releases)  scroll down and find  `nvm-setup.exe`  Download the file and install it.
 - [ ] -   During the installation process, if asked to allow the application to "run" or "control" or "monitor" nodejs on your computer, say yes.

### Method 2: Mac & Windows (including WSL)

 - [ ] -   From  [this Github Repo](https://github.com/nvm-sh/nvm#install--update-script), open your terminal and copy and run **one**  of the following commands from your home directory. These commands will allow you to download and install the scripts.
 - [ ]    `cd ~`  to navigate to your home directory
 - [ ]  `curl -o-  [https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh)  | bash`
### OR
 - [ ]    `wget -qO-  [https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh)  | bash`
 - [ ]   Close and reopen your terminal (including all running instances of terminal that may be open)

#### **Test that nvm has been correctly installed with the command `nvm`  in the terminal. If you see a list of nvm commands with corresponding descriptions, you're all set.**

### _IMPORTANT_:
#### _If you are getting "access denied" errors, run your terminal in administrator mode_.

> If this was helpful give it a star

> Written for CodingPhase by  [Karen](https://khdevtt.com/).
