[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)
[![Github all releases](https://img.shields.io/github/downloads/Naereen/StrapDown.js/total.svg)](https://GitHub.com/Naereen/StrapDown.js/releases/)
# Home Assistant acv-groep component
Integration for bin/waste collection  by acv-groep.

This works in Ede, Renkum, Renswoude, Veenendaal and Wageningen.

Add the following to your sensor yaml and change the postcode and house number to whats applicable to yours.
 ```yaml
 - platform: acv
   postcode: 6861GG
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
###### Original Author: @floriskruisselbrink (Floris Kruisselbrink)
###### Modification for acv-groep by: Cadster
###### Modification for new api address by: aritmeester
