# Environment Setup
  - Ensure Git is installed on your system. http://git-scm.com/downloads/win
  - Ensure Python and pip are installed and that your system environmental variables points to the /Scripts file of your python install folder.
      - https://www.python.org/downloads/ The links here should install pip with Python, you may need to ensure that it is configured to install pip when running the installer.
      - Otherwise follow this for pip install: https://packaging.python.org/en/latest/tutorials/installing-packages/
  - run ```pip install jupyterlab``` to install jupterlab
  - run ```pip install --upgrade jupyterlab jupyterlab-git``` to install Git extension for Jupter Lab (https://github.com/jupyterlab/jupyterlab-git)
  - To run jupyter lab, open command prompt from the folder you want the cloned the repo to be stored, run ```jupyter lab``` into command prompt to open the jupter lab environment.
  - Clone this repo in the Git extension in jupyter lab (https://github.com/ColinCPittman/Cycle-Detection.git)
  - run ```pip install networkx``` and ```pip install matplotlib``` to get the necessary libraries to visualize the graphs.
  - **Optional** run ```pip install jupyterlab-lsp``` and ```pip install python-lsp-server``` to improve coding quality-of-life with more IDE features.
    
