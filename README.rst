SCEPy-ACMPCA
=====

**SCEPy-ACMPCA** is a pure python implementation of a SCEP CA that uses an AWS ACM Private CA as its backend.

Look, I'm going to be honest with you, you're a nice person, I'm a nice person. I'm going to do my gosh diddly darndest to make this thing work great...

for my usecase. Which is issuing SCEP certificates for network devices from an ACM PCA. Don't ask me why I would do such a thing. Why do any of us do anything? 

I am generally regarded as an okay developer. Sometimes, my code may bite you, and its not my fault. As long as we agree, lets roll.

Getting Started
---------------

**SCEPy-ACMPCA** is a Flask based web application which you can run like so::

    $ export FLASK_APP=scepy-acmpca
    $ export SCEPY_SETTINGS=/path/to/scepy-acmpca.cfg
    $ flask run --host=0.0.0.0

An example of some configuration is supplied in ``scepy-acmpca.cfg.example``

Blueprint
---------

**SCEPy** can also be run as a Flask Blueprint as part of your own application by importing ``scepy.blueprint``.

I deleted the mobile stuffs. If you're using this for MDM, buyer beware it'll probably suck.
