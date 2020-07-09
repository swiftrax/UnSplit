# UnSplit
A Kyria layout with some of the thumb keys removed. It is non split and powered by an ATMega32u4-AU. Featuring an exposed component layout with diodes in a bank.

## PCB Renders
Top Full Ground Plane
![Front Full Ground Plane](https://github.com/swiftrax/UnSplit/blob/master/Images/Front.PNG)
Bottom Full Ground Plane
![Back Full Ground Plane ](https://github.com/swiftrax/UnSplit/blob/master/Images/Back.PNG)
Top Partial Ground Plane
![Front Partial Ground Plane](https://github.com/swiftrax/UnSplit/blob/master/Images/Front_Partial.PNG)
Bottom Partial Ground Plane
![Back Partial Ground Plane ](https://github.com/swiftrax/UnSplit/blob/master/Images/Back_Partial.PNG)
*Open with KiCad nightly*

## Bill of Materials
* [ATMega32u4-AU x 1](https://lcsc.com/product-detail/ATMEL-AVR_Microchip-Tech-ATMEGA32U4-AU_C44854.html)
* [16MHz Resonator x 1](https://lcsc.com/product-detail/Others_Murata-Electronics-CSTNE16M0V530000R0_C341521.html)
* [22 Ohm Resistor x 2](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_TyoHM-RMC0805221-N_C325772.html)
* [5.1k Ohm Resistor x 2](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_TyoHM-RMC08055-1K1-N_C269748.html)
* [10k Ohm Resistor x 2](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_TyoHM-RMC080510K1-N_C269742.html)
* [100nF Capactior x 3](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Walsin-Tech-Corp-0805B104J500CT_C314285.html)
* [1uF Capactior x 1](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_FH-Guangdong-Fenghua-Advanced-Tech-0805B105K500NT_C215803.html)
* [10uF Capactior x 1](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_SAMSUNG_CL10A106MA8NRNC_10uF-106-20-25V_C96446.html)
* [500mA Polyfuse x 1](https://lcsc.com/product-detail/Surface-Mount-Fuses_0-25A-16V-Self-healing-fuse_C70068.html)
* [Reset Switch x 1](https://lcsc.com/product-detail/Tactile-Switches_C-K_RS-187R05A2-DSMTRT_C-K-RS-187R05A2-DSMTRT_C221929.html)
* [Type C Port x 1](https://lcsc.com/product-detail/USB-Type-C_Korean-Hroparts-Elec-TYPE-C-31-M-14_C223907.html)
* [Diodes x 44](https://lcsc.com/product-detail/Diodes-General-Purpose_MDD-Microdiode-Electronics-SM4007PL_C64898.html)

*Capactiors and Resistors are 0805 Package size*

## Firmware
[QMK Firmware](https://github.com/swiftrax/qmk_firmware/tree/unsplit/keyboards/handwired/swiftrax/unsplit)

[VIA JSON](https://github.com/swiftrax/keyboards/blob/swiftrax/src/swiftrax/unsplit.json)

## License

This repository is under the [GNU GPL V2 license](https://github.com/swiftrax/UnSplit/blob/master/LICENSE). If you plan to sell these pcbs, make sure to read it.
