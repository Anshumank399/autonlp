Installation
===================================

Installing AutoNLP is super-easy! Since we are moving quite fast with the development of this library, it's always wise to use the latest version from pypi.

To install, you can use `pip`:

.. code-block:: bash

    $ pip install -U autonlp


Please make sure that you have git lfs installed. Check out the instructions here: https://github.com/git-lfs/git-lfs/wiki/Installation

Usage behind an HTTP proxy
===================================

AutoNLP uses the `requests` Python package to make HTTP requests.

To use AutoNLP behind an HTTP proxy, simply set the `HTTP_PROXY` or `HTTPS_PROXY` environment variable in your shell.

.. code-block:: bash

    $ export HTTP_PROXY="http://proxy_ip:proxy_port"
