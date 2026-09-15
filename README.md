# MMRES Python Boot Camp

Materials for the 2026-2027 Python Boot Camp of the **Barcelona Institute of Science and Technology** (BIST) & **Universitat Pompeu Fabra** (UPF) **Master of Multidisciplinary Research in Experimental Sciences** (MMRES).

The contents of this Boot Camp are designed based on [2023](https://github.com/MMRES-PyBootcamp/MMRES-python-bootcamp2023), [2022](https://github.com/MMRES-PyBootcamp/MMRES-python-bootcamp2022), [2021](https://github.com/MMRES-PyBootcamp/MMRES-python-bootcamp2021), [2020](https://github.com/germannp/BIST-Python-Bootcamp) and [2019](https://github.com/BorjaRequena/BIST-master-python-bootcamp) editions. From 2024 onward, we decided to keep a single repo (named just `MMRES-python-bootcamp`) for simplicity. If you are interested in previous editions, please browse the [commit history](https://github.com/MMRES-PyBootcamp/MMRES-python-bootcamp/commits/master/).

**IMPORTANT**: Make sure you have the learning environment ready **before** coming to the first class on September 28th. Follow the steps below to 1) install Python and 2) prepare the `MMRES-python-bootcamp` repository on your machine.

Suggested Python installation
-----------------------------
1. **Learning environment**: We will use [JupyterLab](https://jupyter.org/) (both for learning Python concepts and to carry on hands-on coding), just as it is available with Anaconda.
2. **Installation**: Please, go to the official [Anaconda website](https://www.anaconda.com/download) and follow downloading and installing instructions. Please, skip the registration process by clicking on "Skip Registration". In order to minimize the problems derived from the cross-platform installation heterogeneity, we recommend to install Anaconda3 with the default options via its [graphical installer](https://www.anaconda.com/docs/getting-started/anaconda/install/windows-gui-install) for Windows or macOS. If you work with a Linux, first of all: congratulations, second follow [Linux installer](https://www.anaconda.com/docs/getting-started/anaconda/install/linux-install).
3. **Packages**: NumPy, Pandas, SciPy, Matplotlib, Seaborn, [Plotnine](https://anaconda.org/conda-forge/plotnine)\*, Scikit-learn, Statsmodels, [bioinfokit](https://anaconda.org/bioconda/bioinfokit)\*. Please note that starred packages are not available after default Anaconda3 setup and thus you should manually install them using the **Anaconda Prompt**. Open an **Anaconda Prompt** command line window in your machine, follow the instructions from the starred packages hyperlinks above, and be patient, Anaconda might take a considerable amount of time to install certain packages (type `y` then `↵` if prompted with `Proceed ([y]/n)?` when installing that starred packages).

Suggested repository preparation
--------------------------------
1. From this same page, use the `<> Code` green button and then `Download ZIP` option to store a local copy of this repository (don't forget to unzip it). If you are familiar with Git, you can just clone the repository.
2. Open an Anaconda Prompt and navigate to the folder where the just-unzipped just-downloaded repository is locally stored in your machine (for example, by doing `cd C:Users\YOURNAME\GitHub\MMRES-python-bootcamp` or something similar).
3. Type the command `jupyter lab` (you will see how Jupyter Lab opens a new tab in your default web browser).
4. Check that you can successfully load the first Jupyter Notebook called `01_Intro.ipynb` just by double-clicking it (use the "File Browser" pane at the left side of the Jupyter Lab tab).

If you reached this point, you are up and ready to start the Boot Camp next September 28th.

Timetable (TO BE UPDATED SOON!)
---------
* Sept. 28th (Monday):
    + 10:00 - 11:00: Set up & Intro (I)
    + 11:00 - 12:00: Intro (II)
      
* Sept. 30th (Wednesday):
    + 10:00 - 11:00: Scipy stats (I)
    + 11:00 - 12:00: Pandas (I)
  
* Oct. 1st (Thursday):
    + 10:00 - 11:00: Pandas (II)
    + 11:00 - 12:00: Seaborn

* Oct. 5th (Monday):
    + 12:30 - 13:30: Numpy
    + 13:30 - 14:30: Group Work (I) 

* Oct. 8th (Thursday):
    + 10:00 - 11:00: Scipy stats (II)
    + 11:00 - 12:00: Group Work (II)

* Oct. 13th (Tuesday)
    + 10:00 - 11:00: Group Work (III)
    + 11:00 - 12:00: PCA

Recommended readings and resources
----------------
* [Stack Overflow](https://stackoverflow.com/)
* [I'm done using AI](https://brettcodes.com/im-done-using-ai/)
* [Learn X in Y minutes where X = Python](https://learnxinyminutes.com/docs/python/)
* [The Python Tutorial](https://docs.python.org/3.6/tutorial/index.html)
* [10 Minutes to Pandas](https://pandas.pydata.org/pandas-docs/stable/10min.html)
* [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
* [Pythonic Preambulations](http://jakevdp.github.io/)
