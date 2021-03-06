# pycounts_jlc207
[![PyPI version](https://badge.fury.io/py/pycounts-jlc207.svg)](https://badge.fury.io/py/pycounts-jlc207)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/pycounts-jlc207)
[![Documentation Status](https://readthedocs.org/projects/pycounts-jlc207/badge/?version=latest)](https://pycounts-jlc207.readthedocs.io/en/latest/?badge=latest)

Calculate word counts in a text file!

## Installation

```bash
$ pip install pycounts_jlc207
```

## Usage
`pycounts_jlc207` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_jlc207.pycounts import count_words
from pycounts_jlc207.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_jlc207` was created by Vera Cui. It is licensed under the terms of the MIT license.

## Credits

`pycounts_jlc207` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
