# PyDiscord

A simple Discord API that uses the new interactions framework. 

## Installing

Python 3.9 or higher is required. It may work on earlier versions; but they are untested.

To install the library:

``` 
# Linux/macOS
python3 -m pip install -U py-discord

# Windows
py -3 -m pip install -U py-discord
```

Note the hyphen in the package name.


## Versioning Policy

PyDiscord may work on earlier versions of Python, but is currently developed with Python 3.9. 

The project uses semantic versioning - MAJOR.MINOR.PATCH-prerelease. 

Compatibility will be maintained with Python versions on major versions - for example, all 1.x.y versions will 
support Python 3.9, and only considered for being dropped at 2.x.y. Discord may change their API from time to time, forcing breaking updates. These are outside the project's control.