# DIGEST tutorial
Notebook to recreate the results presented in the paper. Keep in mind, that the results can slighty differentiate as the random background will not create the exact same random sets as before.
# Setup
First, install the DIGEST package `biodigest` from pypi.
```
pip install biodigest
```
After installing `biodigest` it is important run the setup to generate all
needed files for the validation. You can do this directly in the jupyter
notebook or do it manually and skip the cell in the notebook.
```python
from biodigest import setup
setup.main(setup_type="api")
```
Make sure you also have `jupyter notebook` installed.
```
pip install juypter
```
# Start notebook
Now you have all requirements to run the notebook `Tutorial.ipynb`.
Inside you will find a step-by-step guide to recreate all results
from the paper.
```
jupyter notebook
```
