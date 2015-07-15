# Docker Experimental

This charm provides the
[experimental](https://github.com/docker/docker/tree/master/experimental)
version of [Docker](http://docker.io).  
The experimental version contains all the latest features of docker and allows
you to try the latest features.  Experimental features are not ready for
production. They are provided for test and evaluation purposes only.

# Usage

Fork this repository or download the charm to your local system.

Then deploy the charm from your system:

    juju deploy local:trusty/docker-exp


## Scale out Usage

Scaling out the docker service is as simple as adding additional docker units
to expand your cluster.

    juju add-unit docker-exp

## Known Limitations and Issues

This is an experimental version of Docker and should not be used in production.
This charm code is also beta, I would not recommend using it other than to
figure out how to write charms.

# Configuration

There are no configuration options at this time

# Contact Information

Author: Matt Bruzek &lt;[mbruzek@gmail.com](mailto:mbruzek@gmail.com)&gt;

## Upstream Project Name

- [Docker website](http://docker.io)
- [Docker experimental](https://github.com/docker/docker/tree/master/experimental)
- [Docker bug tracker](http://github.com/docker/docker/issues)
- [Docker users mailing list](https://groups.google.com/forum/?fromgroups#!forum/docker-users)
- [Docker dev mailing list](https://groups.google.com/forum/?fromgroups#!forum/docker-dev)
