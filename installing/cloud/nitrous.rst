Nitrous.IO
===========

The following are installation instructions for the `Nitrous.IO <http://nitrous.io>`.

**Step 1:** Create a new application in boxes with NodeJS :

https://www.nitrous.io/app#/boxes/new

**Step 2:** Open terminal / SSH to the application / Open IDE

**Step 3:** Get the files of NodeBB, unzip, delete master.zip and cd to the folder

.. code:: bash

	wget https://github.com/NodeBB/NodeBB/archive/v1.x.x.zip && unzip NodeBB-v1.x.x.zip && rm NodeBB-v1.x.x.zip && cd NodeBB-v1.x.x

**Step 4:** NPM Install

.. code:: bash

  npm install

**Step 5:** Install Redis

.. code:: bash

  parts install redis

**Step 6:** Setup NodeBB

.. code:: bash

	./nodebb setup

Leave everything as default but you can change yourself.

I recommend the port number to bind : 8080

**Step 14:** And the last one, start NodeBB

.. code:: bash

	./nodebb start

And then open the "Preview URI" without port if you have put for port : 8080.

Note
---------------------------------------
You can expand the resources of the application : http://www.nitrous.io/app#/n2o/bonus.
