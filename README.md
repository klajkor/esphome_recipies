# ESPHome Recipies

## How to compile
- Config validation: `esphome config btbridge.yaml`
- Compile: `esphome compile btbridge.yaml`
- Upload via USB serial port: `esphome upload btbridge.yaml --device /dev/ttyUSB0`
- Upload via web OTA: `esphome upload btbridge.yaml --device 10.10.10.37`
- Config validation, compile and upload via web OTA: `esphome run btbridge.yaml --device 10.10.10.37`

## ESPHome manual
- [ESPHome CLI guides](https://esphome.io/guides/cli)
