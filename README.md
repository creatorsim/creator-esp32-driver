# CREATOR ESP-32 Gateway
CREATOR gateway for [Espressif ESP32](https://www.espressif.com/en/products/socs/esp32).

[Documentation](https://creatorsim.github.io/creator-wiki/web/gateway.html#executing-the-esp32-gateway).


## Development
This project uses [uv](https://docs.astral.sh/uv) to manage dependencies.

To add a new dependency, use `uv add <dep>`.

To generate the `requirements.txt` file:
```
uv export --format=requirements-txt --no-hashes
```
