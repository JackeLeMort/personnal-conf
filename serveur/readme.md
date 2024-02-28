# My server

My server, configured my myself over the few pas month, I use it to store and watch media, to store pictures and videos files and to backup everything i can, I plan to add webservice in the future.

It is currently accessible on my home network or via tailscale for remote access.

Almost everything runs as dockers with docker composem, except for tailscale (the instalation is really straightforward), i currently can't but I plan to try [mistborn](https://gitlab.com/cyber5k/mistborn) when I'll have a real wired internet access.
(you can use the .yml yourself, just put it in ~/docker on your server and change to the correct timezone for all services in the docker-compose.yml)

Spec:
- dell optiplex 3050 with i3 7th gen
- 5 bay DAS with
 - 2 * 6TB HDD
 - 2 * 8TBHD
 
I plan to do a raid 5 or 6 as soon as possible
