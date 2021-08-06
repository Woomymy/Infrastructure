# [Vaultwarden](https://github.com/dani-garcia/vaultwarden)

Unofficial [Bitwarden](https://bitwarden.com) compatible server written in Rust

## Configuration

```sh
SMTP_HOST=<SMTP_HOST> # Smtp host. Example: mail.example.com
SMTP_FROM=<USER@DOMAIN> # Example: bitwarden@woomy.ovh
SMTP_PORT=<SMTP_PORT> # Smtp port
SMTP_SSL=<SMTP_SSL_ENABLE> # If you need to use SSL with SMTP
SMTP_USERNAME=<SMTP_USER_NAME> # Example: uwu@woomy.ovh
DOMAIN=<PROTOCOL://DOMAIN> # Example: https://bitwarden.woomy.ovh
ADMIN_TOKEN=<BITWARDEN_ADMIN_PAGE_PASSWORD> # Bitwarden admin page password: **SUPER SENSIBLE**
SMTP_PASSWORD=<SMTP_USER_PASSWORD> # Example: password (yes, we love security)
```

