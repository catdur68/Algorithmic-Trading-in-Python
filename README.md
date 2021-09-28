# Algorithmic-Trading-in-Python
This was my first project after my training at the Tech Academy followed by a 6-month sabbatical. To get back into my groove, I searched the internet for projects that interested me. This was one of them. It refreshed my memory on things covered at the Tech Academy and exposed me to Jupyter Notebook, and exporting to an xlsx file. Nick McCullum expected the student to fork from his repository. I wanted to do it from scratch (install Jupyter Notebook, create an account with iex finance cloud API, use the Command Line to create my Virtual Environment, updates my pip, upload to GitHub, etc...)

Nick's course file is at: https://github.com/nickmccullum/algorithmic-trading-python/
The course contains 3 different projects:
1) Building An Equal-Weight S&P 500 Index Fund
2) Building A Quantitative Momentum Investing Strategy
3) Building A Quantitative Value Investing Strategy

-------------------------------------------------------
Below are my mental notes (steps taken to start the first project which was much needed at the start of this project). 

PREP WORK: Library Imports & Virtual Environment

C:\Users\catdu\OneDrive\Documents\MyPythonProjects\MyVirtualEnvironment\Trading1

Have a virtual environment folder for the project:
 - pip install pipenv
 - Make a src directory

Create a virtual environment --> type virtualenv venv
that will create a venv, scripts, lib directories

Pipfile: 
C:\Users\catdu\OneDrive\Documents\MyPythonProjects\MyVirtualEnvironment\Pipfile
Using 
C:/Users/catdu/AppData/Local/Programs/Python/Python39/python.exe (3.9.0) to create virtualenv...

- pipenv install requests - I kind of recall this should be done in the script directory...
(MyPythonProjects-iJ46yVg-) C:\Users\catdu\OneDrive\Documents\MyPythonProjects\MyVirtualEnvironment>pipenv install requests

Activate the virtual environment: 
C:\Users\catdu\OneDrive\Documents\MyPythonProjects\MyVirtualEnvironment\Trading1\Scripts>activate

Now, in Scripts (folder to be verified) install all the pip necessary for the project in command line.
pip install jupyter notebook
pip install numpy
pip install panda
pip install iexfinance


Move to the main direcctory for the project and in command line open jupyter notebook
