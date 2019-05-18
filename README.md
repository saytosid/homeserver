# homeserver
Configs for my homeserver

#### Lets Encrypt setup on the host
`certbot certonly --standalone -d your.server.url`  
`crontab -e`  
`@daily certbot renew --pre-hook "docker-compose -f path/to/docker-compose.yml down" --post-hook "docker-compose -f path/to/docker-compose.yml up -d"`  

