# Control
This is a *basic* control layout. Of the tools indicated on this page, only **Git** has a global scope.  

## Other Tools  

* [Pip-Tools](http://127.0.0.1:8000/piptools/)  
* [MkDocs](http://127.0.0.1:8000/mkdocs/)

## Git

**Git** is a Swiss army knife.  
Basic configuration:  

* 'git config --global user.name "Name"'
* 'git config --global user.email "name@example.com"'  

Set the **GitIgnore Global file** (available in Model):  

* 'git config --global core.excludesfile ~/.gitignore_global'.  

Set **main** as the default branch name:  

* 'git config --global init.defaultBranch main'

Add to .bashrc file:  

**git-autocompletion**

* 'if [ -f ~/.git-completion.bash ]; then
  . ~/.git-completion.bash
fi
'  

**within “color-prompt” (for to show the activated Branch)**, before **$/**  

* '$(__git_ps1 " (%s)")'  


**Source:**  

* [A1.6 Appendix A: Git in Other Environments - Git in Bash](https://git-scm.com/book/en/v2/Appendix-A%3A-Git-in-Other-Environments-Git-in-Bash)







