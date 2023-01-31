## install the ufw firewall and setup a few rules on web-01

### Requirements:
- Configure ufw so that it blocks all incoming traffic, except the following TCP ports:

- - 22 (SSH)

- - 443 (HTTPS SSL)

- - 80 (HTTP)

### Configure web-01 so that its firewall redirects port 8080/TCP to port 80/TCP.
