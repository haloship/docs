---
description: Documentation for the Flight Computer
---

# Flight Computer

![Block Diagram for Flight Computer](.gitbook/assets/hardware_block_diagram.png)

### Microcontroller

[_STM32F415_](https://www.st.com/content/st_com/en/products/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus/stm32-high-performance-mcus/stm32f4-series/stm32f405-415/stm32f415rg.html)_\(_[_Datasheet_](https://www.st.com/resource/en/datasheet/stm32f405vg.pdf)_\) ARM M4 CPU with 1MB Flash and 168MHz clock speed_

### 9DoF Orientation Sensor \(IMU + Magnetometer\)

\_\_[_BMX055_ ](https://www.bosch-sensortec.com/products/motion-sensors/absolute-orientation-sensors/absolute-orientation-sensors-bmx055.html)_\(_[_Datasheet_](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bmx055-ds000.pdf)\)_with gyroscope, accelerometer, and magnetometer, used for drone applications_

* Supports I2C & SPI \(3/4 wire\)
* Input voltage: 2.4V to 3.6V
* Independent polling for each of the sensors

### Barometer

\_\_[_BMP380_](https://www.bosch-sensortec.com/products/environmental-sensors/pressure-sensors/bmp388/)_\(_[_Datasheet_](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bmp388-ds001.pdf)_\) 300-1250 hPa_

* Supports I2C & SPI \(3/4 wire\)
* Input voltage: 1.65V to 3.6V
* Sampling frequency 200Hz



###  __ 









