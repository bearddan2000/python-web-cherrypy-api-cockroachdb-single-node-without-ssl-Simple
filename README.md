# python-web-cherrypy-api-cockroachdb-single-node-without-ssl-Simple

## Description
Simple web app that serves an api
for a cherrypy project.

Uses sqlalchemy query a table `dog`.

## Tech stack
- python
  - cherrypy
  - sqlalchemy
- cockroachdb

## Docker stack
- python:latest
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- [Endpoint at](http://localhost/)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
