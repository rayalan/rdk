rdk
===

My personal cross-platform development kit, designed to keep multiple computers syncronized with the same development enviroment:

- Checks environment configurations
- Generates templates for my editors and syncs them
- Sets up other common programs

Usage
-----

    pip install -r requirements.txt
    ./rdk check  # Check alignment
    ./rdk sync  # Syncronization

Requirements
------------

- Python 2.7 or 3.6+.

Background
----------

Normally I'd prefer to use Ansible, but it doesn't have good Windows support for running locally.
