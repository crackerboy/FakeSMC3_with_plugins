# FakeSMC3 with plugins
Driver for emulation SMC device with hardware sensors support

## HWSensors
### This is a Mac OS X Package
Working 10.6 to 11.x

### HWSensors branch based on FakeSMC-3.x

### The package includes:
* FakeSMC.kext version 3.x
- ACPIMonitor.kext for custom making ACPI methods to access to hardware
- VoodooBatterySMC for laptop battery monitoring
- IntelMCHMonitor for chipset temperature monitoring, from 7th gen
  (Kabylake, Coffeelake, and up). Get also DIMM temperature
- CPU sensors:
    + IntelCPUMonitor, from Core Duo up to IceLake
    + AmdCpuMonitor, FX... and Ryzen
- GPUSensors
    + RadeonMonitor  for ATI/AMD Radeon card (temperature only), up to RX5900
    + GeforceSensors for Nvidia card Fermi, Kepler, Maxwell, Pascal
    + NVClockX for Nvidia Geforce 7xxx, 8xxx, Tesla
    + X3100 for IntelX3100 (at GM950 chipset)
- LPC chip sensors, motherboard parameters like FAM, Voltages, temperatures
    + ITEIT87x  for chips ITE 87xx, 86xx, usually present on Gigabyte motherboards
    + W836x  for chips Winbond/Nuvoton 83xxx, NCT67xx, usually present on ASUS motherboards
    + F718x  for chips Fintek 
    + PC8739x for chip SMC
- SMI Monitor
    + monitor and control temperature and fans in Dell computers by using SMM technology
- Applications 
    + HWMonitorSMC, it has less functionality. Working with old computer. BigSur 11.x compatible.
    + HWMonitorSMC2 for SandyBridge and up. It is separate project https://github.com/CloverHackyColor/HWMonitorSMC2


### HWSensors Project (c) 2010 netkas, slice, usr-sse2, kozlek, navi, vector sigma and other contributors. All rights reserved. 
