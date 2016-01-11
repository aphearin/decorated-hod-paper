# decorated-hod-paper
This contains code to generate all results in the Introducing Decorated HODs paper (Hearin et al. 2015). 

The notebook contained in the root directory contains annotations providing instructions for how to download and build the code, download the necessary simulation data, and use Halotools to produce the figures published in the paper. Through a combination of the overview given in this notebook and the documentation found on http://halotools.readthedocs.org, you should be able to gain a working knowledge of how to work with Decorated HODs. 

If you have any problems executing the notebook, or otherwise have questions/comments, please contact andrew.hearin@yale.edu. 

## Instructions

To reproduce the results in the paper, open up a terminal and execute the following commands:

$ cd any/working/directory/

$ git clone https://github.com/aphearin/decorated-hod-paper.git

$ cd decorated-hod-paper

$ ipython notebook generate_abthy_results.ipynb

You will need to have ipython installed, as well as the Halotools package dependencies (see halotools.readthedocs.org)