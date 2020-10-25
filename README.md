# homeserver
Configs for my homeserver

## Steps  
- Use a `.env` file to store the secrets/configs needed by `docker-compose.yml`
- `docker-compose up -d --remove-orphans`  
- `^r[0-9]*([-]{1,3}|.)sn-[a-z0-9]{4,}-[a-z0-9]{4,}\.googlevideo` regex to block most yt ads via pihole  
