# Specs and Features

# <img src= "microSWIFT Assembly, Short.PNG" align=center></img>
## General Specifications

|                                       |                                                |
|:------------                          |:-----------------------------------------------|
|Enclosure                              |Acrylic watertight housing (120 m depth rating)
|Buoy dimensions                        |3.5 in diameter, 17.9 in length
|Weight                                 |6 lbs
|Air-drop package                       |Cardboard tube with 28” diameter chute
|Air-drop dimensions                    |4.25” diameter, 25.5” length,
|Air-drop weight                        |8 lbs (including buoy)
|Batteries                              |8 standard Alkaline “C” cells, user replaceable
|Endurance                              |21 days
|Telemetry                              |Satellite (Iridium SBD), 9603 modem
|Processor                              |STM32U5 series (ARM® Cortex®-M33) , 768 kB RAM, 2048 kB Flash memory
|Onboard software                       |C (https://github.com/SASlabgroup/microSWIFT-v2.1-source)
|Duty cycle                             |Configurable.  Typically 30 minute interval for collection of raw wave data (GPS at 4 Hz), onboard processing, and telemetry.  
|Optional sensors                       |Conductivity and temperature (CT) sensor
|Optional long endurance configuration  |16x C cell batteries in extended housing

## Data Products
|                                                     |                                                |
|:------------                                        |:-----------------------------------------------|
|Position (lat, lon)                                  |± 5 m
|Significant wave height, Hs                          |± 0.1 m
|Peak wave period, Tp                                 |± 1 s
|Dominant wave direction, Dp                          |± 15 deg
|Scalar wave energy spectrum, E(f)                    |± 10-2 m2/Hz, 0.05 < f < 0.5 Hz
|Directional moments of the spectrum (a1,a2,b1,b2)    |± 0.1, 0.05 < f < 0.5 Hz







