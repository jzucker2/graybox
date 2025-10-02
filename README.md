# graybox

I want this public so I can use it in the ESPHome docker app.

## Secrets.yaml

You should make your own `secrets.yaml` at `graybox/secrets.yaml` like the following:

```yaml
wifi_ssid: Example
wifi_password: password

encryption_key: "hWp0LB2P6d99/ehh0ZoSIzwKQu7BmTYbSeQ4teZUa20="
ota_password: "graybox"

ota_url: "http://gupdater:2001/update"
```

Base 64 encode and upload to GitHub repo as `ESPHOME_SECRETS_YAML`

To base64 encode:

```
pbpaste | base64
```
