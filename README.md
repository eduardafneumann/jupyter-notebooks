# Sklearn scripts

This repository contains some jupyter notebooks that use the sklearn library to deal with clustering and classification problems. In the 'kmeans' notebook, klearn.cluster.KMeans is used to compress images by clustering the pixels in a set number os colors. In the 'mpl-classifier' notebooks, sklearn.neural_network.MLPClassifier is used to estimate the quantity of bikes rented in a given hour with infomations such as month, season, humidity and temperature. In the 'rf-classifier' notebook, sklearn.ensemble.RandomForestClassifier is used to estimate the probability of a transaction being fraudulent and simulate what would be the net gain if the top 1% suspected transaction were blecked.

# Create virtual environment

Run 'python3 -m venv venv' to create a virtual environment, run 'source venv/bin/activate' to activate it, and 'pip install -r requirements.txt' to install dependencies.

# Run jupyter notebooks

Once with the virtual environment activated and dependencies installed, run 'jupyter notebook' to initiate the jupyter server. Once the interface opens in your browser, you can run and interact with the notebooks from there.
