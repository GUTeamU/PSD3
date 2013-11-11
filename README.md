# REQUIREMENTS
* [python2.7](http://python.org/download/)
* [pip](http://www.pip-installer.org/en/latest/installing.html)
* [virtualenv](http://www.virtualenv.org/en/latest/virtualenv.html#installation)


#INSTALLATION

1. Clone the repository

2. Create a virtualenv for the project:
```bash
virtualenv VENV
source VENV/bin/activate
```

2. Install the dependencies:
```bash
pip install --no-deps -r requirements.txt
```


#RUNING

1. Activate the virtualenv:
```bash
source VENV/bin/activate
```

2. Run the test suite:
```
python test.py
```

3. Run the application:
```
python cats.py
```


