=========================
Install Django virtualenv
=========================

.. container::


Step 1: Install pip3
====================
::

    sudo apt-get install python3-pip

Step 2: Install virtualenv
==========================
::

    pip3 install virtualenv

Step 3: Create virtualenv python3
=================================
::

    virtualenv --python=`which python3` <DIR>

Step 4: Install django
=====================
::

    source <DIR>/bin/activate
    pip3 install Django


Step 5: Install mysqlclient
===========================
::

    sudo apt-get install libmysqlclient-dev
    pip3 install mysqlclient


Step 6: Install MysqlServer
===========================
::

    sudo apt-get install mysql-server

