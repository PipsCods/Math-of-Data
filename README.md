# Math of Data

Welcome to the **Math-of-Data** repository! This document will guide you through using Git and GitHub, as well as how to set up your development environment using the provided *environment.yml* file.

## 1. Setting Up Git

Before you start using Git, make sure you have it installed on your machine. You can download it from https://git-scm.com/.

#### Configuring Git 

After installation, configure your Git identity:

´´´bash  
git config --global user.name "Your Full Name"  
git config --global user.email "your.email@example.com"  
´´´
## 2. Cloning the Repository

To get a copy of the project on your local machine, you need to clone the repository:

´´´bash  
git clone https://github.com/YourUsername/Math-of-Data.git  
´´´

Replace *YourUsername* with your Username.

## 3. Important Git Commands
- Check Status: git status  
- Adding Changes: git add {filename} , this stages a specific file. To stage all changes, use: git add .
- Committing Changes: get commit -m "Your commit message here"  
- Pushing Changes: git push 
- Pulling Changes: git pull origin master

## 4. Branching

To create a new branch for your work (name your branch with your name so everybody know who is the owner of that branch)

´´´bash  
git checkout -b branch-name  
´´´  

to switch back to the master branch:  

´´´bash  
git checkout master  
´´´  
to marge your branch:  

´´´bash  
git merge branch-name  
´´´  

#### Using the *environment.yml* file (Not necessary)

The *environment.yml* file is used to create a conda environment that contains all the necessary packages for this project.
In this way we avoid package conflict using only the library in the requirement.txt for the assignment without mixing it with all the package in our PCs.

- Make sur you have Anaconda installed. If you dont you can download it from https://www.anaconda.com/products/distribution
- Navigate to the project directory in your terminal.
- Create the conda environment using the *environment.yml*  
  ´´´bash  
  conda env create -n environment-name -f environment.yml  
  ´´´  
- Activate the environment:  
  ´´´bash  
  conda activate environment-name  
  ´´´  
  Replace environment-name with a name of your choice.

#### Updating the Environment

If changes are made to the *environment.yml* file, you can update your environment with:

´´´bash  
conda env update -f environment.yml  
´´´  

  
  
  











