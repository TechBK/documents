===========================
Install React-Redux Project
===========================

.. contents::


Step0: Settup NPM
=================

Make a directory for global installations:
::

    mkdir ~/.npm-global

Configure npm to use the new directory path:
::

    npm config set prefix '~/.npm-global'

Open or create a ~/.profile file and add this line:
::

    export PATH=~/.npm-global/bin:$PATH

Back on the command line, update your system variables:
::

    source ~/.profile

Step1: Clone Project
====================
::

    git clone https://github.com/gaearon/react-hot-boilerplate.git

    npm install

Step2: Add package
==================
::

    npm install --save redux react-redux react-router react-router-redux reselect redux-thunk \
    babel-polyfill isomorphic-fetch redux-logger react-dom lodash normalizr \
     humps

