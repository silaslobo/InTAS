# InTAS
InTAS is the realistic Ingolstadt traffic scenario for SUMO. This scenario comprises the following features:

- **Now InTAS supports pedestrian simulation**
- **Modeled and Validated with real traffic numbers**
- 24 hours of simulation
- Actual road network based on the city of Ingolstadt
- Street categories for VANETs simulation: *tunnel*, *under.building*, *under.bridge*
- Simulation of public parking areas 
- Real location of all Traffic Lights in city
- Simulation of real Traffic Light Systems
- Buildings shape and location 
- Simulation of public transport system: *real bus routes with the actual time-table*

You can watch [InTAS](https://www.youtube.com/watch?v=UgPeBxXzDHc) presentation for the SUMO User Conference 2020. 


## Tested for the following versions:
- [x] SUMO version 1.9.0
- [x] SUMO version 1.8.0
- [x] SUMO version 1.7.0

## Actual State
- **Validation:** 24 points of traffic measurment
- **Simulation of Traffic Light System (TLS):** 20 TLS
- **Actual Scenario Error (NRMSE):** 0.33

## How To 
InTAS can be lauched from de cofiguration file:
- ```sumo -c InTAS_buildings.sumocfg```, considering:
  - *buildings*
  - *bus stops*
  - *E1 detectors*
  - *parking areas*
- ```sumo-gui -c InTAS_full_poly.sumocfg```, which provides full polygon bringing a nicer visualization and adds to the previous file:
  - *amenity*
  - *land use*
  - *water*
  - *leisure*
  - *forest*
![InTAS full poly](https://github.com/silaslobo/InTAS/blob/master/InTAS.png)

## Authors
Development of InTAS is part of ongoing research work at [Technische Hochschule Ingolstadt](https://www.thi.de/en/research/carissma/laboratories/car2x-laboratory). Maintenance is coordinated by Silas Lobo. Contributions are happily accepted.

Contact: Silas Lobo [silascorreia.lobo@thi.de]

## License
InTAS is licensed under **GNU General Public License v3.0**, see [lisence file](https://github.com/silaslobo/InTAS/blob/master/LICENSE) for details.
