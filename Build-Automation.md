**Build automation software, continuous integration (CI), continuous delivery (CD), Packaging, Virtualization, Release engineering and management tools, Software configuration management (SCM) software...**

+ [BUILD AUTOMATION](#build-automation)
+ [CONTINUOUS INTEGRATION](#continuous-integration)
+ [Operating System Technology](#operating-system-technology)
   + [Packaging](#packaging)
   + [Sandboxes](#sandboxes)
   + [Virtualization](#virtualization)

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
+ [nupic-darwin64](https://github.com/numenta/nupic-darwin64) :: Python distribution for NuPIC on OSX.
+ [nupic-linux64](https://github.com/numenta/nupic-linux64) :: Python distribution for NuPIC on 64-bit linux.
+ [Pybuilder](http://pybuilder.github.io) :: Continuous build tool for Python. [Source code](https://github.com/pybuilder/pybuilder).
+ [Chef cookbook for Python](https://github.com/poise/python) :: Chef cookbook to install Python and related tools. http://community.opscode.com/cookbooks/python

----

# CONTINUOUS INTEGRATION

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

## Packaging
+ [antipackage](https://github.com/ellisonbg/antipackage) :: Automagically import single file Python modules from GitHub. 
+ [Changes](https://github.com/michaeljoseph/changes) :: It automates python library release tasks.
+ [picnic.py](https://github.com/Zulko/picnic.py) :: Easy Python packages creation. 

###### Resources
+ [Python Packaging User Guide](https://github.com/pypa/python-packaging-user-guide) 
+ Another post explaining Python [Modules, Packages, and all that](https://python4astronomers.github.io/installation/packages.html).
+ How to [Port Python 2 Code to Python 3](https://docs.python.org/3/howto/pyporting.html) and write a proper [trove classifier](https://pypi.python.org/pypi?%3Aaction=list_classifiers) specifying what versions of Python are supported in your `setup.py` file. Here is the idioms [cheat-sheet](http://python-future.org/compatible_idioms.html)


## Sandboxes
#### Anaconda
+ [Conda](https://github.com/conda/conda) :: is a cross-platform, Python-agnostic [binary package manager](http://conda.pydata.org) 
   + [Conda package for Python-3.2 for 64-bit Linux](https://binstar.org/cpcloud/python)
   + [ctox](https://github.com/hayd/ctox) :: Tox with conda.
   
###### Resources
+ [Continuum Analytics: Documentation](http://docs.continuum.io)
+ [python-3 in anaconda](http://continuum.io/blog/anaconda-python-3


## Virtualization
+ [hcp-neurodebian](https://github.com/yarikoptic/hcp-neurodebian) :: Scripts to create HCP environment containing basic Dockerfile to erect 10GB beast containing HCP500 full pipelines.

