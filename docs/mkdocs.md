# Control
This is a *basic* control layout. Of the tools indicated on this page, only **Git** has a global scope.  

## Others Tools

* [GitConfig](http://127.0.0.1:8000/gitconfig/)
* [Pip-Tools](http://127.0.0.1:8000/piptools/)

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


