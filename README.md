pynoter
=======
[![PyPI license](https://img.shields.io/pypi/l/pynoter.svg)](https://pypi.org/project/pynoter/)
[![PyPI version fury.io](https://badge.fury.io/py/pynoter.svg)](https://pypi.org/project/pynoter/)
[![PyPI pyversions](https://img.shields.io/pypi/pyversions/pynoter.svg)](https://pypi.org/project/pynoter/)
<!---[![Build Status](https://travis-ci.org/maxrousseau/pfla.svg?branch=master)](https://travis-ci.org/maxrousseau/pfla)--->

This app enables you to convert powerpoint presentations (.pptx) into
raw text latex (.tex) or org (.org) files for easy editing and
note-taking to produce nice documents.

Usage:

Simply enter the following commands in your terminal: 
```shell
$ py-noter -p pptx\_file -t new\_file\_name -ft org
```

or for a LaTeX document: 
```shell
$ py-noter -p pptx\_file -t new\_file\_name -ft latex
```

Features
--------

-   Create raw text org or Latex files from pptx presentations
-   Customize head, body and tail of document by changing JSON file

Dependencies
------------

-   python 2.7

Installation
------------
```shell
$ pip install pynoter
```
Contribute
----------

-   Issue Tracker: <https://github.com/maxrousseau/pynoter/issues>
-   Source Code: <https://github.com/maxrousseau/pynoter>

Todo
----

- [ ] Fix text spacing issue
- [x] Add markdown conversion
- [ ] Add text processing capabilities
- [ ] Add a progress bar

License
-------

The project is licensed under the MIT license.
