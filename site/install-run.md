# Installation and execution

In this workshop we will use the [Anaconda](https://www.anaconda.com/download) Python distribution to simplify the installation and execution. We will also focus on [Jupyter tools and computational notebooks](https://docs.jupyter.org) (see [here, too](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html)), interacting with Python code via the [JupyterLab application](https://swcarpentry.github.io/python-novice-gapminder/01-run-quit.html#starting-jupyterlab) (see also [here](https://foundations.projectpythia.org/foundations/jupyterlab.html) for a more detailed guide).

```{admonition} Istalling Anaconda in your computer
[Follow these instructions](https://carpentries.github.io/workshop-template/#python). The videos are somewhat dated, so the screenshots may look a bit different from what you will actually see during installation. But the steps are the same. [Here is a more up-to-date, short installation video](https://www.youtube.com/watch?v=5_hB2TNPgRc), for Windows only.
```

## Running JupyterLab

We will use the [Anaconda Navigator](https://docs.anaconda.com/free/navigator/index.html) to launch JupyterLab. It's included in the Anaconda installation, together with JupyterLab itself and many other applications and packages.

## The wider world of Python installation and development

There are **many** options to install Python and software to develop and execute Python code! The second paragraph in [this page](https://swcarpentry.github.io/python-novice-gapminder/01-run-quit.html) is a very brief overview. 

Yes, this can be pretty confusing!

Python itself can be installed directly from the official Python website, https://python.org. The installer includes Python, the ability to execute code at the "terminal", and a very simple "Integrated Development Environment" (IDE) called IDLE.

An initial choice one has to make is the Python **version**. Typically it's best to avoid the very latest versions, and choose a slightly but more stable and more widely supported version. Today, that's probably Python 3.10.

Anaconda is based on the open-source [conda](https://conda.org/) package management system. conda itself can be installed through different distributions, with different pros and cons. The other main distrubutions are `miniconda`, `mamba` and `mambaforge`. I never use the Anaconda distribution myself! The source of the packages also varies; the most widely used one in the scientific and other communities is [conda-forge](https://conda-forge.org/).

We will use JupyterLab and Jupyter notebooks. But as everything Jupyter is also open source, the ability to run Jupyter notebooks is also implemented in other software. For example, [Visual Studio Code (VSCode)](https://code.visualstudio.com/), [Spyder](https://www.spyder-ide.org/) and [PyCharm](https://www.jetbrains.com/pycharm/) (PyCharm is not open-source but is freely available for education).

For complex software development tasks, IDE's are practically necessary. These include VSCode, Spyder and PyCharm. Typically you will write Python code directly (`*.py` files) rather than Jupyter notebooks; or some combination. Out of these IDE's, Spyder probably resembles the Matlab interface the most. VSCode has the advantage of also being a powerful, generic text editor. IDE's provide lots of conveniences that make coding more efficient.

You can also write code (not Jupyter notebooks) directly, "by hand", using a simple text editor; then run the code at the terminal. This is helpful in a pinch but pretty inefficient.

## Simple, no-fuss options for continued learning

If you'd like to polish, practice and extend your understaing of core Python language features, I recommend one of these two no-fuss options:

- [Thonny](https://thonny.org), a straightforward desktop software that also installs Python for its own use. Simple installation, few distractions, and helpful tools.
- Online Python execution sites. There are many options, but this one looks good: https://www.online-python.com

These are great resources for initial learning, but not for Python code development for actual, more complex work.
