
# Caddy test.

Commands to run:


curl -i local.phpimagick.com:8000
curl -i local.phpimagick.com:8001
curl -i local.phpimagick.com:8002
docker exec -it caddytest-caddy_1-1 curl -i local.phpimagick.com
docker exec -it caddytest-caddy_1-1 curl -i local.phpimagick.com:443
