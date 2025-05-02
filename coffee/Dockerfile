FROM caddy:alpine

COPY index.html /usr/share/caddy/index.html
COPY Caddyfile /etc/caddy/Caddyfile

RUN addgroup -g 1001 caddygroup && adduser -u 1001 -G caddygroup -S caddyuser
USER 1001
