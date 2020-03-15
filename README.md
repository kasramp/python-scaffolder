# Python Scaffolder 

Scaffold your Python project in five minutes with this guideline.

## Requirements

+ Python 3+
+ Pip3+

Ensure they are installed

## Set up

### Install `virtualenv`

```bash
$ python3 -m pip install --user virtualenv
```

### Create your project directory

```bash
$ mkdir myproject && cd myproject
```

### Create a `virtualenv`

```bash
$ python3 -m venv env
```

### Activate `virtualenv`

```bash
$ source env/bin/activate
```

### Ensure `virtualenv` is working

```bash
$ which python
```

The result should point to your virtual env path.

### Install your packages

```bash
$ pip3 install [package name] # e.g., pip3 install fxcmpy python-socketio 
```

### Save installed packages to `requirements.txt` file

This is uselful whenever you want to run your project in a new system/environment.

```bash
$ pip3 freeze > requirements.txt
```

## Install all packages from `requirements.txt`

Run this when you want to run the project in a new system.

```bash
$ pip3 install -r requirements.txt
```

Finally to leave the `virtualenv` just type `deactivate`.
