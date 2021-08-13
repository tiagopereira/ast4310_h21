# Software and Tools


## Programming languages

This course can be followed using one of two programming languages: Python or Julia. Each project will be available in a Python and a Julia version. In classes, most of the explanations and examples will be given in Python, but it is also possible to replicate them in Julia if there is enough demand. The Python examples are more mature and have undergone more testing; moreover, Python will normally be more responsive and easier to interact with in a notebook environment because Julia has compilation overheads. However, the Julia versions will prove more versatile and faster in the computationally-heavier parts of later projects.

Besides the programming language used to run code, jupyter notebooks have a text component using the Markdown language. It will be used extensively in your project reports, and you are encouraged to get more familiar with it. The [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is a good reference. Familiarity with LaTeX is also important, but mostly to write equations, which can be included in Markdown using LaTeX syntax.

## JupyterHub

We will make extensive use of [JupyterHub at UiO](https://jupyterhub.uio.no/user/home/lab). JupyterHub is a cloud-based server for Jupyter notebooks and has all the packages and files necessary for AST4310. You need only to login with your UiO credentials, and *don't need to install any software in your computer*. More details on the use of JupyterHub will be given in the first week of classes.

## Other options for running notebooks

It is also possible to run the Jupyter notebooks at the Institute's linux machines or on your own computer. Both options are not recommended and will not be supported - if you choose to do so, you will be on your own in case any problems with packages arise. For advanced users who understand the risks and nevertheless want to do a local install, see the boxes below.

??? warning "Python installation for advanced users"
    The recommended way to install the necessary packages is through conda from the conda-forge channel. *Installing through pip will most likely lead to problems, especially if you use Windows.* You can install the necessary packages into a new conda environment using the [`environment.yml`](https://github.com/tiagopereira/ast4310/blob/master/environment.yml) from the repository, using `conda env create -f environment.yml`.


??? warning "Julia installation for advanced users"
    It is recommended you install Julia 1.6.2 or higher using the [standard downloads](https://julialang.org/downloads/). After that, install an [environment](https://pkgdocs.julialang.org/v1/environments/) using [`Project.toml`](https://github.com/tiagopereira/ast4310/blob/master/Project.toml) from the repository. On the same directory that you have `Project.toml`, start the julia REPL, press `]` for the package manager and then enter `activate .` followed by `instantiate`. Your prompt will change to `(ast4310) pkg>`, and it will install the necessary packages. You will need to do `(@v1.6) pkg> activate ast4310` to use the environment in the REPL, but if you run Jupyter with IJulia, it is enough to start it on the same directory of `Project.toml`. If you don't want an extra environment, you can just manually install the packages on `Project.toml`. While you can install Jupyter from Julia (`using IJulia; notebook`), it works better if you already have a python installation with Jupyter, in which case you need to copy the Julia kernel to your Jupyter kernel directory.
    


