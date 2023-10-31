# Jupyter Notebooks - Useful info

Link to current Jupyterbook - https://nickyjgarland.github.io/jupyternb/

# Getting started
JB utilses command line interface. 
Open Anaconda to work in
Navigate to the correct folder 
* Use cd .. to move back a folder - do several times
* cd jupyterbook
* cd jupyternb

To run Jupyter notebook, type jb into interface when in correct folder

# To Create a jupyter notebook

To create a new jb, naviagte to where you wnat the fler to be created and then type 

```
jb create [Name of book]
```
This creates a folder with the minimal files required for a jb

# To build a jupyter notebook

Once you have created all the content for your in your book folder and you’ve defined your book’s structure (within  _toc.yml), you can build the HTML for your book.

Do so by running the following command:

```
jb build [mybookname/]
```
Note: you have to be situated within the parent folder for this to work as it targets the folder as a whole.

## Possible errors / issues to look for

* Sometimes you recieve errors if you refer to files that do not exist.
* Build notebook slowly, piece by piece and make sure that all redundant files are removed to ensure that all is clear.
* If you build the book it creates a html veriosn of each of the files so that you can preview what you have created. 
* Make sure to delete the "__build"_ folder before you recreate it if needed otherwise it will through up another error.

# Post on Github pages

Push the built book to your github repository

This link below is the basic information that is requied.
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Main issue is to ensure that under 'Settings/Pages' is that the source is correct so that the correct branch is selected so that the Gthub pages go live.

# Useful links
Overview - https://jupyterbook.org/en/stable/start/overview.html

Create a template book - https://jupyterbook.org/en/stable/start/create.html

References with Jupyterbook - https://jupyterbook.org/en/stable/tutorials/references.html

References in Jupyterbooks - https://jupyterbook.org/en/stable/tutorials/references.html

Create a bib.tex file from Zotero - https://libguides.usask.ca/c.php?g=218034&p=1446406

