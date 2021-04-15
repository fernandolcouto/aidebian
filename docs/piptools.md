# Control
This is a *basic* control layout. Of the tools indicated on this page, only **Git** has a global scope.  

## Other Tools

* [GitConfig](http://127.0.0.1:8000/gitconfig/)  
* [MkDocs](http://127.0.0.1:8000/mkdocs/)

## Pip-Tools

I really like **_pip-tools_**. "*A set of command line tools to help you keep your pip-based packages fresh, even when you've pinned them*".  
The most important thing for me is that **_pip-tools_** is inside the virtual environment and not as a global installation, that's why I think the tool is so simple. In addition, **_pip-tools_** delivers exactly what it proposes to do.  

### Commands Pip-Tools

* 'pip install pip-tools' - Install pip-tools.
* 'nano requirements.in' - Creates a requirements.in file and puts the immediate dependencies.  
* 'pip-compile --generate-hashes requirements.in --output-file requirements.txt' - compile and generate hashes. 

The documentation says that "**pip-tools = pip-compile + pip-sync**".  

For full documentation visit [GitHub/JazzBand/Pip-Tools](https://github.com/jazzband/pip-tools)

 


