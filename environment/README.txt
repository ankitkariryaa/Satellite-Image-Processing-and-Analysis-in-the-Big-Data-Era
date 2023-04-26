
Python environment for the course: NIGK22000U Satellite Image Processing and Analysis in the Big Data Era

A. Install mamba https://mamba.readthedocs.io/en/latest/installation.html

B. Please run in order:

1 $ mamba env create --file environment_win1.yml
2 $ mamba env update --name tf --file environment_win2.yml
3 $ mamba env update --name tf --file environment_win3.yml

C. In case of an issue with tensorflow-estimator version run:

$ mamba activate tf 
$ pip install --upgrade tensorflow-estimator==1.15.1

