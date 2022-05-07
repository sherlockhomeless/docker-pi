Caddy is started via cronjob: https://caddy.community/t/help-getting-caddy-to-run-at-boot-solved/8314/4

Caddy is started via cronjob: https://caddy.community/t/help-getting-caddy-to-run-at-boot-solved/8314/4

1. `sudo crontab -e`
2. `@reboot caddy start --config /path/to/Caddyfile`
