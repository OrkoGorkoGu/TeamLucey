# Team Lucey CS 190 Project
## Initial Setup
**(Recommended): Create and activate a virtual environment for this project.**

**Install required packages**

`pip install -r requirements.txt`

***

In src folder, you will find R Markdown (.Rmd) files. These are essentially copies of any used jupyter notebooks without having all of the JSON output.

**To convert Rmd into a runnable python file or Jupyter notebook:**

`jupytext --to [notebook | py] notebook.md`

Examples: 
    
    jupytext --to notebook DataCleaning.Rmd

    jupytext --to py DataCleaning.Rmd

For more information, check out:    

https://towardsdatascience.com/version-control-with-jupyter-notebooks-f096f4d7035a 

or

https://github.com/mwouts/jupytext
