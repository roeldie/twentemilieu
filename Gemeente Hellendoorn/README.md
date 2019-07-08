# Gemeente Hellendoorn

based on https://github.com/yniezink/twentemilieu

Gemeente Hellendoorn garbage collection sensor for Home Assistant


configuration.yaml

```
sensor:
  - platform: hellendoorn
    postcode: 
    huisnummer: 
    toevoeging: 
    resources:
      - GREEN
      - PACKAGES
      - PAPER
      - GREY
