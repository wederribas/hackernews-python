# GraphQL API for a HackerNews Clone

[![Build Status](https://travis-ci.org/wederribas/hackernews-python.svg?branch=master)](https://travis-ci.org/wederribas/hackernews-python)
[![GitHub issues](https://img.shields.io/github/issues/wederribas/hackernews-python.svg)](https://github.com/wederribas/hackernews-python/issues)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![GitHub stars](https://img.shields.io/github/stars/wederribas/hackernews-python.svg)](https://github.com/wederribas/hackernews-python/stargazers)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/wederribas/hackernews-python/master/LICENSE)

This project was built as part of the [How to GraphQL tutorial series](https://www.howtographql.com).

It consists in a GraphQL API to serve a clone of the [Hacker News](https://news.ycombinator.com/) website.

## Built With

- [Python 3](https://www.python.org/downloads/release/python-365/)
- [Django](https://www.djangoproject.com/)
- [GraphQL](https://graphql.org/)
- [Graphene](http://graphene-python.org/)
- [Graphene-Django](http://docs.graphene-python.org/projects/django/en/latest/)

## Installation and Execution

To get this API up and running, follow the steps below to run this project:

```
# Create a root folder
$ mkdir hackernews
$ cd hackernews

# Create a virtual environment with Python 3.6
# The `env` folder name is optional - choose whatever you want
$ python3.6 -m venv env

# Install the project packages
$ pip install -r requirements.txt

# Clone the project
$ git clone https://github.com/wederribas/hackernews-python.git
$ cd hackernews-python

# Perform the migrations
$ python manage.py migrate

# Start the app
$ python manage.py
```

## Authors

- Weder Ribas - [@wederribas](https://twitter.com/wederribas)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
