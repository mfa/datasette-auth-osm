# datasette-auth-osm

[![PyPI](https://img.shields.io/pypi/v/datasette-auth-osm.svg)](https://pypi.org/project/datasette-auth-osm/)
[![Changelog](https://img.shields.io/github/v/release/mfa/datasette-auth-osm?include_prereleases&label=changelog)](https://github.com/mfa/datasette-auth-osm/releases)
[![Tests](https://github.com/mfa/datasette-auth-osm/workflows/Test/badge.svg)](https://github.com/mfa/datasette-auth-osm/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/mfa/datasette-auth-osm/blob/main/LICENSE)

Datasette plugin that authenticates users against Openstreetmap

## Installation

Install this plugin in the same environment as Datasette.

    datasette install datasette-auth-osm

## Usage

Usage instructions go here.

## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:

    cd datasette-auth-osm
    python3 -m venv venv
    source venv/bin/activate

Now install the dependencies and test dependencies:

    pip install -e '.[test]'

To run the tests:

    pytest
