# Introduction: 
This is a set of instructions meant to help run the notebooks made for Optimization Algorithms in Attack Detection for IoT Networks. It can also be found in the readme of this Github repository: https://github.com/bethanygoss/net_sec_25.git which was made for this project. 

We offer two sets of instructions: running in Google Colab and running on local. 

The default models and optimized models should have average runtimes of 16 minutes. Any optimization attempt should be expected to take at least 7 hours. The notebooks given contain all three: the default model, the optimization function, and the optimized model. 

Why do this? 
	To see if specific meta heuristic algorithms produce consistently better results than their peers. We chose from 3 different sub-types of meta heuristic algorithms: human based (Life Choice Based Optimizer/LCBO/LCO), swarm based (FOX), and biology inspired (Seagull/SOA). 

## Google Colab
### Set Up & Execution
1. Create / have a Google account.
2. Log into Google Colab with that account
3. Clone the GitHub Repository to your local device.
    a. git clone https://github.com/bethanygoss/net_sec_25.git 
4. Upload the Dataset/Datasets: 
    a. Upload the specific dataset the notebook calls for: you’ll see the one in the screenshot is called Weather. 
    b. So you will open up the Train_Test_IoT_dataset folder and find Train_Test_IoT_Weather.csv and upload it locally. You can see this on the next page. 
5. Once this is done head to the top taskbar select Runtime and Run All

## Local Execution
Not every notebook can be run in Google Colab, specifically IoT Network can take longer than 24 hours depending on GPU and CPU capabilities. 

If you’d like to attempt longer runtimes and don’t want to pay for Google Colab Pro, then you can run these notebooks on your local machine. 

### Requirements
8GB of RAM (16 is recommended)
Multi - Core Processing (at least 2)
We ran Intel i7 or up. 
Python 3.11.9 or lower. (Python 3.12 was not workable for us) 
 VS Code

### Set Up & Execution
Install Python 3.11 from this website:  https://www.python.org/downloads/
Install VS code from this website:  https://code.visualstudio.com/download

1. Clone the Github repo: git clone https://github.com/bethanygoss/net_sec_25.git
2. Open VS Code
3. Open the chosen notebook. 
4. When you hit run all
    a. Install Recommended Extensions
    b. Python Environments 
        i. Select Python 3.11.9
            1. It will have installed: Python Debugger, Python, Pylance, Jupyter Slide Show, Jupyter Notebook Renderers, Jupyter Keymap, Jupyter Cell Tags, and Jupyters
            2. If you have a current Python environment in VS Code, then it may prompt you to install ipykernel to run the kernel. 