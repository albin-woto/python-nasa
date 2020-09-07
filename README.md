# Microsoft and NASA's project 
## Learning how to classify rocks with AI using python

The project contains:
* An introduction to Python Notebooks in VS Code
* How to read a file and manage that data with python
* The creation of an AI that is trained to classify rocks from a given folder with images of those types of rocks

***

### Configuration

This particular project was created fully in vscode and instead of using anaconda to manage all the python modules, a virtual environment was created from python:3.8.5 and configured to run those packages, you can find them all in `/rock-recognition/requirements.txt`

The libraries used in this project are:
* pandas
* jupyter
* seaborn
* scikit-learn
* keras
* torch
* torchvision

But you can easily install them from the terminal (after activating your virtual environment- recommended) with the following command  
`pip3 install -r ./rock-recognition/requirements.txt`  

To reduce the size of the project there's a Data.zip to train and test the AI with all the pictures, must be unzipped as `/rock-recognition/data` before running the code.

***

### Links

You can checkout the courses here:  
* [Introduction to Python for space exploration](https://docs.microsoft.com/en-us/learn/modules/introduction-python-nasa/)  
* [Learn about space rocks and how to classify them](https://docs.microsoft.com/en-us/learn/modules/research-space-rocks-ai-nasa/)
* [Predict rocket launch delays with machine learning](https://docs.microsoft.com/en-us/learn/paths/machine-learning-predict-launch-delay-nasa/)
