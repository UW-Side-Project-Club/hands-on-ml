# Hands-on Machine Learning Workshop

## Getting set up computationally

### 1. Clone the repository

To get set up for this live coding session, clone this repository. You can do so by executing the following in your terminal:

```
git clone https://github.com/UW-Side-Project-Club/hands-on-ml.git
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository. If you prefer not to use git or don't have experience with it, this a good option.

### 2. Download Anaconda (if you haven't already)

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3, go get it (n.b., you can also do this w/out Anaconda using `pip` to install the required packages, however Anaconda is great for Data Science and I encourage you to use it).

### 3. Create your conda environment for this session

Navigate to the relevant directory `hands-on-ml` and install required packages in a new conda environment:

```
conda env create -f environment.yml
```

This will create a new environment called hands_on_ml. To activate the environment on OSX/Linux, execute

```
source activate hands_on_ml
```
On Windows, execute

```
activate hands_on_ml
```


### 4. Open your Jupyter notebook

In the terminal, execute `jupyter notebook`.

Then open the notebook `SupervisedLearning.ipynb` and we're ready to get coding. Enjoy.

## Resources:

 * [Numpy](www.numpy.org/)
 * [Pandas](pandas.pydata.org/)
 * [Scikit-learn](scikit-learn.org/)

### Used in this workshop:

1. https://www.datacamp.com/community/tutorials/kaggle-machine-learning-eda
2. https://www.datacamp.com/community/tutorials/kaggle-tutorial-machine-learning
3. http://shop.oreilly.com/product/0636920052289.do

## More 

### Tutorials:

1. https://www.datacamp.com/community/tutorials/machine-learning-python
2. https://github.com/datacamp/datacamp_facebook_live_titanic 
3. https://github.com/ageron/handson-ml 

### Books 

1. Joel Grus, [Data Science from Scratch](http://shop.oreilly.com/product/0636920033400.do) (O’Reilly). This book presents the funda‐ mentals of Machine Learning, and implements some of the main algorithms in pure Python (from scratch, as the name suggests).

2. Stephen Marsland, Machine Learning: An Algorithmic Perspective (Chapman and Hall). This book is a great introduction to Machine Learning, covering a wide range of topics in depth, with code examples in Python (also from scratch, but using NumPy).

3. [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do) (O’Reilly): Data Wrangling with Pandas, NumPy, and IPython (By William McKinney)

* Note: You will find free version of all these books with a quick google search!

Finally, a great way to learn is to join ML competition websites such as [Kaggle](https://www.kaggle.com) this will allow you to practice your skills on real-world problems, with help and insights from some of the best ML professionals out there.

### Working with Real Data

When you are learning about Machine Learning it is best to actually experiment with real-world data, not just artificial datasets. Fortunately, there are thousands of open datasets to choose from, ranging across all sorts of domains. Here are a few places you can look to get data:

* Popular open data repositories:
    1. [UC Irvine Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php)
    2. [Amazon’s AWS datasets](https://registry.opendata.aws)
    3. [Kaggle Datasets](https://www.kaggle.com/datasets)
* Meta portals (they list open data repositories): 
    1. http://dataportals.org/
    2. http://opendatamonitor.eu/
    3. http://quandl.com/
* Other pages listing many popular open data repositories: 
    1. [Wikipedia’s list of Machine Learning datasets](https://en.wikipedia.org/wiki/List_of_datasets_for_machine_learning_research)
    2. [Quora.com question](https://www.quora.com/Where-can-I-find-large-datasets-open-to-the-public)
    3. [Datasets subreddit](https://www.reddit.com/r/datasets)
* TCGA: The Cancer Genomics Data: 
    1. http://gdac.broadinstitute.org
    2. https://portal.gdc.cancer.gov 