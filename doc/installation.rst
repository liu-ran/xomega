.. _installation-label:

Installation
============

The quickest way
----------------

xomega is compatible both with Python 2 and 3. The major dependencies are xarray_ and dask_.
The best way to install them is using Anaconda_.::

    $ conda install xomega dask .

Install xomega from GitHub repo
-------------------------------
To get the latest version::

    $ git clone https://github.com/roxyboy/xomega.git
    $ cd xomega
    $ python setup.py install .

Developers can track source code changes by::

    $ git clone https://github.com/roxyboy/xomega.git
    $ cd xomega
    $ python setup.py build .

.. _xarray: http://xarray.pydata.org
.. _dask: http://dask.pydata.org/en/latest/
.. _Anaconda: https://www.continuum.io/downloads