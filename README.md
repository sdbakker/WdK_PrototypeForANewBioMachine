# Prototype for a new BioMachine

This repository contains the simplified and stripped version of [Prototype for a new Bio Machine](http://ivanhenriques.com/2012/09/25/prototype-for-a-new-biomachine/ "Prototype for a new Bio Machine") by [Ivan Henriques](http://ivanhenriques.com "Ivan Henriques").

## Description of Files

* JuremaController
  Containes the arduino source code
* PlantController
  Contains the hardware schematics and material list

### JuremaController
* JuremaController.ino
  The controller source code
* twi.c 
  I2C library source code
* twi.h
  I2C library header file
* arduino-libraries-CapacitiveSensor.zip
  Arduino libarary for capacitive sensing 

### PlantController
* PlantController.sch
  CadSoft Eagle simplified schematic file of the PlantController main board
* PlantController.brd
  CadSoft Eagle board file of the PlantController main board
* __PlantControllerSimplified.png__
  Imange of simplified schematic of the main controller board
* __PlantController_brd.png__
  Image of main controller board

* PC_CapSense.sch
  CadSoft Eagle simplified schematic file of the sensor add-on board
* PC_CapSense.brd
  CadSoft Eagle board file of the sensor add-on board
* __PlantControllerSensorBoardSimplified.png__
  Image of simplified schematic of sensor add-on board
* __PC_CapSense_brd.png__
  Image of sensor add-on board layout

* __PlantController_BOM.pdf__
  Bill of materials with order numbers and URLs
