.. _installation-label:

Installation
============

The quickest way
----------------

xrft is compatible both with Python 2 and 3. The major dependencies are xarray_ and dask_.
The best way to install them is using Anaconda_.::

    $ conda install xarray dask .

Install xrft from GitHub repo
------------------------------

    $ git clone https://github.com/rabernat/xrft.git
    $ cd xrft
    $ python setup.py install .

Developers can track source code change::

    $ git clone https://github.com/rabernat/xrft.git
    $ cd xrft
    $ python setup.py build .

.. _xarray: http://xarray.pydata.org
.. _dask: http://dask.pydata.org/en/latest/
.. _Anaconda: https://www.continuum.io/downloads