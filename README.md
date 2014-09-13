Foxx-manager with ArangoDB
==========================

Install [Docker](https://docs.docker.com/installation/#installation) and [Fig](http://www.fig.sh/):

    $ sudo pip install -U fig

On commandline:

    $ fig run foxxmanager bash
    # foxx-manager --server.endpoint $ARANGODB_1_PORT update
    # foxx-manager --server.endpoint $ARANGODB_1_PORT search
    # foxx-manager --server.endpoint $ARANGODB_1_PORT install hello-foxx /hello

In browser:

  Visit `http://localhost:8529/_db/_system/_admin/aardvark/standalone.html#applications`
  and `http://localhost:8529/hello`
