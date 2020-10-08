[![Build Status](https://travis-ci.com/Arrotech/ALX-IMS.svg?branch=develop)](https://travis-ci.com/Arrotech/ALX-IMS) [![Coverage Status](https://coveralls.io/repos/github/Arrotech/ALX-IMS/badge.svg?branch=develop)](https://coveralls.io/github/Arrotech/ALX-IMS?branch=develop) [![Heroku](https://heroku-badge.herokuapp.com/?app=heroku-badge)] [![Maintainability](https://api.codeclimate.com/v1/badges/22a834de460f5310d730/maintainability)](https://codeclimate.com/github/Arrotech/ALX-IMS/maintainability) [![codecov](https://codecov.io/gh/Arrotech/ALX-IMS/branch/develop/graph/badge.svg)](https://codecov.io/gh/Arrotech/ALX-IMS)


## ALM-IMS

Design and develop the back-end service for the Information Management System.

#### ENDPOINTS

| EndPoints                     |           Functionality            | HTTP Method |
| ----------------------------- | :--------------------------------: | ----------: |
| /api/v1/auth/register         |            Create user             |        POST |
| /api/v1/auth/login            |          Login to account          |         POST |
| /api/v1/users                 |             Fetch Users            |        GET |
| /api/v1/users/`username`      |          Fetch User                |         GET |
| /api/v1/reset                 |           Password Reset Email     |         POST |
| /api/v1/reset/`reset_token`   |            Reset With Token        |         POST/GET |
| /api/v1/auth/refresh          |           Get Access Token         |      POST   |
| /api/v1/auth/protected        |       Get Email                    |         GET |
| /api/v1/confirm/`token`       |              Confirm Email         |        GET  |

#### TOOLS TO BE USED IN THE DEVELOPMENT

1. Server-Side Framework: [Flask Python Framework](http://flask.pocoo.org/)
2. Linting Library: [Pylint, a Python Linting Library](https://www.pylint.org/)
3. Style Guide: [PEP8 Style Guide](https://www.python.org/dev/peps/pep-0008/)
4. Testing Framework: [PyTest, a Python Testing Framework](https://docs.pytest.org/en/latest/)
5. Testing Framework: [Coverage, a Python Testing Framework](https://coverage.readthedocs.io/en/v4.5.x/)

#### REQUIREMENTS

This are the basic project requirements. Make sure to install the before attempting to run the project.

    1. Python: [Install Python3](https://realpython.com/installing-python/)
    2. Postgres: [Install Postgres](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04)
    3. Git: [Install Git](https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-18-04)
    4. Node: [Install Node](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04)
    5. Postman: [Install Postman](https://linuxize.com/post/how-to-install-postman-on-ubuntu-18-04/)

The others can be downloaded and install from the requirements file. The installation process is outlined in the section `How to run the application`.

#### HOW TO RUN THE APPLICATION

Note that this project is meant for linux.

1.  Make a new directory on your computer and name it `ALX-IMS` or give it any name of your choice.
2.  Navigate to the directory you have created and open it in the terminal.
3.  On the terminal type `git clone` and add this link <code>[repo](https://github.com/Arrotech/ALX-IMS/)</code> and the press `enter` to clone the remote repository to your local repository i.e `git clone 'link'`. Add the link without the quotation.
4.  Navigate to the directory that has been cloned to your machine and open it in a terminal.
5.  Create virtual environment by typing this in the terminal `virtualenv -p python3 venv`.
6.  Run `pip install -r requirements.txt` on the terminal to install the dependencies.
7.  Then type on the terminal `source .env` to activate the environment and also to export all the environment variables.
8.  Then type on the terminal `flask run` to start and run the server.

#### RUN IN POSTMAN

Use the following button to run the app from a postman copy collection.

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/019962cfc8b440792425)

#### HOW TO RUN TESTS

1.  Open a new terminal and then activate the environment.
2.  Type `pytest --cov=app --cov-report=term-missing` and hit `enter`. This will run all tests and then give you a Coverage with details.

#### OTHER IMPORTANT LINKS

1.  Heroku deployment of the application: [Heroku](https://alx-ims.herokuapp.com/)
2.  Continuous Integration: [TravisCI](https://travis-ci.com/github/Arrotech/ALX-IMS)
3.  Test coverage: [Coveralls](https://coveralls.io/github/Arrotech/ALX-IMS)
4.  Test coverage: [CodeCov](https://codecov.io/gh/Arrotech/ALX-IMS)
5.  Code Documentation: [Apiary](https://alxims.docs.apiary.io/)


## Contributors

    ALX

## Author

    Harun Gachanja