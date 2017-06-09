## 0.9.5 (2017-06-09):
* split the CLI into a separate `xenstore-tool` opam package
* build with jbuilder
* release with topkg
* remove dependency on camlp4
* search for the xenbus path in Unix client
* add tests

## 0.9.4 (2014-06-16):
* use the xenbus device if the Unix domain socket isn't available
* respect the XENSTORED_PATH environment variable

## 0.9.3 (2014-05-09):
* fix a file descriptor leak when we cannot connect to xenstore

## 0.9.2 (2013-08-27):
* adapt to new xenstore signature which makes it easy to write code
  oblivious to whether it's running in Unix userspace or xen

## 0.9.1 (2013-08-06):
* update to xenstore 1.2.3

## 0.9.0 (2013-06-03):
* first public release

