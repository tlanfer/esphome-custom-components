# Esphome custom components

These are custom components for [esphome](https://esphome.io/).

## git_commit_sha text sensor
Provides a text sensor with the current git commit hash of the firmware at compile time.
```yaml
external_components:
  - source: github://tlanfer/esphome-custom-components

text_sensor:
  - platform: git_commit_sha
    name: "Git hash"
```