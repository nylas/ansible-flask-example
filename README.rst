Example Ansible Automation for flask app
========================================

This repository is an example that shows how to use ansible-test. In addition, it is written in the style of using wrapper roles. For more information, see our blog post at: LINK HERE

Getting Started
---------------

To get started testing with this repository, run:

.. code-block:: bash

   $ virtualenv venv
   $ source venv/bin/activate
   $ pip install -r requirements.txt


Testing
-------

To test locally with ansible-test, you must have docker installed locally. If you are on Mac OSX, I reccomend you use boot2docker to setup docker.

.. code-block:: bash

   $ ansible-test app

The above command will test the app role in a docker container. Once the automation is done, it will drop you into a shell on the container so you can inspect the resulting configuration.
