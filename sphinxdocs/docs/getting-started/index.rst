Getting started
====================================================

By `Karol Kaczmarek`_

Here's how to get started

Table of topics:
	- `Topic1`_
	- `Topic2`_
	- `Topic3`_
	
`View or download sample from GitHub <https://github.com>`_.

Topic1
------------------------------

Description for first topic

.. code-block:: javascript

    "test1": {
        "test1": { }
    },

Topic2
------------------------------

.. _Bootstrap: http://getbootstrap.com/

Description for second topic

.. code-block:: javascript

    "test2": {
        "foo1":{}
        "foo2":{}
        "foo3":{}
    },

Topic3
------------------------------

Description for third topic

.. code-block:: javascript

    var http = require('http');
    
    http.createServer(function (req, res) {
      res.writeHead(200, {'Content-Type': 'text/plain'});
      res.end('Hello World\n');
    }).listen(1337, '127.0.0.1');
    
    console.log('Server running at http://127.0.0.1:1337/');
