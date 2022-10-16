# yaml-resume

## It's Forked!

This is a fork of the excellent [yaml-resume](https://badge.fury.io/py/yaml-resume) available on pypi.

![tests](https://github.com/notsag/yaml_resume/actions/workflows/build.yml/badge.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=notsag_yaml-resume&metric=alert_status)](https://sonarcloud.io/dashboard?id=notsag_yaml-resume)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Python 3.6+](https://img.shields.io/badge/python-3.6%7C3.7%7C3.8-blue.svg)](https://www.python.org/downloads/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/ambv/black)
=======

## Purpose

Building upon the open source initiative to create a YAML-based resume. I am adding some tweaks that I have found useful, and using this repository to demonstrate those separately from the main project. 


### Usage

Init a new resume through an interactive cli:

```
yaml-resume init FILENAME
```

Validate your yaml resume:

```
yaml-resume validate FILENAME
```

Export you resume in html or pdf:

```
yaml-resume export FILENAME [-t <theme>] [-e <html|pdf>] [-i <picture>] [-o <output-file>]
```

### TL;DR

You can ask for features/report bugs using Github issues.
You can submit work using Github Pull Requests.

To test development version without installing : 

```
# To install dependencies
python3 -m pip install -r requirements.txt
python3 -m pip install pytest pytest-cov black pre-commit

# To run the cli
python3 -m yaml_resume

# To run the test suite
python3 -m pytest --cov=yaml_resume tests/

# To install pre-commit hook
pre-commit install
```
