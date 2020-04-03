# vehicule-tour
## M1-CSA project

### Description of the project

In the context of the e-flooding project, the SEPIA team at IRIT is looking for a motivated student team working on the integration of a territory map and an algorithm of planning of civil security vehicles movement. This part of the project is called “Vehicle Tours” and should simulate emergency services interventions during a flood, which are deployed on the territory to save people, animals and goods.

### Content

The E-flooding project is a simulation of a flooding emergency services with constraints of resources such as vehicules (with a certain amount of places, an ability to drive only on roads, water or on airs) and the emergency stations, where they start from. Those saving point might change during the time if needed.
The vehicules needs to go at a precise location to save people in distress. Those saving zones are called challenge, in other words buildings where the emergency services need to have an intervention (hospitals, schools…).
The vehicles should opere a optimized circuit, such that they can pass through as much as challenge possible according to the following constraints: blocked roads, vehicle type and capacity.

### Goals

The goal of the product to be delivered is to implement an interaction between VROOM and QGIS, and adapting VROOM to run a custom algorithm and apply it to a predefined graph.

### Customer constraints

The project should be “Plug and Play”, that means can works with any map and algorithm without new configuration. The project should also be portable, that means can be executed easily on any computer, to achieve that, the solution picked is Docker in order to deliver the project in containers.
There is no limit in terms of financial spend into the wages and the numbers of hours worked.

### Technical specifications

The project will be developed using the programming language Python 3 which will interface VROOM tool with Openstreetmap and QGIS, a geographical information system.
The program should be able to take as an input a graph representing the different challenges.

### Getting started

Simply clone the repo and run:

```
docker-compose up
```