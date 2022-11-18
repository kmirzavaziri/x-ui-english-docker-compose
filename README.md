# Usage

### Get Docker
```
curl -fsSL https://get.docker.com | sh
```

### Clone The Repo
```
git clone https://github.com/kmirzavaziri/x-ui-english-docker-compose.git x-ui
cd x-ui
```

### Docker Compose Up And Detach
```
sudo docker compose up -d
```

### Config
- Go to the `{YOUR_SERVER_IP_ADDRESS_OR_DOMAIN}:54321`
- Login using default username `admin` and password `admin`.
- Change your user pass combo from `panel settings > user settings`. (DO NOT SKIP THIS STEP)
- Add an inbound from `inbound list` with the following config.
  > port: ARBITRARY
  > transmission: ws
  > path: ARBITRARY
