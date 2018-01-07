# Classification_in_python
In these Jupyter notebooks , we are performing Classification on two datasets:
 - CMC dataset
 - Mushroom Dataset
 
# Contraceptive Method Used Dataset Classification
In this Notebook, we will be using the Contraceptive Prevalence dataset. This dataset is a subset of the 1987 National Indonesia Contraceptive Prevalence Survey. The samples are married women who were either not pregnant or do not know if they were at the time of interview. The problem is to predict the current contraceptive method choice (no use, long-term methods, or short-term methods) of a woman based on her demographic and socio-economic characteristics.

The dataset can be found here : https://archive.ics.uci.edu/ml/datasets/cmc
The notebook can be downloaded from this link:
https://github.com/saxenakrati09/Classification_in_python/blob/master/Data%20Science%20Workbook%20-%20cmc%20Dataset.ipynb

# Mushroom Dataset Classification
In this Jupyter Notepad, we will using the Mushroom Dataset to predict whether a Mushroom is edible or poisonous. This dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy.

The dataset can be found here: https://archive.ics.uci.edu/ml/datasets/Mushroom
The notebook can be downloaded from this link:
https://github.com/saxenakrati09/Classification_in_python/blob/master/Data%20Science%20on%20Mushroom%20Data.ipynb

## Steps
In this Notebook, we'll perform:

- Feature Exploration (Uni and Bi-variate)
- Feature Imputation
- Feature Selection
- Feature Encoding
- Feature Ranking
- Machine Learning with sklearn and Tensorflow
- Random Search
- Accuracy, Precision, Recall, and f1 calculations
- ROC Curve

## Setup
This Notebook has been designed to be run on top of the Jupyter Tensorflow Docker instance found in the link below:
- https://github.com/jupyter/docker-stacks/tree/master/tensorflow-notebook

If you haven't downloaded Docker at this point, please visit:
- https://www.docker.com/get-docker

Then, open a shell or terminal session and copy/paste the following:

```shell
docker run -itd \
  --restart always \
  --name jupyter \
  --hostname jupyter \
  -p 8888:8888 \
  -p 6006:6006 \
  jupyter/tensorflow-notebook:latest \
  start-notebook.sh --NotebookApp.token=''
```

Upon running the command, docker will automatically pull the images it needs and get the containers going for us.

Give it a minute or so for Jupyter to start, and head to the following URL: http://localhost:8888

You should now have Jupyter running. If after a minute you can't reach the URL, check that the containers are running correctly and the network has been created by typing:

```shell
### Check the containers are running
docker ps -a
```
## Loading the Notebook
Download the notebook from this repository.

Go back to:
- http://localhost:8888, load your Notebook into Jupyter and run it. That's it!


## Troubleshooting Docker
Here's a few useful commands in case something goes wrong with your docker instance:

```shell
# Restart Jupyter Docker Container
docker restart jupyter

# Stop Jupyter Docker Container
docker stop jupyter

# Remove Jupyter Docker Container
docker rm jupyter
```

Feature Exploration (Uni and Bi-variate)
Feature Imputation
Feature Selection
Feature Encoding
Feature Ranking
Machine Learning Training
Random Search
Accuracy, Precision, Recall, and f1 calculations
ROC Curve
