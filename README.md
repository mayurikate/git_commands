<p align="center"><img src="https://desktop.github.com/images/github-desktop-screenshot-windows.png"></p>


## About Github Commands 

This is very basic commands used heavily and super easy for any one who starts to lean git and along with github
This is sample readme which i have tried by learning git commands :)

- [Simple, fast starting with git](https://www.youtube.com/playlist?list=PLwAKR305CRO-fenwcN2-IC0rgaB6vaJgD).
- [all in one video just in 20 min.](https://www.youtube.com/watch?v=0fKg7e37bQE).

## Gui Based Version Control

- [Download git for windows here](git-for-windows.github.io).
- [SourceTree - Simplicity and power in a beautiful Git GUI , A free Git client for Windows and Mac](https://www.sourcetreeapp.com/).
- [Desktop Github](https://desktop.github.com).

## All Git Configuration Commands
- **[git]--->(to check if git is installed)**
- **[git config --list]--->(list configuartion settings)**
- **[git config --global user.name "ABC XYZ"]--->(add your name globally)**
- **[git config --global user.gmail abc@gmail.com]--->(add your email globally)**

## All Git Commands Related To Interacting with server or your repository.

## CASE 1 [USING FROM LOCAL PROJECT TO SERVER PROJECT]
- **[git init]--->(to initialize git to that particular folder)**
- **[touch filenname]--->(to create new file)**
- **[git status]--->(to check new files it will keep watch on folder)**

- **[git add .]--->(for all new files)**
	OR
- **[git add '*.txt' , '*.php']--->(for all new with specific wildcart)**
- **[git add index.php]--->(only this particular file)**

- **[git commit -m"msg here"]--->(Give specific message to commit)**
- **[git log]--->(all loges from start)**
- **[git status]--->(to check new files it will keep watch on folder)**

## CASE 2 [LOCAL TO SERVER PUSH]
- **[git remote add origin git@github.com:-----url-----]--->(TO UPLOAD FILES FROM LOCAL TO SERVER)**
- **[git push -u origin master]**


## CASE 3 [SERVER -->> LOCAL -->> SERVER PUSH]
- **[git push]--->(after git commit)**
- **[git pull]**


## SSH CONFIG FOR GIT.
- **[ssh-keygen -t rsa -b 4096 -C "your_github_email@gmail.com"]--->(to add specific ssh key)**
- **add password to more security purpose**
- **eval "$(ssh-agent -s)"**
- It will generate ranodm agent id
- **ssh-add ~/.ssh/id_rsa**
- enter above password again 
- It will ad your identity agent id to above generated ssh key
- To copy above key use -->>
- **clip < ~/.ssh/id_rsa.pub** (for windows)
- **pbcopy < ~/.ssh/id_rsa.pub** (for mac)

## [Ignoring some files/folders in git repository]
- **[touch .gitignore ]---->>(Create a new file .gitignore in project folder and list down single file/folder in each line to be ignored)**
- **[git commit .gitignore]---->>(Commit .gitignore file and the contents in the file are not tracked anymore)**

## [Cloning the project on local computer]
- **[git clone url]---->>(Downlaod the entire project mentioned in url with the folderame as the one mentioned in url i.e. before .git)**
- **[git clone url new_foldername]---->>(if we dont want to clone our project in default folder but in customized new_foldername)**

## Contributing

Really Do you want to contribute OH no problem at all, just fork and get started with learning with git :)

## Security Vulnerabilities

If you discover a New Useful Commands within This, please send pull request. All updates will be promptly addressed.
