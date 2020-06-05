Google Play Music
=================

Provides integration with Google Play Music.

Authentication works via OAuth.
When you're logged in you need to select a device id. To be able to do this you need to run Google Play Music at least once on a phone.

Configuration
*************

.. code-block:: toml

  [provider.gmusic]
  client_id = "<client_id>"
  client_secret = "<client_secret>"
  device_id = "<device_id>"
