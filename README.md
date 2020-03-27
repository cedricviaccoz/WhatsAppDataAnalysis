# WhatsAppDataAnalysis
Small notebook to plot some statistics of WhatsApp discussions

You will need to be able to run jupyter notebook on your computer in order to run the .ipynb file of this repository. The [following link](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook) will guide you through how to install and use a jupyter notebook if you don't already know how.

The following python packages will need to be already installed in order to run the notebook correctly:

* pandas
* seaborn
* emoji

Normally the command '''pip install <package_name>''' on a terminal should suffice in order to install those packages.

Once all the requirements are installed, simply open the notebook on your jupyter server and start reading the first cell of text to get started!

### Changelog:

* November 2018: Period during which the notebook was first created with most of its code.
* February 2019: Refactoring, add of comments and textual cell, and upload on github.
* March 2019: @ArnaudPanatier Added "Number of word per person" and "Most talking person ranking" functions + inline matplotlib fix.
* March 2020: @ArnaudPannatier Fixed parsing of messages with newlines ('\n') whose content after the first newline was discarded 
* March 2020: @ArnaudPannatier and (a tiny amount) @cedricviaccoz fixed parsing using regex so it works on data extracted from Android devices 
