 # Quantitative Finance Mini-Project
Overview

This project is a practical introduction to quantitative financial analysis using Python. It demonstrates how to acquire historical market data, calculate key performance and risk metrics, and visualize concepts from Modern Portfolio Theory (MPT), such as the Efficient Frontier.

The analysis is performed within a Jupyter Notebook, and this guide explains how to set up the exact environment needed to run the code.

Prerequisites
Before you begin, ensure you have Anaconda or Miniconda installed on your system. This is required to manage the project's environment and dependencies.

Setup and Installation 🛠️
Follow these steps to clone the repository and create the necessary Conda environment.

1. Clone the Repository
Open your terminal or Git Bash and run the following command to clone this repository to your local machine.

git clone [https://github.com/your-username/your-repository-name.git](https://github.com/HongButNotY/QuantitativeTradingMiniProject1.git)
cd your-repository-name

git clone [https://github.com/your-username/your-repository-name.git](https://github.com/HongButNotY/QuantitativeTradingMiniProject1.git)
cd your-repository-name
Note: Remember to replace your-username and your-repository-name with my actual GitHub URL.

2. Create the Conda Environment from the YAML file
The environment.yml file included in this repository contains all the specific packages and versions needed to run the notebook. To create an identical environment, run the following command in your terminal from the project's root directory:

# This command reads the YAML file and installs all dependencies
conda env create -f environment.yml

3. Activate the New Environment
Once the installation is complete, activate the environment. The environment's name is specified inside the environment.yml file.

conda activate finance1

4. Register the Environment as a Jupyter Kernel
To make this new environment available in Jupyter Notebook or Jupyter Lab, you need to register it as a kernel. This allows you to select it from within your notebook.

# This makes the "Python (Finance Project)" kernel available in Jupyter
python -m ipykernel install --user --name=finance_env --display-name="Python (Finance Project)"

How to Run the Project 🚀
Start Jupyter Lab: With the finance_env environment still active, start Jupyter Lab by running:

jupyter lab

Open the Notebook: Your web browser will open the Jupyter Lab interface. Navigate to and open the .ipynb notebook file in this repository.

Select the Kernel: Inside the notebook, click on the kernel name in the top-right corner. From the dropdown menu, select "Python (Finance Project)" to ensure you're using the correct environment.

Run the Code: You are now ready to run the cells in the notebook to perform the financial analysis.
