# Control
This is a *basic* control layout. Of the tools indicated on this page, only **Git** has a global scope.  
<br />
# https://www.redhat.com/sysadmin/kubernetes-components?utm_medium=Email&utm_campaign=weekly&sc_cid=7013a0000026GNKAA2

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










## Pip-Tools

I really like **_pip-tools_**. "*A set of command line tools to help you keep your pip-based packages fresh, even when you've pinned them*".  
The most important thing for me is that **_pip-tools_** is inside the virtual environment and not as a global installation, that's why I think the tool is so simple. In addition, **_pip-tools_** delivers exactly what it proposes to do.  

### Commands Pip-Tools

* 'pip install pip-tools' - Install pip-tools.
* 'nano requirements.in' - Creates a requirements.in file and puts the immediate dependencies.  
* 'pip-compile --generate-hashes requirements.in --output-file requirements.txt' - compile and generate hashes. 

The documentation says that "**pip-tools = pip-compile + pip-sync**".  

For full documentation visit [GitHub/JazzBand/Pip-Tools](https://github.com/jazzband/pip-tools)

 


## MkDocs

MkDocs "*is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation*".  
After creating or cloning a repository I like to write about the necessary steps to keep a record of the path taken.  
Basicaly MkDocs works with the commands below.


### Commands MkDocs

* `mkdocs new .` - Create a new project within the folder.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

### Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.  

For full documentation visit [mkdocs.org](https://www.mkdocs.org).


