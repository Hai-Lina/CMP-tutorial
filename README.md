# CMP-tutorial
A three hour hands-on tutorial for the Construct Mining Pipeline.

### Installing Anaconda and necessary packages
To benefit fully from the tutorial, please download Anaconda (=Python) onto your personal computer. Please follow the instructions here: [https://docs.anaconda.com/free/anaconda/install/index.html](https://docs.anaconda.com/free/anaconda/install/index.html). Please also make sure you have all necessary packages installed to run the code. This can be done by downloading the _CMP.yml or _CMP-macos.yml file from the repository (see above) and run the following command in your terminal: "conda env create -f _CMP.yml" (or _CMP-macos.yml, respectively). This can take quite some time, be patient! :) Make sure to cd (“change directories”) into the directory where the file lies before you execute the command. You can check whether the installation was successful using the command "conda info --envs" (you should see CMP among the listed environments). Contrary to my earlier message, you do not need to install Jupyter notebook separately. The .yml file will do this for you.

### Tutorial Schedule
9:00 - 9:15 Introduction\
9:15 - 9:35 Sentence embeddings\
9:35 - 9:45 Questions\
9:45 - 9:55 Measuring item bias\
9:55 - 10:15 Reducing item bias\
10:15 - 10:25 Break\
10:25 - 10:45 Reducing dimensionality & clustering\
10:45 - 10:55 Questions\
10:55 - 11:05 Checking robustness\
11:05 - 11:20 Validating clusters\
11:20 - 11:30 Interpreting and comparing\
11:30 - 12:00 Revisiting exercises, questions, discussion\
12:00 - ? Lunch at Spangler for people on site

### Packages needed
- jupyter notebook
- numpy
- pandas
- sentence-transformers
- umap-learn
- hdbscan
- plotly
- matplotlib
- bokeh
