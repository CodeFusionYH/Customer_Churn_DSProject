Customer Churn Prediction Project
=================================

This repository contains the code for a customer churn prediction project. Follow the steps below to set up the environment, install dependencies, and run the project.

---------------------------------
Prerequisites
---------------------------------
Ensure the following tools are installed:
- Anaconda (Download: https://www.anaconda.com/download)
- Visual Studio Code (VS Code) (Download: https://code.visualstudio.com/download)

---------------------------------
Project Setup Guide
---------------------------------

1. Clone the Repository
   --------------------
   Run the following commands:
   git clone <repository-url>
   cd <repository-folder>

2. Create and Activate Conda Environment
   --------------------------------------
   1. Open a terminal and create a Conda environment:
      conda create --name myenv python=3.9
   2. Activate the environment:
      conda activate myenv

3. Configure VS Code to Use Conda Environment
   -------------------------------------------
   1. Open Command Palette in VS Code: Ctrl+Shift+P.
   2. Search for Preferences: Open Settings (JSON) and add the following line:
      "python.condaPath": "C:/ProgramData/Anaconda3/Scripts/conda.exe"

---------------------------------
Dependencies Installation
---------------------------------

4. Install Project Dependencies
   -----------------------------
   Run the following command:
   pip install -r requirements.txt

5. Set Up Jupyter Notebook
   ------------------------
   1. Install Jupyter:
      pip install jupyter
   2. Install IPython kernel:
      conda install ipykernel
      python -m ipykernel install --user --name myenv --display-name "Python (myenv)"
   3. Launch Jupyter Notebook:
      jupyter notebook
   4. Install the Jupyter extension in VS Code (search for "Jupyter" in Extensions Marketplace).

---------------------------------
Troubleshooting Common Issues
---------------------------------

6. Conda Command Not Recognized
   -----------------------------
   1. Open System Properties > Environment Variables.
   2. Under System Variables, find the "Path" variable and ensure the following paths are added:
      - C:\Users\YourUsername\Anaconda3
      - C:\Users\YourUsername\Anaconda3\Scripts
      - C:\Users\YourUsername\Anaconda3\condabin
   3. Verify Conda works by running:
      conda --version

7. Set Default Shell in VS Code
   -----------------------------
   1. Open Command Palette: Ctrl+Shift+P.
   2. Search for Terminal: Select Default Profile.
   3. Choose Command Prompt or PowerShell.
   4. Open a new terminal (restart VS Code if necessary).

---------------------------------
About the Project
---------------------------------
This project aims to predict customer churn using machine learning models. The dataset and detailed methodology can be found in the repository.

Feel free to explore the code and contribute! For any issues, refer to the troubleshooting section above or raise a ticket in the repository.
