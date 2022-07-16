# HTML_CSS_1206
Generate SSH and copy ssh to your github account

reference  link https://www.w3docs.com/snippets/git/how-to-generate-ssh-key-for-git.html

go to git bash

   ssh-keygen -t rsa -b 4096 -C "****.******@gmail.com"
   
cat ~/.ssh/id_rsa.pub | clip

paste in GitHub's account =>Settings =>click on SSH and GPG keys.=> New SSH key
Type the title and your SSH key, and press the Add SSH key button.
------------------------------------------
how to create ssh key and set username to local machine notes
reference  link
https://www.javatpoint.com/git-commands
    git config --global user.name "*******"
    git config --global user.email "****.******@gmail.com"
    git config --global core.editor Vim 
    git config --list  
    Git config --global color.ui true  
