.. code-block:: bash

         _       _ _            
      __| |____ | (_)____   ___ 
     / _  |  _ \| | |  _ \ / _ \
    | (_| | |_) | | | | | |  __/
     \____|  __/|_|_|_| |_|\___|
          |_|                   
     ___________________________ 
     ___________________________

About
-----

CLI tool to remove duplicate lines from text file.


Installation
------------

.. code-block:: bash

    $ tar xvf dpline-<version>.tar.gz
    $ cd dpline-<version>
    $ python setup.py install


    or via pip:

    $ pip install dpline --upgrade

    uninstall:

    $ pip uninstall dpline


Command Line Tool Usage
-----------------------

.. code-block:: bash

    Usage: dpline [OPTION] <file> [--ignore-blank, [--case-ins],
                                   --number]]

    dpline is tool to remove duplicate lines from file

    Optional arguments:
      -h, --help          Print this help message and exit
      -v, --version       Print program version and exit
      -d, --display       Display removed lines
      -p, --preview       Preview duplicate lines before removal
      --ignore-blank      Ignore blank lines from remove
      --case-ins          Matching upper- and lowercase letters
      --number            View duplicate line number
