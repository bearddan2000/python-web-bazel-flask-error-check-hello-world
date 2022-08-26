# python-web-bazel-flask-error-check-hello-world

## Description
Creates a simple web-bazel response for a flask project.
If path is not found, will default to 404 error.

## Tech stack
- bazel
- python
- flask

## Docker stack
- l.gcr.io/google/bazel:latest

## To run
`sudo ./install.sh -u`
- Good path: http://localhost
- Bad path: http://localhost/bad

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
