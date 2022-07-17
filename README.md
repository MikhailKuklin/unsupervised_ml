# Implementation of unsupervised machine learning techniques
A notebook with implementation of unsupervised techniques in a docker environment. Notebook 
includes:

* data preprocessing
* development of the models (k-means for hard clustering and GMM for soft clustering)

**Dataset:** Palmer Penguin

**Python library:** scikit-learn


# How to run the notebook?

**Option 1** 

If you have a docker installed :whale:, just create a docker image (in a repo root): `make -f Makefile.docker lab`

Next, go to local host and open notebook there: `http://localhost:8888` (password: unsup_ml) 

**Option 2** 

If you do not have docker on your PC, you can just open notebook using Google Colab or Jupyter. In that case, do not forget to install necessary packages (detailed instructions in the notebook)
