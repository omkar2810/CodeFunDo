# CodeFunDo
Project Repo for TEAM **NATURAL DISASTERS**

### Problem Statement

Adding efficiency to city evacuation and post disaster management using crowdsourcing.

### Background

A natural disaster always leads to tremendous chaos. This chaos makes it difficult for first responders and evacuators to reach everyone in a timely manner. Hence many people are not able to evacuate on time leading to excessive loss of/damage to life. At the same time there are people leaving the city with empty seats in their cars or even leaving cars behind. This represents a potentially huge pool of seats-in-vehicles, left unused, which could be put to better use.

### Idea

In the case of a natural disaster in a city, we aim to liquidate this unused-vehicular-seat asset and get as many people as possible, in vehicles, to provide a boost to the number of people who are able to evacuate successfully.

### How do we plan to do it?

- We plan on building a smartphone application to achieve this. The app operates in two modes - volunteer and SOS. The app will use SMS and low bandwidth internet(where possible) for communication.

- Upon installation the app will ask for the vehicle details and some permissions(Turn on mobile network, location service, wifi, battery saver etc). It will also download the map of the area in a compressed format for later use.

- When a disaster(eg tsunami) strikes, we will send an activation signal to all the phones with our app(either through internet or through SMS). This will turn on the location services, battery saver, wifi, and mobile network). Also the app will be launched in SOS mode, which means that location will be continuously tracked and shared.

- People can choose to switch to volunteer mode, wherein they can select the number of seats available in their car. We will then suggest the best possible path for them to evacuate. This path will also be optimised so that they are able to pickup as many users with SOS status as possible. The route optimisation will also take into account the speed of the car and will ensure that the safety of those already in cars is not compromised.

- The SOS location data can also be used to identify hotspots, for post disaster management. This data can be shared with official emergency responders, relief camps etc.

### Extensibility

1.  The app can then be expanded to connect people who are willing to provide goods(like extra medicines) and services(like doctors) to other affected people within the city.
    
2.  The app can also be expanded to integrate the already existing services network, like Uber, Ola etc for transportation, various hospitals etc.
