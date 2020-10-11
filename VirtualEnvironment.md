#### Why I need Python virtual environment?
* Create isolated environment on each projects.
* Maintain dependencies.
* What next :v ???

Python virtual environment
There are three ways to create the Python virtual environment that I used.
* Pipenv
* Virtualenv
* Conda

Assuming you've already installed pip.

### PipEnv

Install
```
pip install pipenv
```
Create new environment
```
pipenv install
```
Active
```
pipenv shell
```
Ref: https://pypi.org/project/pipenv/


### Virtualenv

Install
```
pip install virtualenv
```
Create new environment
```
virtualenv Name
```
Active
```
. Name\bin\activate
or
. Name\Scripts\activate
```
Deactivate
```
deactivate
```
Delete
```
rm -r /path/to/ENV
```
Ref: https://virtualenv.pypa.io/en/latest/userguide/

### Conda

Install
```
conda create --name virtual_name python=[version]
```
example: [version] : 3.6, 3.9

Active
```
activate virutal_name
```

Install Packages
```
conda install -n virutal_name [package]
```

Deactivate
```
deactivate
```

Delete
```
conda remove -n virtual_name -all
```

Ref : https://medium.com/@krishnaregmi/pipenv-vs-virtualenv-vs-conda-environment-3dde3f6869ed


### Docker contain the Jupyter notebooks
https://u.group/thinking/how-to-put-jupyter-notebooks-in-a-dockerfile/
