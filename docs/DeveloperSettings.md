# Dev Settings

Here is a summary on how to work with Python and Jupyter Notebooks for reference.

## How to Create a new Jupyter Notebook

Create and open your jupyter notebook by doing the following:

```bash
jupyter notebook
```

## Virtual Environments in Python

### Create a Virtual Environment

Create a new virtual environment using venv

```bash
python3 -m venv myvenv
```

A new folder was created for us named `myvenv` where we will find the following created for us:

```bash
+-- project_name
|   +-- myvenv
|   |   +-- bin # tools to start virtual env
|   |   +-- include
|   |   +-- lib  # packages and python versions
|   |   +-- lib64
|   |   +-- pyvenv.cfg
```

### Activating the Virtual Environment

To activate the virtual environment:

```bash
source myvenv/bin/activate
```

### Deactive the Virtual Environment

To stop the virtual envrionment:

```bash
deactivate
```

### Packages and Virtual Environments

To view our installed packages:

```bash
pip list
```

Upgrade pip:

```bash
python3 -m pip install --upgrade pip
```

Output all the installed packages into a new text file. This reference file can be used to create new virtual environments.

```bash
pip freeze > requirements.txt
```

To create a new virtual environment with our requirements, create a new virtual environment, activate it, and run the following:

```bash
pip install -r requirements.txt
```
