# Device Database v4.16.0
For details, refer to [README.md](./README.md).

## Version info
* Add T2G-C-2D-6M device support.
* Add new PSOC™ 4000T part numbers.
* Removal of non-primary SWD selections (ref. [Design impact](#design-impact))
* Bug fixes.

## Recommended device support libraries
* mtb-pdl-cat1 >= 3.11.0
* mtb-pdl-cat2 >= 2.11.0
* mtb-xmclib-cat3 >= 4.4.0
* mtb-pdl-cat5 1.0.0

## Design impact
For this release, non-primary SWD selections (e.g., P0.3 for PSoC™ 4100) were removed from ModusToolbox™ Device Configurator for the following device series:
* PMG1
* CCG
* WLC1
* PAG2S
* PSoC™ 4100S Max
* PSoC™ 4000T

Non-primary SWD selection comes with significant limitations. Please use a primary SWD selection (e.g., P3.3 for PSoC™ 4100).

## Added devices
### PSoC™ 4
#### PSoC 4000T
* CY8C4025LQI-T442
* CY8C4025FNI-T442
* CY8C4045LQI-T442
* CY8C4045LQI-T441
* CY8C4045FNI-T442
* CY8C4025LQI-T441
* CY8C4025LQI-T452
* CY8C4025FNI-T452
* CY8C4045LQI-T452
* CY8C4045LQI-T451
* CY8C4045FNI-T452
* CY8C4025LQI-T451
* CY8C4026LQI-T442
* CY8C4026FNI-T442
* CY8C4046LQI-T442
* CY8C4046LQI-T441
* CY8C4046FNI-T442
* CY8C4026LQI-T441

### TRAVEO™
#### CYT4DN
* [CYT4DNJBAS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBBS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBCS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBDS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBES](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBFS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBGS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBHS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBJS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBKS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBLS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBMS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBNS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBPS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBQS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)
* [CYT4DNJBRS](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-cluster/traveo-t2g-cyt4dn/)



## More information in:
* [Device Database README.md](./README.md)
* [ModusToolbox™ Software Environment, Quick Start Guide, Documentation, and Videos](https://www.infineon.com/cms/en/design-support/tools/sdk/modustoolbox-software)
* [ModusToolbox™ Device Configurator user guide](https://www.infineon.com/ModusToolboxDeviceConfig)
* [Infineon](https://www.infineon.com)

---
© 2022-2024, Cypress Semiconductor Corporation (an Infineon company) or an affiliate of Cypress Semiconductor Corporation.
