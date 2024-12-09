# Esphome custom components

These are custom components for [esphome](https://esphome.io/).

## Git text sensor

```yaml
external_components:
  - source: github://tlanfer/esphome-custom-components

text_sensor:
  - platform: git_commit_sha
    name: "Git hash"
```