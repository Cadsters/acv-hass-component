# Garbage collection sensor for Acv-groep for Home Assistant

Add the following to your configuration.yaml:

```yaml
sensor:
  - platform: acv
    postcode: 6718WV 
    housenumber: 4
    resources:
      - today
      - tomorrow
      - grey
      - green
      - paper
      - packages
      - textile
```
Change the postcode and house number to whats applicable to yours.

It will create sensors for the next few future calendar events, called:

* sensor.afval_rest
* sensor.afval_gft
* sensor.afval_papier
* sensor.afval_pmd
* sensor.afval_textiel
* sensor.afval_vandaag
* sensor.afval_morgen
