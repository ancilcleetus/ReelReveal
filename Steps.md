# ReelReveal: Step-by-Step Development Log

## Project Initialization

### Download and install Python 3.12

### Create folder for model => ReelReveal-video-sentiment-model

### Open model folder in VSCode

### Install VSCode extensions => Python, Pylance, Python Debugger, autopep8, isort

### Create Virtual Environment in model folder using VSCode
* VSCode: View => Command Palette => Python: Create Environment
* Select an environment manager: venv
* Select a Python environment: Python 3.12.13 /usr/local/bin/python3.12
* Enter a name for the virtual environment: .venv
* Select an option: Skip package installation

### Setup terminal in VSCode
* Right click on the empty space on left side (Explorer)
* Choose 'Open in Integrated Terminal'
* Wait for VSCode to automatically activate venv
* `python --version` => verify Python version as 3.12
* `pip --version` => check python package manager
* `pip list` => shows list of installed packages

## Download MELD Dataset
* Go to [Multimodal EmotionLines Dataset (MELD)](https://affective-meld.github.io/)
* `wget https://web.eecs.umich.edu/~mihalcea/downloads/MELD.Raw.tar.gz`  # Download MELD dataset inside VSCode Integrated Terminal

## Installation of Libraries and Dependencies
