## foocat2 

![](https://github.com/ttimbers/foocat2/workflows/build/badge.svg) [![codecov](https://codecov.io/gh/ttimbers/foocat/branch/master/graph/badge.svg)](https://codecov.io/gh/ttimbers/foocat2) ![Release](https://github.com/ttimbers/foocat2/workflows/Release/badge.svg)[![Documentation Status](https://readthedocs.org/projects/foocat2/badge/?version=latest)](https://foocat2.readthedocs.io/en/latest/?badge=latest)

Python package that eases the pain concatenating Pandas categoricals!

[Read the docs!](https://foocat2.readthedocs.io/en/latest/)

### Installation:

```
pip install -i https://test.pypi.org/simple/ foocat2
```

### Features
- TODO

### Dependencies

- pandas

### Usage
Example usage:
```
>>> import pandas as pd
>>> a = pd.Categorical(["character", "hits", "your", "eyeballs"])
>>> b = pd.Categorical(["but", "integer", "where it", "counts"])
>>> cat.catbind(a, b)
```

```
[character, hits, your, eyeballs, but, integer, where it, counts]
Categories (8, object): [but, character, counts, eyeballs, hits, integer, where it, your]
```
### Documentation
The official documentation is hosted on Read the Docs: <https://foocat2.readthedocs.io/en/latest/>

### Credits
This package was created with Cookiecutter and the UBC-MDS/cookiecutter-ubc-mds project template, modified from the [pyOpenSci/cookiecutter-pyopensci](https://github.com/pyOpenSci/cookiecutter-pyopensci) project template and the [audreyr/cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage).
