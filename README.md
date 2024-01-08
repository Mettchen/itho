# itho

This page will serve as living documentation for the Itho system that I have.
The system consists of:
- Ventilation: Itho Daalderop HRU 400 (DuoZone)
- Floorheating Controller: Itho Daalderop Autotemp (x2 - begane grond and 2de verdieping)
- Warmtepomp: Itho Daalderop WPU 5G
- Temperature: Itho Daalderop Spider
- CO2: Itho Daalderop RFT CO2 sensor


# Connection
| System  | Communication | Solution used | Supported from | 
| ------------- | ------------- | ------------- | ------------- |
| Ventilation | Modbus   | ESP+MAX485 | Heating Service | 
| Floorheating  | Modbus I2C  | https://www.nrgwatch.nl/product/itho-non-cve-wifi-module/ | Heating Service | 
| Warmtepomp  | Modbus I2C  | https://www.nrgwatch.nl/product/itho-non-cve-wifi-module/ | Klimaatgarant | 
| Temperature  | Ramses II (886 MHz)  | https://indalo-tech.onlineweb.shop/ | Heating Service | 
| CO2 | Ramses II (886 MHz)  | https://indalo-tech.onlineweb.shop/ (Same stick as above) | Heating Service | 

