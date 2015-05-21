Salsa Express
=================================

Description
-----------

A very simple static file server. For development use only like angular.

Install dependencies (first time only):

    $ npm install

How to start:

    $ node server

Open [http://localhost:4567](http://localhost:4567)

If you need a different port:

    $ PORT=9999 node server

Open [http://localhost:9999](http://localhost:9999)

If you need a different hostname:

    $ HOSTNAME=192.168.0.1 node server

Open [http://192.168.0.1:4567](http://192.168.0.1:4567)

CLI based generic server:
----------

Install as a global module

    $ sudo npm install -g radjivC/salsa-express

Serve a directory

    $ salsa-express my/public/dir
