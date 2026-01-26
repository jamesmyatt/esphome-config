# LoctekMotion

Standing desks using [iMicknl/LoctekMotion_IoT][1] component.

- Flexispot E7

[1]: https://github.com/iMicknl/LoctekMotion_IoT

## Example

```yml
packages:
 - url: https://github.com/jamesmyatt/esphome-config
   files:
    - path: packages/loctekmotion/flexispot.yaml
      vars:
       tx_pin: GPIO21
       rx_pin: GPIO20
       screen_pin: GPIO10
       min_height: "58.1" # Min height + 0.1
       max_height: "122.9" # Max height - 0.1
   ref: main
```
