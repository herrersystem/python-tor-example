#python-tor-exemple

### Example of use Tor with Python 3 on Ubuntu###

Installation required:

* stem: sudo apt-get install python3-stem
* socks: pip3 install PySocks
* tor: sudo apt-get install tor

Configuration:

Create password for tor controller:

* tor --hash-password my_password

Add hash password an add controller port in /etc/tor/torrc :

ControlPort 9051
HashedControlPassword 16:7F74432B0864F0E06004A63636E07F7A1EF8C97ABC5907A7FE9107743D

### Python example ###

In this example, I use requests module for HTTP connection.

 




