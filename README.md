# Example Package
This is a simple example package. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.

# Setup
```{bash}
$ git clone 
```

To install the package locally:

```bash
$ make install
```

To build the wheels and source distributions files:

```bash
$ make build
```

To upload the builded package to PyPI:

```bash
$ make upload
```

In order to build and upload sequentially, you should just:

```bash
$ make pypi
```

# Usage
```python
from example_package_joaopcnogueira import example

example.add_one(10)
```

# Package Structure

`example_package_joaopcnogueira`


# References
[Packaging Python Projects from PyPA - Python Project Authority](https://packaging.python.org/en/latest/tutorials/packaging-projects/)
