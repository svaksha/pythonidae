+ [2to3](#2to3)
+ [DOCUMENTATION](#documentation)
+ [ENVIRONMENTS](#environments)
    + [IDE](#ide)
        + [Zoof](#zoof) 
    + [Jupyter](#jupyter)
+ [TERMINAL](#terminal)
+ [UTILS](#utils)
   + [Backups](#backups)
   + [Communication](#communication)
   + [Desktop Document Processing](#desktop-document-processing)
   + [File Compression](#file-compression)
   + [MTA](#mta)
   + [Open-Research-Tools](#open-research-tools)

----

# 2to3
__Python 2&3 tools__
+ [py3readiness](http://py3readiness.org) ::  Python 3 support graph for most popular packages. [Source code](https://github.com/chhantyal/py3readiness).
+ [python-future](http://python-future.org) :: Easy, clean, reliable Python 2/3 compatibility. [Source code](https://github.com/PythonCharmers/python-future) and a [cheat sheet for writing Python 2-3 compatible code](http://python-future.org/compatible_idioms.html). 
+ [Six](https://pypi.python.org/pypi/six) :: A Python 2-3 porting utility.

----

# DOCUMENTATION
**Documentation tools**
+ [PythonTeX](https://github.com/gpoore/pythontex) :: A LaTeX package that provides fast, user-friendly access to Python code entered within a TeX document to be executed, and the output to be included in the original document. It also provides syntax highlighting for code within LaTeX documents via the Pygments syntax highlighter. PythonTeX also provides support for Ruby, Julia, and Octave programming languages.
+ [Scisphinx](https://github.com/numfocus/scisphinx) :: Sphinx extensions common to the scientific computing ecosystem.

----

# ENVIRONMENTS
**Braille, REPL shells, GUI, IDE/Text editors, WIDE, Desktop User Interface, GUI, &c..**

## IDE
+ [anaconda-mode](https://github.com/proofit404/anaconda-mode) :: Code navigation, documentation lookup and completion for Python. 
+ [autocomplete-python](https://github.com/sadovnychyi/autocomplete-python) :: [Jedi](http://jedi.jedidjah.ch/) based Python autocomplete for [Atom](https://atom.io/packages/autocomplete-python).
+ [Bugjar](https://github.com/pybee/bugjar) :: A interactive graphical debugger for Python code. 
+ [jedi](https://github.com/davidhalter/jedi) :: Awesome autocompletion and static analysis library for python. 
+ [MagicPython](https://github.com/MagicStack/MagicPython) :: Syntax highlighter for cutting edge Python for Sublime Text and Atom. 
+ [pyzo](https://github.com/almarklein/pyzo) :: The Interactive editor for Python.

### Zoof
+ [Zoof](http://zoof.io) :: The Official repository - The IDE for dynamic coding. [Source code](https://github.com/zoofIO/zoof).
+ [flexx](https://github.com/zoofIO/flexx) :: A Python UI tookit based on web technology. [Documentation](http://flexx.readthedocs.org).
   + [flexx-notebooks](https://github.com/zoofIO/flexx-notebooks) :: Jupyter notebooks with Flexx examples. 

## [Jupyter](https://github.com/jupyter)
+ [Jupyter](http://jupyter.org), 'nee [IPython](http://ipython.org/) provides a rich architecture for interactive computing with interactive shells (terminal and Qt-based) and browser-based notebook support for code, text, mathematical expressions, inline plots and support for interactive data visualization and use of GUI toolkits. The Project Jupyter has a [governance process and model](https://github.com/jupyter/governance) for their organization.
+ [bookmarkd](https://github.com/ryansb/bookmarkd) :: Markdown -> IPython conversion tool. 
+ [callipy](https://github.com/damiendr/callipy) :: Call IPython notebooks with arguments.
+ [cite2c](https://github.com/takluyver/cite2c) :: Citations in the IPython Notebook.
+ [Colaboratory](https://github.com/jupyter/colaboratory) :: Create and store notebooks in Google Drive and allow for collaborative editing of notebooks.
+ [cookbook](http://ipython-books.github.io/cookbook/) :: Recipes of the IPython Cookbook, the definitive guide to high-performance scientific computing and data science in Python. Get the [source code](https://github.com/ipython-books/cookbook-code).
+ [ipydb](https://github.com/jaysw/ipydb) ::  Turn your IPython console into a cross-database SQL client. [Documentation](http://ipydb.readthedocs.org).
+ [ipymd](https://github.com/rossant/ipymd) : Use the IPython notebook as an interactive Markdown editor.
+ [ipyparallel](https://github.com/ipython/ipyparallel) :: Interactive Parallel Computing in Python. [Documentation](http://ipyparallel.readthedocs.org/).
+ [Ipython_memory_usage](https://github.com/ianozsvald/ipython_memory_usage) :: This tool reports memory usage deltas for every command you type.
+ [IPythonblocks](http://ipythonblocks.org) :: Practice Python with colored grids in the IPython Notebook. [Source code](https://github.com/jiffyclub/ipythonblocks) on GH.
+ [ipython-sql](https://github.com/catherinedevlin/ipython-sql) :: Introduces a `%sql` (or `%%sql`) magic for Jupyter/IPython. Connect to a database, using SQLAlchemy connect strings, then issue SQL commands within IPython or IPython Notebook.
+ [jupyter_kernel_test](https://github.com/jupyter/jupyter_kernel_test) :: A tool for testing Jupyter kernels. 
+ [Multiuser-server](https://github.com/jupyter/multiuser-server) :: Multi-user server for Jupyter notebooks.
+ [NBDiff](http://nbdiff.org) :: A diffing and merging tool for the IPython Notebook.
+ [qtconsole](https://github.com/jupyter/qtconsole) ::  Jupyter Qt Console - [stable release](http://jupyter.org/qtconsole/stable/).
+ [RunIPy](https://github.com/paulgb/runipy) :: Run IPython notebooks as command-line scripts, generate HTML reports.
+ [Rodeo](https://github.com/yhat/rodeo/) :: A data science IDE for Python - an alternative UI to the notebook for the IPython Kernel, heavily inspired by great projects like Sublime Text and Eclipse.
   + [Introducing Rodeo](http://blog.yhathq.com/posts/introducing-rodeo.html).
+ [sudospawner](https://github.com/jupyter/sudospawner) :: Spawn JupyterHub single-user servers with sudo.
+ [vIPer](https://github.com/damianavila/vIPer) :: A new tool for IPython notebooks. 

### JupyterLab
+ [JupyterLab](https://github.com/jupyter/jupyterlab) :: The computational environment. 
+ A blog post [Walkthrough of Jupyter Lab Alpha](https://veekaybee.github.io/jupyter-lab/)


### Jupyter Themes
+ [jupyter-themer](https://github.com/transcranial/jupyter-themer) :: Apply custom CSS styling to your jupyter notebooks.

###### Resources
+ [Jupyter notebook beginner guide](https://github.com/tritemio/jupyter_notebook_beginner_guide) :: A brief guide to install and run Jupyter/IPython notebooks.
+ [Run Jupyterhub on a Supercomputer](http://zonca.github.io/2015/04/jupyterhub-hpc.html).
+ [NotebookNameTest](http://nbviewer.ipython.org/github/staticfloat/notebooks/blob/master/julia_notebooks/NotebookNameTest.ipynb) from the julia-users thread on [How to find the name of the current IJulia notebook](https://groups.google.com/forum/#!topic/julia-users/mnCEQNd7ew0)
+ [IPython quick reference sheets](http://damontallen.github.io/IPython-quick-ref-sheets/)
+ D3 in IPython Notebook-2 :: [Here is an example of getting information back from d3 into the kernel](http://nbviewer.ipython.org/gist/anonymous/9975962) and another [eventful_graph and eventful_dict datastructures written for a demo with live-updating graphs (NetworkX -> D3)](https://gist.github.com/takluyver/9619942351cdc571a302). Mailing list discussion: http://mail.scipy.org/pipermail/ipython-dev/2014-June/014109.html
+ [ipython-in-depth](https://github.com/ipython/ipython-in-depth) :: IPython in-depth Tutorial, first presented at PyCon 2012, is meant to be executed with IPython 2.0 or newer.
+ Talk: [Project Jupyter](https://speakerdeck.com/fperez/project-jupyter) by Fernando Perez at Scipy-2014.
+ [IPython Interactive Computing and Visualization Cookbook](http://ipython-books.github.io/cookbook/) and the [recipes used in the IPython Cookbook](https://github.com/ipython-books/cookbook-code) :: Your definitive guide to high-performance scientific computing and data science in Python.
+ [A gallery of interesting IPython Notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks)
+ [7 favorite IPython Notebooks](http://beautifuldata.net/2014/03/datalicious-notebookmania-my-favorite-7-ipython-notebooks/)
+ The [Wakari IPython Notebook gallery](https://www.wakari.io/gallery) on learning Python.
+ The EuroPython 2014 training session "[Topic Modeling for Fun and Profit](https://github.com/piskvorky/topic_modeling_tutorial)".
+ [Networks meet Finance in Python - July 27 2014](https://github.com/mvaz/PyData2014-Berlin) 
+ [OsloWorkshop2014](https://github.com/jakevdp/OsloWorkshop2014) :: Material for @jakevdp 's lectures at the University of Oslo, Dec 2014.
+ [Running Jupyter with multiple Python and iPython paths](http://stackoverflow.com/questions/39007571/running-jupyter-with-multiple-python-and-ipython-paths/).
+ Kirill Pomogajko blogs on [Why I Don't Like Jupyter (FKA IPython Notebook)](http://opiateforthemass.es/articles/why-i-dont-like-jupyter-fka-ipython-notebook/).

----

# TERMINAL
+ [cookiecutter](https://github.com/audreyr/cookiecutter) :: A command-line utility that creates projects from cookiecutters (project templates). E.g. Python package projects, jQuery plugin projects. 
+ [dotfiler](https://github.com/svetlyak40wt/dotfiler) :: Shell agnostic git-based dotfiles package manager, written in Python. 
+ [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) :: Library for building powerful interactive command lines in Python.
+ [pythonpy](https://github.com/Russell91/pythonpy) :: command line kung-fu with python.
+ [Xonsh_Kernel](https://github.com/Calysto/xonsh_kernel) :: Jupyter Kernel for Xonsh.
    + [xonda](https://github.com/gforsyth/xonda) :: This is a thin wrapper around conda for use with xonsh.
+ [xontrib-prompt-ret-code](https://github.com/Siecje/xontrib-prompt-ret-code) :: Adds return code info to xonsh prompt. 

----

# UTILS
__General tools & useful utilities.__ 
+ [free-labour](https://github.com/brettcannon/free-labour) :: Calculate your open source contributions.
+ [pandocfilters](https://github.com/jgm/pandocfilters) :: A python module for writing pandoc filters, with a collection of examples. 
+ [podoc](https://github.com/podoc/podoc) :: A minimalistic pure Python pandoc clone, i.e. a markup document conversion library. Currently, it supports Markdown, Jupyter notebook, OpenDocument, O'Reilly Atlas, Python + comments. Support for ReST, LaTeX, HTML, AsciiDoc is planned.
+ [python-progressbar](https://github.com/niltonvolpato/python-progressbar) :: Text progress bar library for Python.
+ [Slides](https://github.com/mrocklin/slides) :: A template for slides using markdown. 

## Backups
+ [attic](https://github.com/jborg/attic) :: Deduplicating backup program.
+ [rotate-backups](https://github.com/xolox/python-rotate-backups) :: Simple command line interface for backup rotation, also available via [PyPI](https://pypi.python.org/pypi/rotate-backups).

## Communication
#### WhatsApp
+ [whatsapp-bot-seed](https://github.com/joaoricardo000/whatsapp-bot-seed) :: A 
small python framework to create a whatsapp bot, with regex-callback message 
routing. 
+ [whatsappcli](https://github.com/KarimJedda/whatsappcli) :: Control your server from Whatsapp. 
+ [yowsup](https://github.com/tgalal/yowsup) :: The python WhatsApp library.

#### Twitter
+ [followtrack](https://github.com/grote/followtrack) :: Keeps track of your Twitter followers and lets you know who unfollowed you. 
+ [twitter-unfav](https://github.com/grote/twitter-unfav) :: A script to remove favorited tweets from Twitter for privacy reasons. 

## Desktop Document processing 
+ [Pweave](https://github.com/mpastell/Pweave) :: A scientific report generator and a literate programming tool for Python. Pweave can capture the results and plots from data analysis and works well with numpy, scipy and matplotlib. Pweave is inspired by Sweave, an excellent tool for R programmers, and the syntax is mostly compatible with it.

## File Compression
+ [bitshuffle]((https://github.com/kiyo-masui/bitshuffle) :: Filter for improving compression of typed binary data. 

## MTA
+ [python-slimta](http://slimta.org/) :: Lightweight, asynchronous SMTP libraries. [Source code](https://github.com/slimta/python-slimta).

## Open-Research-Tools
+ [arxiv-sanity-preserver](https://github.com/karpathy/arxiv-sanity-preserver) :: Web interface for browsing, search and filtering recent arxiv submissions. [Website](http://www.arxiv-sanity.com/). 
+ [autograde](https://github.com/asutton/autograde) :: A set of tools that help automate the more mechanical aspects of grading.
+ [Citer](https://github.com/mangecoeur/Citer) :: Citations from bibtex for Sublime Text 3. 
+ [depsy](http://depsy.org) :: Track the impact of research software. [Source code](https://github.com/impactstory/depsy).
   + [depsy-research](https://github.com/Impactstory/depsy-research) :: Documentation and research output for Depsy.
+ [duecredit](https://github.com/yarikoptic/duecredit) :: Automated collection and reporting of citations for used software/methods. 
+ [gradebook](https://github.com/jarrodmillman/gradebook) :: Tools for grading.
+ [habanero](https://github.com/sckott/habanero) :: crossref search low level client.
+ [sempervirens](https://github.com/njsmith/sempervirens) :: An experimental prototype for gathering anonymous, opt-in usage data for open scientific software. 

## TimeTracker
+ [Watson/](http://tailordev.github.io/Watson/) :: A wonderful CLI to track your time! [Source code](https://github.com/TailorDev/Watson). 
