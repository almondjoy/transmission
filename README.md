# transmission
Transmission Docker Image

Defaults are set in Dockerfile, can be overridden with environment variables.

Several files, particularly the user and environment file templates were taken from https://github.com/haugene/docker-transmission-openvpn.

This is still a WiP and requires further verification/cleanup.


Build:
$ docker build -t transmission .

Run:
$ docker run -it -v /sterge/torrents/:/data -p 9091:9091 transmission
##then ctrl-p + ctrl-q to detach
