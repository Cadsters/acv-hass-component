# Home Assistant acv-groep component
Component for bin/waste collection  by acv-groep
This works in Ede, Renkum, Renswoude, Veenendaal and Wageningen

add the following to your sensor yaml and change the postcode and housenumber to whats applicable for yours
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
###### Original Author: @vloris (Floris Kruisselbrink)
###### Modification for acv-groep by: Cadster
