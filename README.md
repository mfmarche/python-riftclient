# python-riftclient
A python client for rift orchestration

# Installation

## Install dependencies
    sudo apt-get install pycurl python-dev libcurl4-gnutls-dev

## Install python-riftclient
    sudo pip install git+https://github.com/mfmarche/python-riftclient

# Setup
Set the RWCLIENT_RIFT_HOSTNAME variable to the host of the rift server.

Example
    export RWCLIENT_RIFT_HOSTNAME=<hostname>:8888


## Bash Completion
python-riftclient uses [click](http://click.pocoo.org/5/).  You can setup bash completion by putting this in your .bashrc:
    
    eval "$(_RWCLIENT_COMPLETE=source rwclient)"

