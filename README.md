RS 103 - Supplemental Material
===============================

Jupyter Notebooks to support Planet Launch course RS 103: Remote Sensing
Programming with Python

Requirements
--------------

This repo is optimized for use within a PythonAnywhere environment. As such,
the following prerequisites are assumed to be installed and available at the
system level:

    - GDAL 2.3+
    - NumPy

Installation
-------------

Requires Python 3. To install Python dependencies _(for local
development, a virtualenv is strongly recommended)_:

    $ pip install -r requirements.txt

Running Locally
----------------

In PythonAnywhere, there's no need to run the Jupyter server directly. For
local development, however, it can be useful to run Jupyter from within the
project virtualenv.

To set up the kernel with virtualenv packages, run the following within the
virtualenv:

    (venv) $ python -m ipykernel install --user --name <venv name>
    

After that, start Jupyter:
    
    $ jupyter notebook

From within the Notebook interface, change the kernel (`Kernel --> Change
Kernel --> <name of venv>`) to use the newly created project kernel.
