.. blockchain-api-docs documentation master file, created by
   sphinx-quickstart on Mon Oct 21 17:14:42 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

REST API
=======================================================
The REST API allows you to query block info.

Base URL
-----------
All REST APIs in the documentation have the following base URL:

    http(s)://host:8080/api/

Basic Authentication
------------------------
The HTTP requests to the REST API are protected with HTTP Basic authentication. You can create an application in Dashboard, using appid and appsecret to authenticate.  For example:

.. code-block:: bash

    curl -v --basic -u <appsecret> -k http://localhost:8080/api/v3/brokers

+---------+---------------------------------------------------+
|GitHub:  |https://github.com/nerodocs/blockchain-api-docs.git|
+---------+---------------------------------------------------+
|Contact: | contact <zhangnero@163.com>                       |
+---------+---------------------------------------------------+


.. toctree::
   :maxdepth: 2

   zcash
   rippled
   test

License
-------

Apache License Version 2.0