Code Generator for the XP Framework
========================================================================

This tool runs utilities that generate sourcecode from a given input
source.

Usage:

```sh
$ cgen [-O {output}] {generator} [-? | --help] [options]
```

Output options
--------------

* -O: Output is written to standard ouput (default if omitted)
* [name].xar: Output is written to a XAR archive
* [directory]: Output is written to the filesystem

Generators
----------

* dataset: Creates rdbms.DataSet class from a database
* wsdl: Creates web service client for a given WSDL uri or file
* esdl: Creates remote interfaces for EASC services
