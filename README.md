# nm_distributions
This repo contains the source code for custom nm-distributions package that can be found at www.pypi.org and can be installed by :
```
pip install nm-distributions```

##Getting Started
This repo can also be used to locally install the nm-distributions package. Firstly, create a virtual environment from your terminal:
`conda create --name environmentname pip`
Activate your virtual environment:
`source activate environmentname`
Go to the folder where you have cloned this repo install the package via pip. Pip looks for the setup.py file for installtion:
`pip install .`
Now that the package is locally installed, you can use the following python code in any of your local projects to play around with Gaussian and Binomial distribution functionalities provided with the package.
`from distributions import Gaussian`
`from distributions import Binomial`
