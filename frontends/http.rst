HTTP
====

The HTTP Frontend provides a HTTP Api to interact with Rustic.

For Web Applications you can use the @rustic/http-client package to communicate with rustic.
It's a WASM package built from the same models as used in the http frontend.

Configuration
*************

.. code-block:: toml

  [frontends.http]
  ip = "0.0.0.0"
  port = 8080
  static_files = "static"

