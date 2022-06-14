# atmosferISA
Calculating characteristics Atmosfer ISA with C

![](https://img.shields.io/github/license/Nabil-Syahnaufal/atmosferISA)
![](https://img.shields.io/github/issues/Nabil-Syahnaufal/atmosferISA)
![](https://img.shields.io/github/issues-closed/Nabil-Syahnaufal/atmosferISA)
![](https://img.shields.io/badge/Python-3-blue)
![](https://img.shields.io/github/forks/Nabil-Syahnaufal/atmosferISA)
![](https://img.shields.io/github/stars/Nabil-Syahnaufal/atmosferISA)
![](https://img.shields.io/github/last-commit/Nabil-Syahnaufal/atmosferISA)


## What is International Standard Atmosphere(ISA)?
The International Standard Atmosphere (ISA) is a static atmospheric model of how the pressure, temperature, density, and viscosity of the Earth's atmosphere change over a wide range of altitudes or elevations. It has been established to provide a common reference for temperature and pressure and consists of tables of values at various altitudes, plus some formulas by which those values were derived. The International Organization for Standardization (ISO) publishes the ISA as an international standard, ISO 2533:1975.[1] Other standards organizations, such as the International Civil Aviation Organization (ICAO) and the United States Government, publish extensions or subsets of the same atmospheric model under their own standards-making authority.

### Description
The ISA mathematical model divides the atmosphere into layers with an assumed linear distribution of absolute temperature T against geopotential altitude h.[2] The other two values (pressure P and density ρ) are computed by simultaneously solving the equations resulting from:

the vertical pressure gradient resulting from hydrostatic balance, which relates the rate of change of pressure with geopotential altitude:
![image](https://user-images.githubusercontent.com/97229948/173484501-c57301ea-75eb-4a96-a558-2302f26fd118.png)

the ideal gas law in molar form, which relates pressure , density, and temperature:

![image](https://user-images.githubusercontent.com/97229948/173484573-6c040be2-148b-45ad-a76c-20072f5c9d70.png)

