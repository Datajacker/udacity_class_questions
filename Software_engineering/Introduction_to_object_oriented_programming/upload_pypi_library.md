```
cd binomial_package_files
python setup.py sdist
pip install twine
```

# commands to upload to the pypi test repository
```python
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
pip install --index-url https://test.pypi.org/simple/ dsnd-probability
```

# command to upload to the pypi repository
```python
twine upload dist/*
pip install dsnd-probability
```
