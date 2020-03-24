# Jupyter Server

[![Google Group](https://img.shields.io/badge/-Google%20Group-lightgrey.svg)](https://groups.google.com/forum/#!forum/jupyter)
[![Build Status](https://github.com/jupyter/jupyter_server/workflows/CI/badge.svg)](https://github.com/jupyter/jupyter_server/actions)
[![Documentation Status](https://readthedocs.org/projects/jupyter-server/badge/?version=latest)](http://jupyter-server.readthedocs.io/en/latest/?badge=latest)

The Jupyter Server provides the backend for Jupyter web applications like Jupyter notebook, JupyterLab, and Voila.

## Installation and Basic usage

You can find the installation documentation for the
[Jupyter platform, on ReadTheDocs](https://jupyter.readthedocs.io/en/latest/install.html).
The documentation for advanced usage of Jupyter notebook can be found
[here](https://jupyter-server.readthedocs.io/en/latest/).

To install the latest release locally, make sure you have
[pip installed](https://pip.readthedocs.io/en/stable/installing/) and run:

    $ pip install jupyter_server

Jupyter Server currently supports the following Python versions:

Platform | Python
--- | ---
Linux | >=3.5
OSX | >=3.5
Windows | >=3.7

### Versioning and Branches

If Jupyter Server is a dependency of your project/application, it is important that you pin it to a version that works for your application. Currently, Jupyter Server only has minor and patch versions. Different minor versions likely include API-changes while patch versions do not change API.

When a new minor version in released on PyPI, a branch for that version will be created in this repository, and the version of the master branch will be bumped to the next minor version number. That way, the master branch always reflects the latest un-released version.

To see the changes between releases, checkout the [CHANGELOG](https://github.com/jupyter/jupyter_server/blob/master/CHANGELOG.md).

To install the latest patch of a given version:

    $ pip install jupyter_server>=0.2

## Usage - Running Jupyter Server

### Running in a local installation

Launch with:

    $ jupyter server

## Contributing

If you are interested in contributing to the project, see [`CONTRIBUTING.rst`](CONTRIBUTING.rst).

## Weekly Dev Meeting

We have videoconference meetings every week where we discuss what we have been working on and get feedback from one another.

Anyone is welcome to attend, if they would like to discuss a topic or just to listen in.

When: Thursdays [8:00am, Pacific time](https://www.thetimezoneconverter.com/?t=8%3A00%20am&tz=San%20Francisco&)
Where: [calpoly/jupyter Zoom](https://zoom.us/my/jovyan)
What: [Meeting notes](https://github.com/jupyter/jupyter_server/issues/126)

## Resources

- [Project Jupyter website](https://jupyter.org)
- [Online Demo at try.jupyter.org](https://try.jupyter.org)
- [Documentation for Jupyter Server](https://jupyter-server.readthedocs.io/en/latest/) [[PDF](https://media.readthedocs.org/pdf/jupyter-server/latest/jupyter-server.pdf)]
- [Korean Version of Installation](https://github.com/ChungJooHo/Jupyter_Kor_doc/)
- [Documentation for Project Jupyter](https://jupyter.readthedocs.io/en/latest/index.html) [[PDF](https://media.readthedocs.org/pdf/jupyter/latest/jupyter.pdf)]
- [Issues](https://github.com/jupyter/jupyter-server/issues)
- [Technical support - Jupyter Google Group](https://groups.google.com/forum/#!forum/jupyter)
