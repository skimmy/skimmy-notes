# Python

* [CPython](#cpython)
* [`http` module](#http-module)


## CPython

[CPython](https://github.com/python/cpython) is, essentially, the official Python release (the one you get from [python.org](https://www.python.org/).
* In [PEP11](https://peps.python.org/pep-0011/) there is a list of supported platforms (divided in tiers 1, 2, and 3), also mentioned by [Brett Cannon](https://snarky.ca/) in [Episode 154 of Real Python Podcast](https://realpython.com/podcasts/rpp/154/).

## `http` Module
It is possible to run a simple HTTP server serving from the current directory by executing
```shell
python -m http.server
```
This is possible because the `http.server` module has the code in the `if __name__ == "__main__"`
