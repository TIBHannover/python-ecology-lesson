---
layout: page
title: Setup
---

> ## Data
> Data for this lesson is from the Portal Project Teaching Database -
> [available on FigShare](https://figshare.com/articles/Portal_Project_Teaching_Database/1314459).
>
> We will use the six files listed below for the data in this lesson.
> Download these files to your computer either by clicking
> [this link](https://github.com/weecology/portal-teachingdb/archive/master.zip),
> which will give you everything in a single compressed file.
> You'll need to unzip this file after downloading it.
>
> Or download each file indvidually with the following links:
>
> - [surveys.csv](https://ndownloader.figshare.com/files/10717177)
> - [species.csv](https://ndownloader.figshare.com/files/3299483)
> - [speciesSubset.csv]({{ page.root }}/data/speciesSubset.csv)
> - [plots.csv](https://ndownloader.figshare.com/files/3299474)
> - [bouldercreek_09_2013.txt]({{ page.root }}/data/bouldercreek_09_2013.txt)
{: .prereq}



> ## Software
> [Python](http://python.org) is a popular language for
> scientific computing, and great for general-purpose programming as
> well.  Installing all of its scientific packages individually can be
> a bit difficult, so we recommend an all-in-one installer.
>
> For this workshop we use Python version 3.x.
>
> ### Required Python Packages for this workshop
>
> * [Pandas](http://pandas.pydata.org/)
> * [Jupyter notebook](http://jupyter.org/)
> * [Numpy](http://www.numpy.org/)
> * [Matplotlib](http://matplotlib.org/)
{: .prereq}

## Install Anaconda

Download [Anaconda's Python 3.x installer](https://www.anaconda.com/distribution/#download-section)
and run it according to the instructions.
This automatically installs the above-listed required Python packages.

### Check the installation

In the terminal or the Anaconda Prompt, type:

~~~
conda list
~~~
{: .language-bash}

## Launch a Jupyter notebook

After installing Anaconda,
launch a Jupyter notebook by typing this command from the terminal:

~~~
jupyter notebook
~~~
{: .language-bash}

The notebook should open automatically in your browser. If it does not or you
wish to use a different browser, open this link: <http://localhost:8888>.

For a brief introduction to Jupyter Notebooks, please consult with our
[Introduction to Jupyter Notebooks](https://datacarpentry.org/python-ecology-lesson/jupyter_notebooks/) page.

We use it for its user-friendly presentation of plots, data and text.
However, it [does cause problems](https://twitter.com/joelgrus/status/1044318416012750850)
for projects larger than a single analysis script.

## Install PyCharm with EduTools

We recommend [PyCharm Community](https://www.jetbrains.com/pycharm/download/)
for developing larger Python codes and projects.

It can be upgraded with [EduTools](https://www.jetbrains.com/help/education/install-edutools-plugin.html?section=PyCharm)
which makes many interactive tutorials available to continue learning.
