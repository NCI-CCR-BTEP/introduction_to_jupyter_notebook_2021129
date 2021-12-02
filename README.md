[![Binder](https://mybinder.org/badge_logo.svg)](https://hub.gke2.mybinder.org/user/nci-ccr-btep-in-otebook_2021129-v7o7rkxb/lab)

# Publishing your data analysis story with Jupyter Notebook
This GitHub page contains material for an introduction to Jupyter Notebook course taught by the Bioinformatics Training and Education Program (BTEP) at National Institutes of Health.

Objectives for this course included:
* Obtaining an understanding of what Jupyter Notebook does
* Getting to know ways to access and use Jupyter Notebook
* Becoming familiar with the Jupyter Notebook interface and working in Jupyter Notebook
* Getting to know methods for sharing Jupyter Notebook


## Jupyter Notebook is used for the following
* Documentation of data analysis
  - Text
  - Images
  - Equations
  - Links
  - Code
* Allows for sharing of data analyses
* Facilitate data analysis reproducibility. Figure 1 adapted from Rule et al (https://arxiv.org/pdf/1810.08055.pdf) highlights the work flow for reproducible analysis.

<img src="reproducible_analysis_workflow.png" />
Figure 1: Reproducible analysis workflow


## Jupyter Note supports many languages
* Python
* R
* Julia
* C++
* Matlab
* Fortran

<img src="jupyter_note_book_supported_languages.png" />
Figure 2: From https://www.dataquest.io/blog/jupyter-notebook-tutorial

## Ways to access Jupyter Notebook
* NIH HPC (Biowulf; https://hpc.nih.gov/apps/jupyter.html)
* Anaconda or mini conda distributions (allows Jupyter Notebook to be use locally)
  - https://www.anaconda.com/
  - https://docs.conda.io/en/latest/miniconda.html 
* Google Colab	
* Cloud computing services

## Start Jupyter Notebook with Anaconda Navigator - click on the Jupyter Notebook tab
<img src="jupyter_on_anaconda.png" />
Figure 3: Starting Jupyter Notebook from Anaconda Navigator

* For Macs users, if going through mini conda 
  - From Finder, goto the Applications Folder
  - Select miniconda3 
  - Goto the bin folder
  - Click on jupyter-notebook and then copy and paste the URL that shows up in the terminal to a browser
* In Windows (I have a Windows 10 PC)
  - Goto Start
  - Then there should be a menu for Anaconda - open this
  - Click on Jupyter-Notebook (see Figure 4)

<img src="anaconda_jupyter_windows10.png" />
Figure 4: Starting Jupyter on Windows PC

## Figure 5 and Figure 6 show examples of R and Python Jupyter Notebooks.

<img src="jupyte_r_notebook_example.png" />
Figure 5: Example R Jupyter Notebook

<img src="jupyter_python_notebook_example.png" />
Figure 6: Example Python Jupyter Notebook
</p>

## Other ways to inferface with Jupyter Notebook
While we typically work with Jupyter Notebook via a web browser, there are other tools that we can use to interface with Jupyter Notebook.
* Visual Studio Code (https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
* Spyder IDE (https://github.com/spyder-ide/spyder-notebook) - Spyder IDE is an integrated development environment for Python (like what R Studio is for R)

## Sharing Jupyter Notebook with collaborators and other researchers
* Github (static)
* Binder (others can actually run the codes; https://mybinder.org/)
* Other tools for sharing Jupyter Notebooks exist (see table 1 in https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7359270/)

## Files in this repository
* Requirements.txt
  - Contains required packages for the Python portion of the demo Jupyter Notebook. 
  - When loading the demo Jupyter Notebook to Binder, this file is needed so that the appropriate packages will be installed
