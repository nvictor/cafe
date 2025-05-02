FROM caddy:alpine

COPY index.html /usr/share/caddy/index.html
COPY Caddyfile /etc/caddy/Caddyfile

RUN addgroup -S caddyuser && adduser -S caddyuser -G caddyuser
USER caddyuser
