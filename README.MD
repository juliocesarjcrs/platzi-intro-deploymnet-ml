## Installation

### virtual enviroment
Check that we have virtualenv with:
```
virtualenv --version
```
Or the contrary install virtualenv.

```sh
pip3 install virtualenv
```

Then create the virtual enviroment [venv] is the name of the us envioroment. The nex comand also create a folder con the same name.

```sh
virtualenv venv
```
Then we can activate our enviorment with:
```sh
source venv/bin/activate
```
### Install requirements

Is important to have the previso step(enviorment active) beside the check that requiremnets are in path 'notebooks/requirements.txt'
```sh
pip install -r notebooks/requirements.txt
```
