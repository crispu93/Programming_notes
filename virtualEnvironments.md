# Virtual environments
Virtual environments deals with incompatible versions of the same add-ons
or packages that don't play nice with each other.

A virtual environment mantains a discrete copy of the python interpreter.

## Create a virtual environment
```sh
$ python -m venv /path/to/directory
```
## Activate a virtual environment
On Unix or MacOS:
```shell
$ source /path/to/venv/bin/activate
```
On Windows 
```shell
$ path\to\venv\Scripts\activate.bat
```

## Upgrade pip in a virtual environment
```shell
$ python -m pip install -U pip
```

## Managing packages in virtual environments
```shell
$ pip install -r requirements.txt 
```

## Deactivating a virtual environment
On Unix or MacOS:
```shell
$ deactivate
```
On Windows:
```console
$ path\to\venv\Scripts\deactivate.bat
```

## Upgrading virtual environments
If you’ve upgraded an existing Python interpreter with a minor point upgrade—e.g., from Python 3.9.5 to Python 3.9.7 — you can upgrade any corresponding virtual environments easily enough:
```shell
$ python -m venv /path/to/venv --upgrade
```
