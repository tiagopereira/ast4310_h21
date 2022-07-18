# Software and Tools


## Programming language

This course can be followed using the Python programming language.

Besides the programming language used to run code, jupyter notebooks have a text component using the Markdown language. It will be used extensively in your project reports, and you are encouraged to get more familiar with it. The [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is a good reference. Familiarity with LaTeX is also important, but mostly to write equations, which can be included in Markdown using LaTeX syntax.

## JupyterHub

We will make extensive use of [JupyterHub at UiO](https://jupyterhub.uio.no/user/home/lab). JupyterHub is a cloud-based server for Jupyter notebooks and has all the packages and files necessary for AST4310. You need only to login with your UiO credentials, and *don't need to install any software in your computer*. More details on the use of JupyterHub will be given in the first week of classes.

## Other options for running notebooks

It is also possible to run the Jupyter notebooks at the Institute's linux machines or on your own computer. **Both options are not recommended and will not be supported** - if you choose to do so, you will be on your own in case any problems with packages arise. For advanced users who understand the risks and nevertheless want to do a local install, see the boxes below.

??? warning "Python installation for advanced users"
    The recommended way to install the necessary packages is through conda from the conda-forge channel. *Installing through pip will most likely lead to problems, especially if you use Windows.* You can install the necessary packages into a new conda environment using the [`environment.yml`](https://github.com/tiagopereira/ast4310/blob/master/environment.yml) from the repository, using `conda env create -f environment.yml`.

