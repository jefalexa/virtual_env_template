# virtual_env_template

## Setup Process - First time only
### Install Python3.7
https://www.python.org/downloads/release/python-372/

### Install PIP
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

sudo python get-pip.py

### Install VirtualEnv
sudo pip3 install virtualenv

### Create the local VirtualEnv
python3 -m virtualenv env

source env/bin/activate

pip install -r requirements.txt

deactivate

## Usage Process - How to run the script from within the venv
### Activate the Virtual Environment
source env/bin/activate

### Launch the notebook with code
env/bin/jupyter-lab

### When Finished:
deactivate
