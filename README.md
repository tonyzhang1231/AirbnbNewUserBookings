





# How to set up the environment and train the model
I suggest using  `virtualenvwrapper`, then this project will not affect others
- Set up a virtualenv with python

`mkvirtualenv --python=/usr/bin/python nameOfyourEnvironment`

`workon nameOfyourEnvironment`

- Install all the requirements

`pip install -r requirements.txt`

- Install tensorflow and keras with gpu enabled

`pip install tensorflow-gpu`

`pip install keras`

- Setup ipykernel

`pip install ipykernel`

`python -m ipykernel install --user --name=nameOfyourEnvironment`

- Open jupyter notebook, choose nameOfEnvironment kernel