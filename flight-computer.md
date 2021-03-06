---
description: Documentation for the Flight Computer
---

# Flight Computer

## Block Diagram

![Block Diagram for Flight Computer](.gitbook/assets/hardware_block_diagram.png)

## Components

### Microcontroller

[_STM32F415_](https://www.st.com/content/st_com/en/products/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus/stm32-high-performance-mcus/stm32f4-series/stm32f405-415/stm32f415rg.html)_\(_[_Datasheet_](https://www.st.com/resource/en/datasheet/stm32f405vg.pdf)_\) ARM M4 CPU with 1MB Flash and 168MHz clock speed and **available on JLCPCB**_

### 9DoF Orientation Sensor \(IMU + Magnetometer\) -- SPI

\_\_[_BMX055_ ](https://www.bosch-sensortec.com/products/motion-sensors/absolute-orientation-sensors/absolute-orientation-sensors-bmx055.html)_\(_[_Datasheet_](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bmx055-ds000.pdf)\)_with gyroscope, accelerometer, and magnetometer, used for drone applications **and available on JLCPCB**_

* Supports I2C & SPI \(3/4 wire\)
* Input voltage: 2.4V to 3.6V
* Independent polling for each of the sensors

### Barometer -- SPI

[_MPL3115A2_](https://www.adafruit.com/product/1893)_\(_[_Datasheet_](https://datasheet.lcsc.com/szlcsc/1904171803_NXP-Semicon-MPL3115A2R1_C54429.pdf)_\) 200-1100 hPa **and available on JLCPCB**_

* Supports I2C & SPI \(3/4 wire\)
* Input voltage: 1.65V to 3.6V
* Sampling frequency 200Hz

### Current/Voltage/Power Monitor -- I2C

\_\_[_INA219_](https://www.ti.com/product/INA219?HQS=TI-null-null-digikeymode-df-pf-null-wwe&DCM=yes&distId=10)_\(_[_Datasheet_](https://www.ti.com/lit/ds/symlink/ina219.pdf?ts=1596310228469&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FINA219%253FHQS%253DTI-null-null-digikeymode-df-pf-null-wwe%2526DCM%253Dyes%2526distId%253D10)_\) I2C compatible, max voltage 26, **and available on JLCPCB**_

### GPS Receiver -- I2C

\_\_[_SAM-M8Q_](https://www.u-blox.com/en/product/sam-m8q-module)_\(_[_Datasheet_](https://www.u-blox.com/sites/default/files/SAM-M8Q_DataSheet_%28UBX-16012619%29.pdf)_\) I2C compatible, **and NOT available on JLCPCB**_

### FRAM -- I2C

\_\_[_MB85RC256V_](https://www.adafruit.com/product/1895)_\(Datasheet\) I2C compatible, 256 K, 1MHz max frequency, **and available on JLCPCB**_

### EEPROM

\_\_[_CAT24C256_](https://www.onsemi.com/products/memory/eeprom-memory/cat24c256)_\(_[_Datasheet_](https://www.onsemi.com/pub/Collateral/CAT24C256-D.PDF)_\) I2C compatible, 256K, 1MHz max frequency, **and available on JLCPCB**_

### Radio Module -- SPI

\_\_[_NRF24L01P-R_](https://www.nordicsemi.com/Products/Low-power-short-range-wireless/nRF24-series)_\(_[_Datasheet_](https://datasheet.lcsc.com/szlcsc/Nordic-Semicon-NRF24L01P-R_C8791.pdf)_\) SPI compatible, 2.4GHz ISM band, **and available on JLCPCB**_

###  __ 









