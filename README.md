White Market Games  Version 1.0  07/31/2015

What is it?
-----------

Tournament Manager is a Python script that allow you to keep track of several 
tournaments. Uses a PostgreSQL database to store tournaments, 
players and matches using swiss pairings system. With Tournament 
Manager you can quickly know the pairs list for each tournament round.

Requirements
------------
To a full success use of Tournament Manager you need:

    o PostgreSQL
    o Python 2.7
    o psycopg2

Installation
------------
Setup and populate database:

    # Go to the project folder
    $ cd /vagrant/catalog
    
    # Setup database
    $ python db/setup.py
    
    # Populate database (optional)
    $ python db/populate.py
    
How to use
------------

You can start the application by running it in any Python IDE or directly from terminal using the command:

    # Go to the project folder
    $ cd /vagrant/catalog
    
    # Start application
    $ python app.py
    
If everything runs well you will get the message:

    * Running on http://0.0.0.0:5000/
    * Restarting with reloader

Licensing
---------

Please see the file LICENSE.

Contacts
--------

o If you want to be informed about new code releases, bug fixes,
security fixes, general news and information about the White Market Games project just keep tracking this repository.

o If you want freely available support for this script 
or any kind of help just mail <hugophp@sapo.pt>

