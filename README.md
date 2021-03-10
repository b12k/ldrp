# Local Developement Reverse Proxy

## Why:

Used to proxy `*.localhost` subdomain to respective ports.

## Ingridients:
- Docker
- Nginx

## Usage:
### Install:
```bash
> cd $YOUR_AWESOME_FOLDER
> git clone git@github.com:b12k/ldrp.git .
> docker-compose up -d
```
Open: [http://localhost](http://localhost)

### Configure:
Add your configuration to `nginx.conf` and
```bash
> docker-compose restart
```
