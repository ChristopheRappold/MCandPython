# MCandPython

Jupyter sessions for lecture on Python and Monte Carlo techniques.

1. Introduction to Python for numerical calculations
   + The language: basics and syntax
   + Numpy module
   + Matplotlib module

2. Monte Carlo techniques in statistics and error handling.

## How to install Python and that is necessary for the lectures

   + What is mendatory:
	 - Python > v3.5
     - jupyter module
     - numpy module
     - matplotlib module
     - scipy module
     - pandas module
     
   + Windows:
     - If you are familiar with prompts or Python is already installed by administrators but you can not have admin access go to (2.):  
   
	   1. Go to https://www.python.org/ and download the windows version (or go directly here: https://www.python.org/downloads/windows/ ). Take executable installer of the version > 3.5 (currently at the creation of this readme it is 3.6.1)
	   2. Open a powershell prompt (search for powershell executable)
	   3. Then create a "virtual environment" that will have isolated environment in which you can install modules without affecting the main installation:
	 ```
     python -m venv myenv
     ```
       4. Set the environment variables:
     ```
     myenv\Scripts\activate
     ```
       5. Now install jupyter module :
     ```
     pip3 install jupyter
     ```
       6. Now install the other modules :
     ```
     pip3 install numpy
     pip3 install matplotlib
     pip3 install scipy
     pip3 install pandas
     ```
       7. You can start a jupyter server with:
     ```
     jupyter notebook
	 ```
	 - If you have admin access and want to be quick :
       1. Go to Anaconda website: https://www.continuum.io/downloads and download the packaged python distribution that will includes jupyter, numpy, etc in one setup.

   + Linux :
     1. Install through your distribution the version python that you want (2.7 or >3.5)
     2. Use pip install or pip install --user to install the following modules :
     ```
     pip3 install --user jupyter
     pip3 install --user numpy
     pip3 install --user scipy
     pip3 install --user pandas
     pip3 install --user matplotlib
     ```
     3. You can start a jupyter server with
     ```
     jupyter notebook
     ```
 
