# Git Login Command
<br>
add path C:\Program Files\Git\
<br>
now you can win+r and type -> `git-bash`
<br>
git config --global user.name "yourUsername"
<br>
git config --global user.email "youremail@example.com"
<br>

# Git init
git init
<br>
git add .
<br>
git commit -m "first commit"
<br>
git branch -M main
<br>
git remote add origin https://github.com/examples/examples.git
<br>
git push -u origin main
<br>
<br>
git remote add origin https://github.com/examples/examples.git
<br>
git branch -M main
<br>
git push -u origin main

# Git SSH key (Git Bash)
<br>
eval $(ssh-agent -s)
<br>
ssh-keygen -t ed25519 -C "youremail@example.com"
<br>
ssh-add E:/Git/.ssh/id_rsa
<br>
ssh-add -l
<br>
to del ssh key from agent THIS IS NOT DELETE FILE COMMAND
ssh-add -D
<br>
ssh -T git@github.com
<br>
chmod 400 ~/.ssh/id_rsa

# ETC
<br>
# Custom Git Command
<br>
to check .bashrc file
ls -a ~
nano ~/.bashrc
alias cls='clear'
source ~/.bashrc