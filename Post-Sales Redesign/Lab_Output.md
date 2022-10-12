Lab_Output.md

## Data.csv data file contents: ##

Inc_ID | Inc_Type | VIN_Number | Make | Model | Year | Inc_Date | Description
------------|---------------|------------|------|-------|------|---------------|------------
1 | I | VXIO456XLBB630221 | Nissan | Altima | 2003 | 2002-05-08 | Initial sales from TechMotors
2 | I | INU45KIOOPA343980 | Mercedes | C300 | 2015 | 2014-01-01 | Sold from EuroMotors
3 | A | VXIO456XLBB630221 |  |  |  | 2014-07-02 | Head on collision
4 | R | VXIO456XLBB630221 |  |  |  | 2014-08-05 | Repair transmission
5 | I | VOME254OOXW344325 | Mercedes | E350 | 2015 | 2014-02-01 | Sold from Carmax
6 | R | VOME254OOXW344325 |  |  |  | 2015-02-06 | Wheel allignment service
7 | R | VXIO456XLBB630221 |  |  |  | 2015-01-01 | Replace right head light
8 | I | EXOA00341AB123456 | Mercedes | SL550 | 2016 | 2015-01-01 | Sold from AceCars
9 | A | VOME254OOXW344325 |  |  |  | 2015-10-01 | Side collision
10 | R | VOME254OOXW344325 |  |  |  | 2015-09-01 | Changed tires
11 | R | EXOA00341AB123456 |  |  |  | 2015-05-01 | Repair engine
12 | A | EXOA00341AB123456 |  |  |  | 2015-05-03 | Vehicle rollover
13 | R | VOME254OOXW344325 |  |  |  | 2015-09-01 | Replace passenger side door
14 | I | UXIA769ABCC447906 | Toyota | Camery | 2017 | 2016-05-08 | Initial sales from Carmax
15 | R | UXIA769ABCC447906 |  |  |  | 2020-01-02 | Initial sales from Carmax
16 | A | INU45KIOOPA343980 |  |  |  | 2020-05-01 | Side collision


## Initial Sales Data: ##

Incident_Type | VIN_Number | Make | Year
--------------|------------|------|-----
I | EXOA00341AB123456 | Mercedes | 2016
I | INU45KIOOPA343980 | Mercedes | 2015
I | UXIA769ABCC447906 | Toyota | 2017
I | VOME254OOXW344325 | Mercedes | 2015
I | VXIO456XLBB630221 | Nissan | 2003


## Accident Data: ##

Incident_Type | VIN_Number | Make | Year
--------------|------------|------|-----
A | EXOA00341AB123456 | null | null
A | INU45KIOOPA343980 | null | null
A | VOME254OOXW344325 | null | null
A | VXIO456XLBB630221 | null | null


## Accident to Incident Data Join and Count: ##

Make | Year | Record Count
-----|------|-------------
Mercedes | 2015 | 2
Mercedes | 2016 | 1
Nissan | 2003 | 1