![dogedcoindark-python](http://i.imgur.com/2iVVp2a.png)

#dogecoindark-python 

a fork of dogecoin-python by jcsaaddupuy: https://github.com/jcsaaddupuy/dogecoin-python

It is a set of Python libraries that allows easy access to the
dogecoindark peer-to-peer cryptocurrency client API.


Documentation
===========================

The documentation for bitcoin-python can be found here (or built from sources) :

http://jcsaaddupuy.github.io/dogecoin-python/doc/index.html


Installation instructions
===========================

dogecoindark-python uses setuptools for the install script. There are no dependencies apart from Python itself.

::

  $ python setup.py build
  $ python setup.py install
  

Pypi / Cheeseshop
==================

It is possible to install the package through Pypi (cheeseshop), see http://pypi.python.org/pypi?:action=display&name=dogecoin-python
::
 $ pip install dogecoindark-python
 # if not working, try
 $ pip install --pre dogecoindark-python

Connection to dogecoindark-qt
=========================

If you want to connect to dogecoin-qt, add server=1 in your dogecoin.conf
::

 rpcuser=dogecoindarkrpc
 rpcpassword=A RANDOM GENERATED PASSWORD
 server=1

TODO
======
These things still have to be added:

- SSL support (including certificate verification) for managing remote dogecoindark daemons.

