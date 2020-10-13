Example p2p video meeting based on [PeerJs](https://peerjs.com/)

## Notes

Your domain must be available over https

`docker-compose.yml` configured to use reverse proxy Traefik

## Prepare

1. Copy `.env.dist` to `.env` and change values to configure docker
2. Copy `/src/vars.js.dist` to `/src/vars.js` and change values to configure fronted
3. Run `docker-compose up -d`