# Dataiku DSS
---
  
## Pull latest version

```bash
sudo docker-compose pull
```

## Create your docker container
This will create the container based on an existing image

**WARNING**: Before running the following command, you need to stop all **VPN** connections to avoid **docker** errors. If you are usin g OpenVPN run ```sudo service openvpn stop```

```bash
sudo docker-compose up -d
```

## Run your docker container
After creation run

```bash
sudo docker-compose start
```

## Acces the webapp
Go to http://[SERVER_IP]:10000

