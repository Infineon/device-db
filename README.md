# Device Database (device-db) - Device Metadata for ModusToolbox™ Ecosystem

## Overview

Device database provides device information for project-creator, configurators,
and other ModusToolbox™ tools. The device database is tied to the PDL
(Peripheral Driver Library) packages available for different device categories.

The database is structured as a hierarchical directory tree with device-related
information defined at different hierarchy levels.

See [DEVICES.md](./DEVICES.md) for a list of supported devices and modules.

## Related Middleware and Dependencies

**This database is used by:**

- [Device Configurator](https://www.infineon.com/ModusToolboxDeviceConfig) - Displays and
  configures peripheral resources
- [BSP Assistant](https://www.Infineon.com/ModusToolboxBSPAssistant) - Creates and configures
  the BSP for a given device/module part number
- [QSPI Configurator](https://www.Infineon.com/ModusToolboxQSPIConfig) - Creates and
  configures QSPI configuration for external memory chips
- [Project Creator](https://www.Infineon.com/ModusToolboxProjectCreator) - Selects devices
  when creating new ModusToolbox™ projects

**The libraries depend on this database:**

- [MTB CAT1 Peripheral Driver Library](https://github.com/Infineon/mtb-pdl-cat1) - PDL for CAT1 devices
- [MTB CAT2 Peripheral Driver Library](https://github.com/Infineon/mtb-pdl-cat2) - PDL for CAT2 devices
- [MTB CAT3 XMC Library](https://github.com/Infineon/mtb-xmclib-cat3) - Library for CAT3 (XMC) devices
- [MTB CAT5 Peripheral Driver Library](https://github.com/Infineon/mtb-pdl-cat5) - PDL for CAT5 devices
- [MTB PSE8xxGP Device Support Library](https://github.com/Infineon/mtb-dsl-pse8xxgp) - DSL for PSOC™ Edge PSE8xxGP devices
- [MTB PSE8xxGO Device Support Library](https://github.com/Infineon/mtb-dsl-pse8xxgo) - DSL for PSOC™ Edge PSE8xxGO devices
- [MTB PSE8x6 Device Support Library](https://github.com/Infineon/mtb-dsl-pse8x6) - DSL for PSOC™ Edge PSE8x6 devices

## Release Notes and Changelog

- [RELEASE.md](./RELEASE.md) - Detailed release notes for all versions

## License

- **[LICENSE.txt](LICENSE.txt)** - Infineon End User License Agreement

---

## Copyright

© 2022-2026, Infineon Technologies AG or an affiliate of Infineon Technologies AG.
