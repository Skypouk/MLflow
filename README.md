# MLflow
Using MLflow for tracking AI models runs and packaging data science code in a reusable and reproducible way

Adding MLflow commands to code to enable experiments tracking

Using MLProject and yaml files in order to facilitate the reproduction of the models results

# Dataset 
The dataset used in this example is from http://archive.ics.uci.edu/ml/datasets/Wine+Quality, We aim to predict the quality of the wine by giving a rate between 3 and 9.

# Trained Model
The elastic net is a regularized regression method that linearly combines the L₁ and L₂ penalties of the lasso and ridge methods.

# How to use MLflow
the repository contains the files MLproject and conda.yaml, MLproject file specify the dependencies and entry points to your code. While the conda.yaml file has the dependencies located in a Conda environment file, which garantees the reproducity of the results by enabling the user to run the model in a completely similar environment.

# MLflow Commands
by running the command :
mlflow run https://github.com/Skypouk/MLflow.git -P alpha=5.0

MLflow runs your training code in a new Conda environment with the dependencies specified in conda.yaml.
