# SlamData Community Edition Docker Image

Builds a Docker image for the [SlamData](http://slamdata.com)  NOSQL analytics Tool (Community Edition). 

There are three environment variables that can be used to configure the image.

__PORT__
The TCP port that the SlamData server is available on. Defaults to _8080_

__CONNECTION_NAME__
The name of the preconfigured SlamData MongoDB connection. Defaults to _MongoDB_

__CONNECTION_URI__
The MongoDB connection string to be used for the initial connection. Defaults to _mongodb://mongodb:27017_

This is not an official image.

# Supported tags

* `latest`, `3.0` The most recent version of SlamData Community Edition v3.0
* `3.0.x` Specific versions of SlamData Community Edition v3.0