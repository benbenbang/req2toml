.. req2toml documentation master file, created by
   sphinx-quickstart on Sat Dec 26 12:45:16 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to req2toml's documentation!
====================================

    CLI Endpoint: To convert requirements file to pyproject.toml & poetry lock

    Example:

        The entrypoint of the converter is `req2lock`

        ## Options
            - `-f` [required]  The  path to the `requirements.txt`
            - `--install` [optional] By default, it will only update the lock, add this flag to install the dependencies at the same time.
            - `--dev` [optional] By default, the flag is disable, pass `--dev` to add packages to dev section.
            - `-v`: Enable verbose mode to print out the debug logs

        .. code-block:: shell

           # Only update the poetry.lock
           $ req2lock -f requirements.txt

           # Install
           $ req2lock -f requirements.txt --install

           # To dev
           $ req2lock -f requirements_test.txt --install --dev

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
