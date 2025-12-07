# NekoAWBox

docker run -d -p 443:443 -v proxy-config:/data --name mtproto_proxy -e SECRET=<openssl rand -hex16> telegrammessenger/proxy:latest
