# bw_edgarsergues_01

[![PyPI](https://img.shields.io/pypi/v/bw_edgarsergues_01.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/bw_edgarsergues_01.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/bw_edgarsergues_01)][pypi status]
[![License](https://img.shields.io/pypi/l/bw_edgarsergues_01)][license]

[![Read the documentation at https://bw_edgarsergues_01.readthedocs.io/](https://img.shields.io/readthedocs/bw_edgarsergues_01/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/edgarsergues/bw_edgarsergues_01/actions/workflows/python-test.yml/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/edgarsergues/bw_edgarsergues_01/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/bw_edgarsergues_01/
[read the docs]: https://bw_edgarsergues_01.readthedocs.io/
[tests]: https://github.com/edgarsergues/bw_edgarsergues_01/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/edgarsergues/bw_edgarsergues_01
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

## Installation

You can install _bw_edgarsergues_01_ via [pip] from [PyPI]:

```console
$ pip install bw_edgarsergues_01
```

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide][Contributor Guide].

## License

Distributed under the terms of the [Apache 2.0 license][License],
_bw_edgarsergues_01_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue][Issue Tracker] along with a detailed description.


<!-- github-only -->

[command-line reference]: https://bw_edgarsergues_01.readthedocs.io/en/latest/usage.html
[License]: https://github.com/edgarsergues/bw_edgarsergues_01/blob/main/LICENSE
[Contributor Guide]: https://github.com/edgarsergues/bw_edgarsergues_01/blob/main/CONTRIBUTING.md
[Issue Tracker]: https://github.com/edgarsergues/bw_edgarsergues_01/issues


## Building the Documentation

You can build the documentation locally by installing the documentation Conda environment:

```bash
conda env create -f docs/environment.yml
```

activating the environment

```bash
conda activate sphinx_bw_edgarsergues_01
```

and [running the build command](https://www.sphinx-doc.org/en/master/man/sphinx-build.html#sphinx-build):

```bash
sphinx-build docs _build/html --builder=singlehtml --jobs=auto --write-all; open _build/html/index.html
```