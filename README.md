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


at each geopotential altitude, where g is the standard acceleration of gravity, and Rspecific is the specific gas constant for dry air (287.058J⋅kg−1⋅K−1).

Air density must be calculated in order to solve for the pressure, and is used in calculating dynamic pressure for moving vehicles. Dynamic viscosity is an empirical function of temperature, and kinematic viscosity is calculated by dividing dynamic viscosity by the density.

Thus the standard consists of a tabulation of values at various altitudes, plus some formulas by which those values were derived. To accommodate the lowest points on Earth, the model starts at a base geopotential altitude of 610 meters (2,000 ft) below sea level, with standard temperature set at 19 °C. With a temperature lapse rate of −6.5 °C (-11.7 °F) per km (roughly −2 °C (-3.6 °F) per 1,000 ft), the table interpolates to the standard mean sea level values of 15 °C (59 °F) temperature, 101,325 pascals (14.6959 psi) (1 atm) pressure, and a density of 1.2250 kilograms per cubic meter (0.07647 lb/cu ft). The tropospheric tabulation continues to 11,000 meters (36,089 ft), where the temperature has fallen to −56.5 °C (−69.7 °F), the pressure to 22,632 pascals (3.2825 psi), and the density to 0.3639 kilograms per cubic meter (0.02272 lb/cu ft). Between 11 km and 20 km, the temperature remains constant.[3][4]

### Comparison of a graph of International Standard Atmosphere temperature and pressure and approximate altitudes of various objects and successful stratospheric jumps

![image](https://user-images.githubusercontent.com/97229948/173485000-ce7a8e25-64d6-4cb6-a86f-6de2a1c62d13.png)
