# This is just notes when I was setting up the environment for this project.

## first create a virtual environment

```
python3 -m venv <venv_name>

in this case, <venv_name> is "iris_venv" so..

python3 -m venv iris_venv
```

## Then, activate the virtual environment
```
source <venv_name>/bin/activate
# in this case, <venv_name> is "iris_venv" so..
source iris_venv/bin/activate
```

## Install the required packages using the following command
```
pip install -r requirements.txt
```

## To deactivate the virtual environment
```
deactivate
```

## To freeze the requirements
```
pip freeze > requirements.txt
```
