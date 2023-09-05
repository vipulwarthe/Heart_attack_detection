# Heart Attack Prediction Using Different ML Models:

# ABOUT HEART ATTACK:
A heart attack (Cardiovascular diseases) occurs when the flow of blood to the heart muscle suddenly becomes blocked. From WHO statistics every year 17.9 million dying from heart attack. The medical study says that human life style is the main reason behind this heart problem. Apart from this there are many key factors which warns that the person may/maynot getting chance of heart attack.

This dataset contain some medical information of patients which tells whether that person getting a heart attack chance is less or more. Using the information explore the dataset and classify the target variable using different Machine Learning models and findout which algorithm suitable for this dataset.

Table of Contents:

1) Import Packages
2) EDA
3) Preparing ML models
4) Models evaluation
5) Ensembling
6) Conclusion



# ML models:
Here I take different machine learning algorithm and try to find algorithm which predict accurately.

Logistic Regression
Naive Bayes
Random Forest Classifier
Extreme Gradient Boost
K-Nearest Neighbour
Decision Tree
Support Vector Machine

# First we Create instance with ubuntu AMI with t2.medium instance type with 30GB storage 


       sudo apt-get update && sudo apt-get upgrade -y       (update and upgrade the required packages)
       sudo apt install python3-venv -y                     (install python environment)
       python3 -m venv MLPRO                                (name given to the env MLPRO)
       source MLPRO/bin/activate                            (activate env)
       mkdir mlproject                                      (create one project directory)
       cd mlproject                                         (enter in project directory)

# Login to your github account and create a new repo and paste cmds from github repo:

      echo "# End-to-end-ML-Project" >> README.md
      git add README.md
      git commit -m "First Commit"
      git status
      git branch -M main
      git branch
      git remote add origin https://github.com/vipulwarthe/mlproject.git
      git push -u origin main
      git remote -v    (additional command)

# Create .gitignore file with python template in mlproject repo on github

      git pull    # It will pull the .gitignore file in VScode mlproject repo

# create setup.py and requirements.txt in mlproject repo add a code in setup.py & requirements.txt

# setup.py will be responsible in creating my ML application as a package
# setup.py is a module used to build and distribute Python packages
# requirements.txt file is a type of file that usually stores information about all the libraries, modules, and packages in itself that are used while developing a particular project

       pip install -r requirements.txt 
       git status
       git add .
       git status
       git commit -m "setup file added"
       git push -u origin main
