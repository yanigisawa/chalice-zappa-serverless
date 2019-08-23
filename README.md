# chalice-zappa-serverless
Presentation slides for IndyPy Web Conf 2019

To install and download all dependencies for this repo: 

`pipenv install`

Each serverless example project is in a sub-directory from this repository. I used this top-level Pipfile to store the dependencies for running each of the sub-projects within this repository. This is bad for Zappa since it uses the currently installed packages of the virtualenv for deployment to AWS. Better would be to use a separate virtualenv with just the dependencies you need for your zappa project. 
