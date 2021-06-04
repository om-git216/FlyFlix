# FlyFlix

This repository is a supplement to our preprint [An inexpensive, high-precision, modular spherical treadmill setup optimized for *Drosophila* experiments](https://doi.org/10.1101/2021.04.29.442008).

## Usage

### Installation

To run the FlyFlix server, a recent version of [python](https://www.python.org/) is required. The server was written in Python-3 and only tested in [Python-3.7](https://devguide.python.org/#status-of-python-branches) and newer. The [installation of a recent python interpreter](https://wiki.python.org/moin/BeginnersGuide/Download) or another type of [python distribution](https://www.anaconda.com/products/individual) is outside the scope of this documentation.

To install dependencies, a python package management system compatible with [pip](https://pip.pypa.io/en/stable/) is required. Using a [virtual environment](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment) is encouraged although optional and once again outside the scope of this documentation.

## Architecture

FlyFlix is a web application that runs in most modern web browsers. While the server component is written in python-3 and requires a computer to run, the client is implemented in JavaScript inside an HTML website. Browsers that access the server receive the client code as part of the website. Through a bidirectional communication server and client exchange status information. Consequently, several clients can connect to the same server.

### Server

### Client