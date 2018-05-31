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
