==========
httpstatus
==========

This project using Scala and SBT, conscript.

:Original: http://blog.64p.org/entry/2013/02/21/121830 

Try this
========

setup conscript_

.. _conscript: https://github.com/n8han/conscript

::

  $ cs masahitojp/httpstatus

Use
===

::

  $ httpstatus 4
  Status 400: Bad Request
  ...
  Status 449: Retry with

  $ httpstatus Bad
  Status 400: Bad Request
  Status 502: Bad Gateway

License
=======

Licensed under the Apache License, Version 2.0.

http://www.apache.org/licenses/
