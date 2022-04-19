# ESPHome Projects

Usage:

```sh
pip install esphome --upgrade

# Configure
esphome new-config.yaml wizard

# Flash
esphome new-config.yaml run
```

## Tips

- Use dashes, not underscores, for names. Especially for anything involving DNS as some network firmware has trouble with underscores.
- `secrets.yaml` files are directory-unique, ensure the `/common/` directory has one
- ESP32-WROOM uploading: press the EN button when the compiler is waiting to begin the upload