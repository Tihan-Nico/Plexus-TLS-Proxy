# Plexus TLS Proxy

To run a Plexus TLS proxy, you will need a host with a domain name that has ports 80 and 443 available.

1. Install docker and docker-compose (`apt update && apt install docker docker-compose`)
1. Ensure your current user has access to docker (`adduser $USER docker`)
1. Clone this repository
1. `./init-certificate.sh`
1. `docker-compose up --detach`

Your proxy is now running! You can share this with the URL `https://proxy.plexus.dev/#<your_host_name>`
