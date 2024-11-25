Welcome to Getting started with sphinx's documentation!
=======================================================

Introduction
------------
**Overview:** Sphinx is a tool that generates documentation for Python projects. It converts *reStructuredText* files into formats like HTML, PDF, and more.

**Install Sphinx**
::

   pip install sphinx

**Configure Sphinx**
::

   import os
   import sys
   sys.path.insert(0, os.path.abspath('./'))
   sys.path.insert(0, os.path.abspath('../'))
   extensions = ['sphinx.ext.autodoc']


Python Codes
------------
.. toctree::
   :maxdepth: 2
   :caption: Contents

   modules


Tables
------

1. Example with Grid table

+------------+-----------------+--------------------------+
| Parameter  | Type            | Description              |
+============+=================+==========================+
| radius     | float           | The radius of the circle |
+------------+-----------------+--------------------------+
| area       | float           | The area of the circle   |
+------------+-----------------+--------------------------+

2. Example Table with list-table

.. list-table:: Circle Properties
   :header-rows: 1

   * - Parameter
     - Type
     - Description
   * - radius
     - float
     - The radius of the circle
   * - area
     - float
     - The area of the circle


Figures
-------

.. image:: images/Log.png
  :width: 500
  :align: center



