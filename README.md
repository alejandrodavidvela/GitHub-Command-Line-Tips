# GitHub Command Line Tips
 Tips and Tricks for using GitHub in Terminal


To Use GitHub in the Terminal first you need to install Homebrew 

Go to this site:

https://brew.sh/

Copy paste this into your terminal. The script will run and tell you what to do if it needs direction.

 $ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" 



Then you need to install Github (gh)

Install:

brew install gh

Upgrade:

brew upgrade gh



Create a new githhub repository and push code to github:

git init
gh repo create
git add .
git commit -m "Full code"
git push 