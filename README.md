# Home Assistant acv-groep-component
Component for bin/waste collection  by acv-groep

add the following to your sensor yaml and change the postcode and housenumber to whats applicable for yours

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
