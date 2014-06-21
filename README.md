[![Build
Status](https://travis-ci.org/secure-pipeline/node-travis-example.svg?branch=master)](https://travis-ci.org/secure-pipeline/node-travis-example)

An example of testing a node web application using various security
testing tools.

This project tests the vulnerable
[NodeGoat](https://github.com/OWASP/NodeGoat) application with:

* [Zapr](https://github.com/garethr/zapr)
* [Gauntlt](http://gauntlt.org)

Note that the test suite runs on [Travis](https://travis-ci.org) and is
failing because the application under test actually has various
cross-site-scripting vulnerabilities.
