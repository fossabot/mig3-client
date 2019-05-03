# mig3-client
Submit your results to Mig3 service.

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/8fbaac0868ee4261915b7c48ba8ee881)](https://app.codacy.com/app/mverteuil/mig3?utm_source=github.com&utm_medium=referral&utm_content=mverteuil/mig3-client&utm_campaign=Badge_Grade_Dashboard)
[![Build Status](https://travis-ci.com/mverteuil/mig3-client.svg?branch=master)](https://travis-ci.com/mverteuil/mig3-client)
[![PyPI version](https://badge.fury.io/py/mig3-client.svg)](https://badge.fury.io/py/mig3-client)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)


## Basic setup

Install it:
```
$ pip install mig3-client
```

Run the application:
```
$ mig3 --help
```

## Developer setup

Install dependencies:
```
$ poetry install
```

To run the tests for the current environment:
```
$ poetry shell
$ py.test
```

To run the tests for all environments:
```
$ tox
```
