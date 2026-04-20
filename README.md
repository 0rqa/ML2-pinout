# Pinout of IBM/Lenovo ML2 edge connector and socket 

>[!Caution]
> Disclaimer / Reverse Engineering Notice: <br> <br>
> All information, diagrams, and schematics in this repository were obtained through independent reverse engineering, measurement, and observation. 
> No proprietary, confidential, or leaked documents were used directly to create this content. 
> All pin assignments, signal mappings, and layouts represent independent analysis and do not reproduce any proprietary documentation. <br> <br>
> This project is intended for educational, research, and interoperability purposes only. 
> Commercial use of patented or proprietary technologies is not authorized by this notice.

<br>

>[!NOTE]
>This repo is still being developed (WIP). All information in this repository is provided in good faith but may contain inaccuracies.

<br>

---

<br>
    
- [molex 1717742118](https://www.digikey.com/en/products/detail/molex/1717742118/4504792) - 118 pin 0.8mm edge connector

<br>

[![Image](https://github.com/0rqa/ML2-pinout/blob/main/Kicad/ML2_interface_pinout/ML2_interface_pinout_01.png)](https://github.com/0rqa/ML2-pinout/blob/main/Kicad/ML2_interface_pinout/ML2_interface_pinout_01.pdf)


<br>
<br>
<br>


| pin name | description  |
|----------|--------------|
| ML_P_OK | High when 12V, 3.3V, 12V_aux, 3.3V_aux are in spec. |
|12V_aux / 3.3V_aux|Voltage present always. MAX 15W|
|12V / 3.3V|Voltage present only in operation.|
|SDA / SCL |I2C 3.3V  data / clock line|
|I2C_reset|I2C reset line|
|I2C_int||
|/|/|
|PCIE_wake||
|PCIE_reset||
|CLK+|Posistive - 100MHz PCIE bus Referance clock|
|CLK-|Negative - 100MHz PCIE bus Referance clock|
|HSTX+_0-7||
|HSTX-_0-7||
|HSRX+_0-7||
|HSRX-_0-7||





<br>
<br>
<br>




# https://www.digikey.com/en/products/detail/molex/1717742118/4504792
