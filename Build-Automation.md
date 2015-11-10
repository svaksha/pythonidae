**Build automation software, continuous integration (CI), continuous delivery (CD), Packaging, Virtualization, Release engineering and management tools, Software configuration management (SCM) software...**

+ [BUILD AUTOMATION](#build-automation)
+ [CONTINUOUS INTEGRATION](#continuous-integration)
+ [Operating System Technology](#operating-system-technology)
   + [Binaries](#binaries)
   + [Containers-Virtualization](#containers-virtualization)
   + [DistrOS](#distros)
   + [Packaging](#packaging)
   + [Sandboxes](#sandboxes)
+ [NEWS](#news)


----

# BUILD AUTOMATION
+ [Autopkg](https://github.com/autopkg) has more automation recipes:
   + [48kRAM-recipes](https://github.com/autopkg/48kRAM-recipes).
   + [Hansen-m-recipes](https://github.com/autopkg/hansen-m-recipes) :: More recipes for Autopkg.
   + [Jaharmi-recipes](https://github.com/autopkg/jaharmi-recipes) :: Recipes for the Mac OS X system administration tool.
   + [Jleggat-recipes](https://github.com/autopkg/jleggat-recipes) :: Recipes for [autopkg](http://autopkg.github.io/autopkg/).
   + [ScriptingOSX-recipes](https://github.com/autopkg/scriptingosx-recipes).
   + [Thenikola-recipes](https://github.com/autopkg/thenikola-recipes).
   + [Timsutton-recipes](https://github.com/autopkg/timsutton-recipes).
+ [BuildBot](https://en.wikipedia.org/wiki/Buildbot) :: Runs atop the Twisted libraries.
+ [nupic-darwin64](https://github.com/numenta/nupic-darwin64) :: Python distribution for NuPIC on OSX.
+ [nupic-linux64](https://github.com/numenta/nupic-linux64) :: Python distribution for NuPIC on 64-bit linux.
+ [Pybuilder](http://pybuilder.github.io) :: Continuous build tool for Python. [Source code](https://github.com/pybuilder/pybuilder).
+ [Chef cookbook for Python](https://github.com/poise/python) :: Chef cookbook to install Python and related tools. http://community.opscode.com/cookbooks/python
+ [Diamond](https://github.com/python-diamond/Diamond) :: A python daemon that collects system metrics and publishes them to Graphite (and others). It is capable of collecting cpu, memory, network, i/o, load and disk metrics. Additionally, it features an API for implementing custom collectors for gathering metrics from almost any source.
+ [GRR](https://github.com/google/grr) Rapid Response :: remote live forensics for incident response.
+ [Pinball](https://github.com/pinterest/pinball) :: A scalable workflow manager.
+ [SCons](http://scons.org/) :: A build automation tool that automatically analyzes source code file dependencies and operating system adaptation requirements from a software project description and generates final binary executables for installation on the target operating system platform. [Wikipedia page](https://en.wikipedia.org/wiki/SCons).

### DevOps tools
+ [Fabric](http://www.fabfile.org) :: A Python library and command-line tool for streamlining the use of SSH for application deployment or systems administration tasks. [Source code and bug tracker](https://github.com/fabric/fabric/).
+ [patchwork](https://github.com/fabric/patchwork) :: Common deployment/sysadmin operations, built on Fabric. 
+ [Plumbum](https://pypi.python.org/pypi/plumbum) :: Shell combinators library written in Python. Read the [documentation](https://plumbum.readthedocs.org/en/latest/) and [source code](https://github.com/tomerfiliba/plumbum).
+ [pyinvoke](http://pyinvoke.org) :: Simple Python task execution. [Source code](https://github.com/pyinvoke/invoke).
+ [Watcher](https://github.com/splitbrain/Watcher) :: A daemon that watches specified files/folders for changes and fires commands in response to those changes. It is similar to incron, however, configuration uses a simpler to read ini file instead of a plain text file. Unlike incron it can also recursively monitor directories. It's also written in Python, making it easier to hack.

----

# CONTINUOUS INTEGRATION

+ [Homu](http://homu.io/) :: A bot that integrates with GitHub and your favorite continuous integration service. [Source Code](https://github.com/barosl/homu).

##### Resources
* Blog post series on Continuous integration in Python by @jni:
   * [Volume 1: automated tests with pytest](http://ilovesymposia.com/2014/10/01/continuous-integration-0-automated-tests-with-pytest/)
   * [Volume 2: measuring test coverage](http://ilovesymposia.com/2014/10/02/continuous-integration-1-test-coverage/)
   * [3: set up your test configuration files](http://ilovesymposia.com/2014/10/13/continuous-integration-in-python-3-set-up-your-test-configuration-files/)
   * [4: set up Travis-CI](http://ilovesymposia.com/2014/10/15/continuous-integration-in-python-4-set-up-travis-ci/)
   * [5: report test coverage using Coveralls](http://ilovesymposia.com/2014/10/15/continuous-integration-in-python-5-report-test-coverage-using-coveralls/)
   * [6: Show off your work](http://ilovesymposia.com/2014/10/17/continuous-integration-in-python-6-show-off-your-work/)
   * [7: some helper tools and final thoughts](http://ilovesymposia.com/2014/10/27/continuous-integration-in-python-7-some-helper-tools-and-final-thoughts/)

----

# [Operating System Technology](http://en.wikipedia.org/wiki/Category:Operating_system_technology)

+ [klusta_process_manager](https://github.com/tymoreau/klusta_process_manager) :: A process manager.

## Containers-[Virtualization](http://en.wikipedia.org/wiki/Category:Virtualization_software)
__Docker, etc..__
+ [Ansible and Docker](https://developer.rackspace.com/blog/ansible-and-docker/)
+ [docker-notebook](https://github.com/ipython/docker-notebook) :: Docker containers for the Jupyter IPython notebook (+SciPy Stack). https://registry.hub.docker.com/u/ipython/
+ [hcp-neurodebian](https://github.com/yarikoptic/hcp-neurodebian) :: Scripts to create HCP environment containing basic Dockerfile to erect 10GB beast containing HCP500 full pipelines.
+ [Pythonista](https://github.com/ikalnitsky/pythonista) :: A Docker image for Python developers to use and test their applications.

## Packaging
+ [antipackage](https://github.com/ellisonbg/antipackage) :: Automagically import single file Python modules from GitHub.
+ [Changes](https://github.com/michaeljoseph/changes) :: Automates python library release tasks.
+ [cookiecutter-pylibrary](https://github.com/ionelmc/cookiecutter-pylibrary) :: Enhanced cookiecutter template for Python libraries.
+ [picnic.py](https://github.com/Zulko/picnic.py) :: Easy Python packages creation.
+ [pip2pi](https://github.com/wolever/pip2pi) :: Builds a PyPI-compatible package repository from pip requirements.
+ [pip-tools](https://github.com/nvie/pip-tools) :: A set of tools to keep your pinned Python dependencies fresh.
+ [pynsist](https://pypi.python.org/pypi/pynsist) :: Build Windows installers for Python apps.
+ [pythonize](https://github.com/princebot/pythonize) :: Download, install, and configure Python in one line.
+ [twine](https://github.com/pypa/twine) :: Utilities for interacting with PyPI. 

###### Resources
+ AOSA book [Python Packaging](http://www.aosabook.org/en/packaging.html) by Tarek Ziadé.
+ [Python Packaging User Guide](https://packaging.python.org/en/latest/index.html) and the github [source code](https://github.com/pypa/python-packaging-user-guide).
+ [python-cffi-example](https://github.com/wolever/python-cffi-example) :: An example project showing how to use Python's CFFI.
+ Another post explaining Python [Modules, Packages, and all that](https://python4astronomers.github.io/installation/packages.html).
+ How to [Port Python 2 Code to Python 3](https://docs.python.org/3/howto/pyporting.html) and write a proper [trove classifier](https://pypi.python.org/pypi?%3Aaction=list_classifiers) specifying what versions of Python are supported in your `setup.py` file. Here is the idioms [cheat-sheet](http://python-future.org/compatible_idioms.html)


## Sandboxes

+ [autoenv](https://github.com/kennethreitz/autoenv) :: Directory-based environments. 

#### Anaconda
+ [Conda](https://github.com/conda/conda) :: is a cross-platform, Python-agnostic [binary package manager](http://conda.pydata.org)
   + [Conda package for Python-3.2 for 64-bit Linux](https://binstar.org/cpcloud/python)
   + [ctox](https://github.com/hayd/ctox) :: Tox with conda.
   + [python-appveyor-conda-example](https://github.com/rmcgibbo/python-appveyor-conda-example) :: Demo project for building and shipping Python conda packages with Appveyor CI and Travis CI.
+ [conda-execute](https://github.com/pelson/conda-execute) : Execute scripts in their own temporary environment.
+ [conda-smithy](https://github.com/conda-forge/conda-smithy) :: The tool for managing conda-forge feedstocks. 
+ [xz-feedstock](https://github.com/scopatz/xz-feedstock) :: The conda recipe (raw material).

###### Resources
+ [Continuum Analytics: Documentation](http://docs.continuum.io)
+ [python-3 in anaconda](http://continuum.io/blog/anaconda-python-3

----

# NEWS
+ [Devops Weekly](http://www.devopsweekly.com/).

### Interesting Reads
+ [HN thread](https://news.ycombinator.com/item?id=9517392) on the blog post [Python 3 in Science: the great migration has begun](https://astrofrog.github.io/blog/2015/05/09/2015-survey-results/) by astrofrog.
