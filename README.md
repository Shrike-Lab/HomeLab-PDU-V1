# WIP!!!!!!!

# **MiniLab PSU** - 5 Port Homelab USB-C PD Power Supply
MiniLab PSU is a power delivery solution for micro PC clusters and homelabs that fits in a 1U 10-inch rack. It's built around a 300W Meanwell PSU featuring 5 USB-C power delivery ports and active cooling. 

### Kits/PCBs Coming Soon?: [Shrikelab.co](Shrikelab.co) ###

<p float="left">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/ph-1.png" width="48%" />
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/ph-2.png" width="48%" /> 
</p>

<p float="left">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/ph-2.png" width="48%" /> 
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/ph-2.png" width="48%" />
</p>


Mini and micro labs are a great solution for homelabbing, but the power delivery options are often bulky and hard to manage due to the need for an individual power brick per computer.
This project addressess this by consolidating power delivery for up to five 65W micro PCs into a single unit that fits in a standard 1U 10-inch rack mount. This differs from a conventional multi-port USB PD hub by not needing to re-negotiate any power delivery voltages when a unit is turned off or unpluggded, or when the power load across ports changes drastically. Also the packing is designed specifially with rack mounting in mind, with active cooling and power switching.

Full Video and build guide [here](youtube.com)

## Features:
- 1U 10 inch form factor - 234mm Deep (9.2")
- 5x 65W USB-C outputs
- Active cooling with 2x 40mm fans
- Meanwell PSU
- Built around XPM52C PD chips

## PCB: ##
The PCB is 2 layers and 1.6mm. "PCB/1U Minilab PSU V2" folder contains both the source and production files. The production files can be uploaded to JLCPCB or PCBWAY for manufacturing or PCB assembly. PCB assembly is recommended unless you have capability to do reflow soldering.

## Housing: ##
**Facia:**
- Front and rear facia should be printed from ABS to better deal with heat output from the PSU and breakout PCB. Printed with 5 walls and 40% infill, STL's can be found in "CAD".

**Enclosure:**
- DXFs, STPs and STLs for manufacturing the bottom housing and lid can be found in "CAD".

## Cooling: ##
Switched 24V is stepped down via an LM2596 to power chassis fans. The PCB has 2 fan headers, one for the PCB fan and an optional header for swapping out the PSU fan if it's too loud.

## Assembly:


## Bill of Materials:

### Components

| Part        | Quantity | Notes                                  | Link                                                                            |
| ----------- | -------- | -------------------------------------- | ------------------------------------------------------------------------------- |
| HRP-300-24  | 1        | Meanwell                               | https://www.digikey.com/en/products/detail/mean-well-usa-inc/HRP-300-24/7704305 |
| 16mm Button | 1        | Latching 24v                           | -                                                                               |
| 40mm Fan    | 2        | One unless the PSU fan is replaced too | -                                                                               |
| LM2596      | 1        | Buck converter                         | https://www.aliexpress.com/item/1005010001439374                                |
| Heatsinks   | 7        | 10mmx10mm                              | https://www.aliexpress.com/item/10000038519525                                  |
| PD Boards   | 5        |                                        | https://www.aliexpress.com/item/1005007016771773                                |

### Chassis:
| Part           | Quantity | Notes            | Link      |
| -------------- | -------- | ---------------- | --------- |
| Bottom Housing | 1        | 1mm Steel        | FILE PATH |
| Lid            | 1        | 1mm Steel        | FILE PATH |
| Front Facia    | 1        | 3D Printed - ABS | FILE PATH |
| Rear Facia     | 1        | 3D Printed - ABS | FILE PATH |

### Hardware:
| Part                 | Quantity | Notes                            | Link                                             |
| -------------------- | -------- | -------------------------------- | ------------------------------------------------ |
| Heat set inserts     | 14       | 10 for facia, 4 for PCB securing | https://www.aliexpress.com/item/1005005920120561 |
| Low profile M4 - 5mm | 4        | PSU to bottom housing            | https://www.aliexpress.com/item/1005005070119421 |
| Low profile M3 - 6mm | 14       | 10 for facia, 4 for PCB securing | https://www.aliexpress.com/item/1005005070119421 |
| M3 Washers           | 4        | PCB mounting                     | https://www.aliexpress.com/item/1005003131496689 |

### PCB:
| Type      | Key                 | Value     | Quantity | Footprint         | Component       |
| --------- | ------------------- | --------- | -------- | ----------------- | --------------- |
| Capacitor | C1                  | 1000uF    | 1        | THT-CP_Radial_D10 |                 |
| Capacitor | C2,C5,C6,C7,C8,C9   | 470uF     | 6        | THT-CP_Radial_D10 |                 |
| Capacitor | C3                  | 1uF       | 1        | 1206              |                 |
| Capacitor | C4                  | 220nF     | 1        | 0603              |                 |
| Capacitor | C10,C11,C12,C13,C14 | 1uF       | 5        | 1206              |                 |
| Capacitor | C15,C16,C17,C18,C19 | .1uF      | 5        | 0603              |                 |
| Resistor  | R1                  | 4.7k      | 1        | 1206              |                 |
| Resistor  | R2                  | 47k       | 1        | 0603              |                 |
| Resistor  | R3                  | 100       | 1        | 0603              |                 |
| Resistor  | R4                  | 100k      | 1        | 0603              |                 |
| Diode     | D1,D2,D3,D4,D5      | SMBJ24A   | 5        | D_SMB             |                 |
| Diode     | D6                  | SMCJ24A   | 1        | D_SMC             |                 |
| Diode     | D7                  | 12v Zener | 1        | SOD-123           |                 |
| Fuse      | F1                  | 15A       | 1        | 2410              | 0451015.MRL     |
| Fuse      | F2,F3,F4F5,F6       | 3A        | 5        | 1206              |                 |
| Connector | J1,J2               |           | 2        |                   | Molex_5569-06A2 |
| Connector | J13,J14,J15,J16     |           | 4        |                   | 1x01_2.54mm     |
| Connector | J17,J18             |           | 2        |                   | 1x03_2.54mm     |
| Connector | J19,J20,J21,J22     |           | 4        |                   | 1x02_2.54mm     |
| Mosfet    | Q1                  |           | 1        | TO-263-2L         | NCEP40PT15D     |


