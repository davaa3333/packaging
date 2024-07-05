
# Build the package
1. Goto Project directory and install dependencies
`pip install -r requirements.txt`
2. create Pickle file after training:
`python prediction_model/training_pipline.py`
3. Create source distribution and wheel
`python setup.py sdist bdist_wheel`

# installation of Package
go to project directory where `setup.py` file is located
1. To install it in editable or developer mode

```python
pip install -e .
```


## Virtual Environment
Install virtualenv

```python
python3 -m pip install virtualenv
```

check version
```python
virtualenv --version
```

 create virtual environtment

 ```python
 virtualenv ml_package
 ```

 activate virtual environment

 for linux/mac
 ```python
 source ml_package/bin/activate
 ```
 for windows 
 ```python
 ml_package\Scripts\activate
 ```