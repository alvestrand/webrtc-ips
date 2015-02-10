# STUN IP Address requests for WebRTC

Based on: https://diafygi.github.io/webrtc-ips/

### What this does

This demo shows something about IP addresses available through WebRTC.

Some of these are learned from STUN servers, some are learned locally.

Some are already known to a Web server serving the page, some are not.

### Running the demo

The demo includes a lighttpd config file that will allow you to run
the demo locally.

To run lighttpd:

  lighttpd -D -f lighttpd.conf

To access the demo:

  <a href="localhost:3100">localhost:3100</a>

For variations, try <yourhostname>:3100.
