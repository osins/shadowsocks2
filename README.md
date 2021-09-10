# shadowsocks2
shadowsocks server and client

## .env config

./client/.env and ./server/.env

```
PASSWORD=your password
SERVER=your server ip
```

## server run

```
cd server
./restart.sh
```

## client run

```
cd client
./restart.sh
```

## setting your os

proxy address: 127.0.0.1:1080

or on linux

```
export http_proxy="127.0.0.1:1080"
export https_proxy="127.0.0.1:1080"
export ftp_proxy="127.0.0.1:1080"
```

