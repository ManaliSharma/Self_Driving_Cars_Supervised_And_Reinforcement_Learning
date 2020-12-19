# Umbrella_Academy
# Self Driving Car in OpenAI Gym using Imitation Learning and Reinforcement Learning
## Overview

### Part 1
Driving requires reacting to a wide variety of complex environment conditions and agent behaviors. Explicitly modeling each possible scenario is unrealistic. In contrast, imitation learning can, in theory, leverage data from large fleets of human-driven cars. In the following project we have tried simulating a beginner’s version of self-driving car using basics of Imitation Learning (Behavioral Cloning).

### Part 2
In the following project we implemented deep-q learning model for self driving cars.


## Requirements (Libraries)
- OpenAI Gym
- Tensorflow=1.15.0-rc3
- Pytorch=0.3
- PIL
- Keras
- Opencv
- Skimage
- Imageio
- Pyglet
- Numpy
- Matplotlib

## Environment Setup
In order to begin with this project, we suggest you to make two different virtual environment , one for supervised learning and other for reinforcement learning. This is done so that there is no conflict in version libraries installed. 

- Commands for making new virtual environment in Anaconda:-

> - conda create -n yourenvname python=3.7 anaconda
> - conda activate yourenvname
> - conda install -c conda-forge nb_conda_kernels
> - conda install -c conda-forge nb_conda
> - conda install -c conda-forge ipykernel


### For other person to use the environment
conda env create -f <environment-name>.yml

## Python Files (Mandatory)
For your code to run smoothly there are some python scripts in (folder modules) which are imported in notebooks directly. In order to understand the models better please go through those scripts.


## Folder Structure

- INFO7390_SelfDrivingCar
- README.md
- Research Paper
- INFO7390_FinalProject.ipynb
- main_videos
- images_main_notebook
- autonomous.yml
- self-driving.yml
- requirements_SL.txt
- requirements_RL.txt
> Umbrella_Academy_INFO7390_Project
- INFO7390_Notebooks
    - sdc_gym (gym environment)
    - modules (py files)
        - SL_model.py
        - SL_data.py
    - Basics_of_Convolutional_Neural_Network.ipynb
    - Self Driving Car using Supervised Learning
    - Basics_of_Deep_Q_Learning
    - Self Driving Car using Reinforcement Learning 
    - Supervised_IL_train_images
    - Supervised_IL_test_images
    - Supervised_IL_models
    - Images (All images used in project)
   

## How to Run
- Clone the repository in your local disk.
- Refer the folder structure mentioned above, and open the file "INFO7390_FinalProject.ipynb".
- This is the master notebook and it links to all the different parts of the project.
- Please make sure that the libraries mentioned above are all installed


