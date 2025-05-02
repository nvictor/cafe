FROM caddy:alpine

RUN addgroup -S caddyuser && adduser -S caddyuser -G caddyuser
RUN chown -R caddyuser:caddyuser /usr/share/caddy /etc/caddy /var/lib/caddy
USER caddyuser

COPY index.html /usr/share/caddy/index.html
COPY Caddyfile /etc/caddy/Caddyfile
