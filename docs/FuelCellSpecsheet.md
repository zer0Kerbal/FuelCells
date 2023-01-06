# Fuel Cell Specifications

## Design considerations

* Fuel cells first made their first official appearance during the Gemini/Apollo programs
* Continued use in the Shuttle and ISS programs.
* As technology advanced, the mass of the storage (ec) was cut in half (Pb --> LiFePO4 as example from Apollo to SpaceX)
* Capacity of storage doubled during the same time
* Fuel storage containment improvements have also allows more fuel to be stored in the same sized container (not factored in)

## Specification Spreadsheet

aim is 42 hours of runtime using only internal fuels. (which is seven kerbal days (six hours per day))

151,200 seconds of runtime (see runtime sheet)

| Mod  | Name      |  Cost |  Entry |    Mass |         Tech          |   TL | maxEC | Fuel (L) | RunTime† | Battery (EC) | efficiency‡ |
| :--- | :-------- | ----: | -----: | ------: | :-------------------: | ---: | ----: | :------: | -------: | -----------: | ----------: |
| (S)  | Fuel Cell |   750 |   2250 |    0.05 |    largeElectrics     |    7 |   1.5 |    -     |     0h0m |           50 |    baseline |
| (S)  | FC Array  |  4500 |  13500 |    0.24 | specializedElectrics  |    8 |    18 |    -     |     0h0m |          300 |    baseline |
|      |           |       |        |         |                       |      |       |          |          |              |             |
| (HB) | 0.3125m   |   330 |    750 |    0.03 |     survivability     |    3 | 0.375 |    5     |     0h0m |           10 |        -25% |
| (HB) | 0.625m    |   495 |   1250 |    0.05 |     basicScience      |    4 |  0.75 |    15    |     0h0m |           50 |        -15% |
| (HB) | 1.25m     |   895 |   2250 |     0.1 |       Electrics       |    5 |   1.5 |    30    |     0h0m |          100 |             |
| (HB) | 1.875m    |  2390 |   6008 |  0.2967 |    Miniaturization    |    5 |   4.5 |    90    |     0h0m |          300 |        +10% |
| (HB) | 2.5m      |  4277 |  10753 |    0.59 |     advElectrics      |    6 |     9 |   180    |     0h0m |          600 |        +15% |
| (HB) | 3.75m     |  7829 |  19683 |     1.2 |    largeElectrics     |    7 |    18 |   365    |     0h0m |         1225 |        +25% |
| (HB) | 5.0m      |     2 |  35429 |     2.4 | specializedElectrics  |    8 |    36 |   730    |     0h0m |         2427 |        +50% |
| (HB) | 7.5m      | 17616 |  44287 |  3.3333 | specializedElectrics  |    8 |    50 |   1010   |     0h0m |         3371 |        +75% |
| (HB) | 10m       | 33031 |  83038 |  6.9444 | experimentalElectrics |    9 |    75 |   1515   |     0h0m |         5056 |       +100% |
| (HB) | 20m       | 49546 | 124556 | 11.5741 | experimentalElectrics |    9 |   125 |   2530   |     0h0m |         8427 |      +200 % |
|      |           |       |        |         |                       |      |       |          |          |              |             |
| (HB) | mk0       |       |        |         |     basicScience      |    4 |       |          |     0h0m |              |        -25% |
| (HB) | mk1       |       |        |         |       Electrics       |    5 |       |          |     0h0m |              |        -15% |
| (HB) | mk2       |  4277 |  10753 |    0.59 |     advElectrics      |    6 |  8.85 |   180    |     0h0m |          600 |             |
| (HB) | mk3       |  7829 |  19683 |     1.2 |    largeElectrics     |    7 |    18 |   365    |     0h0m |         1225 |        +15% |
| (HB) | mk4       |       |        |         | specializedElectrics  |    8 |       |          |     0h0m |              |         +25 |
| (HB) | mk5       |       |        |         | experimentalElectrics |    9 |       |          |     0h0m |              |        +50% |

* S = Stock | HB = Hot Beverage | HB+ = Hot Beverage + Another | US =  Universal Storage | US2 =  Universal Storage 2 *

†: internal capacity only
‡: currently doesn't include efficency adjustment to maxEX/Battery/mass/costs - fuel capacity won't be affected

## Effeciency scaled

| Mod  | Name    | Cost | Entry |    Mass |      Tech       |   TL | maxEC | Fuel (L) | RunTime† | RunTime+EF† | Battery (EC) | efficiency‡ |
| :--- | :------ | ---: | ----: | ------: | :-------------: | ---: | ----: | :------: | -------: | -------: | -----------: | ----------: |
| (HB) | 0.3125m |  330 |   750 |  0.0375 |  survivability  |    3 |   0.1 |    20    |   22h 0m |   22h 0m |            7 |        -25% |
| (HB) | 0.625m  |  495 |  1250 |  0.0575 |  basicScience   |    4 | 0.125 |    40    |   35h 0m |   35h 0m |           50 |        -15% |
| (HB) | 1.25m   |  895 |  2250 |     0.1 |    Electrics    |    5 |  0.25 |    80    |   35h 0m |   35h 0m |          200 |             |
| (HB) | 1.875m  | 2390 |  6008 | 0.26972 | Miniaturization |    5 |   0.5 |   170    |   37h 0m |   42h 0m |          500 |        +10% |
| (HB) | 2.5m    | 4277 | 10753 | 0.23455 |  advElectrics   |    6 |   1.0 |   380    |   45h 0m |   53h 0m |         1000 |        +15% |
| (HB) | 3.75m   | 7829 | 19683 |    0.96 | largeElectrics  |    7 |   2.0 |   768    |   42h 0m |   57h 0m |         2000 |        +25% |
    +25% |

†: internal capacity only
‡: cumulative efficency adjustment to maxEX/Battery/mass/costs - fuel capacity won't be affected even though advances in tech would increase storage capabilities

## Stock Specifications

### Stock Fuel Cell

* ***cost:*** 750
* ***entry cost:*** 2250
* ***techRequired:*** Electrics
* ***mass:*** 0.05
* ***EC/s Produces:*** 1.5
* ***EC storage:*** 50

### Stock Fuel Cell Array

* ***cost:*** 4500
* ***entry cost:*** 13500
* ***techRequired:*** Electrics
* ***mass:*** 0.24
* ***EC/s Produces:*** 18
* ***EC storage:*** 300
