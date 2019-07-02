## Introduction to Differential Privacy in Deep Learning

## This lesson covers the basics of differential privacy , a method for measuring how operations impact the privacy  of data. 

* **Part 1:** Introduction to Differential Privacy
* **Part 2:** Evaluating the Privacy of a Function
* **Part 3:** Introduction to Local and Gloabal Differential Privacy
* **Part 4:** Differential Privacy for Deep Learning
* **Part 5:** Project : Build Private Database in Python
    * For this project, install the required libraries, and work through the notebook Section 1 - Differential Privacy.ipynb


## Dependencies
To run these notebooks you'll need to install Python 3.6+, PySyft, Numpy, PyTorch 1.0, and Jupyter Notebooks. The easiest way for all of this is to create a conda environment and then install the dependencies in that environment. In your termina:

````
conda create -n pysyft python=3
conda activate pysyft
conda install numpy jupyter notebook
conda install pytorch torchvision -c pytorch
pip install syft
````

If you have any errors relating to zstd - run the following (if everything above installed fine then skip this step)
````
pip install --upgrade --force-reinstall zstd

````

and then retry installing syft (pip install syft). If this still doesn't work, and you happen to be on OSX, make sure you have [OSX command line tools](https://railsapps.github.io/xcode-command-line-tools.html) installed and try again.


If you are using **Windows**, I suggest installing Anaconda and using the Anaconda Prompt to work from the command line.

With this environment activated and in the repo directory, launch Jupyter Notebook:
````
jupyter notebook

````