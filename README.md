# Titanic scikit-learn demo

Jupyter Notebook for Data Science Presentation. This Notebook shows examples of Feature Engineering and Hyperparameter tuning.

### The Kaggle Titanic Problem
- https://www.kaggle.com/c/titanic/data

### Video: Dive Into Data Science and Build your First ML Model – With All Star Rhea 
- Tuesday, 8:30 AM PST on 15th March 2022
- https://www.youtube.com/watch?v=ToHp0hrNheI

### Dependencies
Install pip3 and python3 and then the necessary packages from requirements.txt
```
python -m pip install -r requirements.txt
```
I like to create a python virtual environment for individual projects. [This](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments) is a resource I refer to frequently.

Once you have pip3 installed locally, install the virtualenv package with
```
python3 -m pip install --user virtualenv
```

Then go ahead and create a virtual environment which will be saved in a directory called 'env' within your current directory, as follows
```
python3 -m venv env
```

<i>Note: You should exclude your virtual environment directory from your version control system using .gitignore or similar.</i>

Activate the virtual environment by
``` 
source env/bin/activate
```

And to deactivate, 
```
deactivate
```

Once you are within the active virtual environment you can install the dependent packages from the requirement.txt file in this repository by,
```
python3 -m pip install -r requirements.txt
```

In case you were wondering, I created the requirement.txt file like this,
```
python3 -m pip freeze
```