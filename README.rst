booleanp
========

Converts strings such as "true", "True", "y", "n", ... to their equivalent Boolean value.

Installation
------------

.. code::

  $ pip install boolean

Usage
-----

.. code::

  >>> from boolean import boolean
  >>> boolean('True')
  True
  >>> boolean('t')
  True
  >>> boolean('f')
  False
  >>> boolean('False')
  False

