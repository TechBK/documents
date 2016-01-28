===============
Install Pycharm
===============

.. contents::

Step 1: Install Java
====================
::

    sudo apt-get purge openjdk*
    sudo add-apt-repository ppa:webupd8team/java
    sudo apt-get update
    sudo apt-get install oracle-java8-installer

Check java version:
::

    javac -version

Step 2: Install Pycharm
=======================

- Download from www.jetbrains.com/pycharm/download/#section=linux

- Copy the pycharm-5.0.3.tar.gz to the desired installation location(make sure you have rw permissions for that directory)

- Unpack the pycharm-5.0.3.tar.gz using the following command:
::

    tar xfz pycharm-5.0.3.tar.gz

- Remove the pycharm-5.0.3.tar.gz to save disk space (optional)
- Run pycharm.sh from the bin subdirectory


Practice: How to install a specific package version?
====================================================

::

    sudo apt-get install package=version

