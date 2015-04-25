# The argparse module is now part of the Python standard library! #

All new development on argparse will continue in the Python repository. Get Python 2.7 or 3.2 for the latest argparse updates!

Additionally, there is an effort to maintain an argparse package here:
  * it is based on the python 2.7 stdlib code, backported to older python versions
  * provides argparse for everybody who still needs to support python < 2.7
  * provides argparse >= 1.2 under Python license to fix license compatibility issues (e.g. Apache License 2.0 is considered incompatible to GPL v2)
  * fix other issues as they come up without forcing people to use python 2.7

## argparse: Python command line parser ##

The argparse module provides an easy, declarative interface for
creating command line tools, which knows how to:

  * parse the arguments and flags from sys.argv
  * convert arg strings into objects for your program
  * format and print informative help messages
  * and much more...

The argparse module improves on the standard library optparse module
in a number of ways including:

  * handling positional arguments
  * supporting sub-commands
  * allowing alternative option prefixes like + and /
  * handling zero-or-more and one-or-more style arguments
  * producing more informative usage messages
  * providing a much simpler interface for custom types and actions

See the [argparse documentation in the Python standard library](http://docs.python.org/library/argparse.html).