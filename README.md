# Retarding-Field-Analyzer 
Retarding Field Analyzers (RFA) allow to measure the Ion Energy Distribution, Plasma Potential, Ion Density and Ion Temperature.

### Driving and Measurement Specifications
| Variable | Range | Resolution | Accuracy | Notes
| :---   | :---:   | :---:   | :---:   |  :--- |
| Suppressor Voltage | 	0 - 600 V  | 0.1 V | ± 0.1 V  | Repelling of electrons |
| Retarding Voltage | 	20 - 1000 V  | 0.5 V | ± 0.2 V  | Ion retardation for energy analysis |
| Collector Ion Current | 	0 - 100 μA  | 10 nA |  ± 2% RD  | Direct measurement of ion current |

### Features
| Variable | Value | Notes
| :---   | :---:   | :--- |
| Update Rate | 5 Hz | report of fully swept cycles |
| Voltage Ramp Rate | ±100 V/μs | slew rate for retarding voltage |
| Voltage Noise/Ripple | ≤ 5 mV peak-to-peak | noise characteristics |
| Digital Interface | USB-C | serial communication |

## Partlist
|QTY|	DESCRIPTION	|PART NAME|
| :---:   | :---   | :---   |
|1|	Microcontroller |	Arduino Nano |
|3|	24-bit ADC | ADS1220IPW |
|1|	... |	... |

## Build

- print PCB from Gerber File
- order  and assemble parts from Partlist
- flash MCU code from PlatformIO Project
