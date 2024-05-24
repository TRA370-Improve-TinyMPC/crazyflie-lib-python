## Requirements
#### Virtualenv
This section contains a very short description of how to use [virtualenv (local python environment)](https://virtualenv.pypa.io/en/latest/)
with package dependencies. If you don't want to use virualenv and don't mind installing cflib dependencies system-wide
you can skip this section.

* Install virtualenv: `pip install virtualenv`
* create an environment: `virtualenv venv`
* Activate the environment: `source venv/bin/activate`

## Install
### Clone  the repository
 ```
 git clone https://github.com/bitcraze/crazyflie-lib-python.git
 ```
### Install cflib from source
 ```
 cd crazyflie-lib-python
 pip install -e .
 ```
