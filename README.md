# **MiniLab PSU** - 5 Port Homelab USB-C PD Power Supply
MiniLab PSU is a power delivery solution for micro PC clusters and homelabs that fits in a 1U 10-inch rack. It's built around a 300W Meanwell PSU featuring 5 USB-C power delivery ports and active cooling. 

### Kits/PCBs Coming Soon?: [Shrikelab.co](Shrikelab.co) ###

<p float="left">
  <img src="https://github.com/joshr120/PD-Stepper/assets/120012174/70c9a55e-43c8-42c1-9540-dcf600ba0539" width="48%" />
  <img src="https://github.com/user-attachments/assets/1d594941-e84c-44e8-9f2c-273dbbe360d2" width="48%" /> 
</p>

<p float="left">
  <img src="https://github.com/user-attachments/assets/c0fa1ab4-82ac-4a1e-87f9-4fefa437d6c6" width="48%" /> 
  <img src="https://github.com/joshr120/PD-Stepper/assets/120012174/65909313-01d8-4cda-bbda-bfbe47be087a" width="48%" />
</p>


Mini and micro labs are a great solution for homelabbing, but the power delivery options are often bulky and hard to manage due to the need for an individual power brick per computer.
This project addressess this by consolidating power delivery for up to five 65W micro PCs into a single unit that fits in a standard 1U 10-inch rack mount. This differs from a conventional multi-port USB PD hub by not needing to re-negotiate any power delivery voltages when a unit is turned off or unpluggded, or when the power load across ports changes drastically. Also the packing is designed specifially with rack mounting in mind, with active cooling and power switching.

Full Video and build guide [here](youtube.com)



## Bill of Materials:
### Chassis:
| Part                 | Quantity | Notes                            | Link                                             |
| -------------------- | ----- | -------------------------------- | ------------------------------------------------ |
| Bottom Housing       | 1     | 1mm Steel                        | FILE PATH                                        |
| Lid                  | 1     | 1mm Steel                        | FILE PATH                                        |
| Front Facia          | 1     | 3D Printed - ABS                 | FILE PATH                                        |
| Rear Facia           | 1     | 3D Printed - ABS                 | FILE PATH                                        |

### Hardware:
| Part                 | Quantity | Notes                            | Link                                             |
| -------------------- | ----- | -------------------------------- | ------------------------------------------------ |
| Heat set inserts     | 14    | 10 for facia, 4 for PCB securing | https://www.aliexpress.com/item/1005005920120561 |
| Low profile M4 - 5mm | 4     | PSU to bottom housing            | https://www.aliexpress.com/item/1005005070119421 |
| Low profile M3 - 6mm | 14    | 10 for facia, 4 for PCB securing | https://www.aliexpress.com/item/1005005070119421 |
| M3 Washers           | 4     |                                  | https://www.aliexpress.com/item/1005003131496689 |

### PCB:
| Type      | Key                 | Value     | Footprint         | Quantity | Component       |
| --------- | ------------------- | --------- | ----------------- | -------- | --------------- |
| Capacitor | C1                  | 1000uF    | THT-CP_Radial_D10 | 1        |                 |
| Capacitor | C2,C5,C6,C7,C8,C9   | 470uF     | THT-CP_Radial_D10 | 6        |                 |
| Capacitor | C3                  | 1uF       | 1206              | 1        |                 |
| Capacitor | C4                  | 220nF     | 0603              | 1        |                 |
| Capacitor | C10,C11,C12,C13,C14 | 1uF       | 1206              | 5        |                 |
| Capacitor | C15,C16,C17,C18,C19 | .1uF      | 0603              | 5        |                 |
| Resistor  | R1                  | 4.7k      | 1206              | 1        |                 |
| Resistor  | R2                  | 47k       | 0603              | 1        |                 |
| Resistor  | R3                  | 100       | 0603              | 1        |                 |
| Resistor  | R4                  | 100k      | 0603              | 1        |                 |
| Diode     | D1,D2,D3,D4,D5      | SMBJ24A   | D_SMB             | 5        |                 |
| Diode     | D6                  | SMCJ24A   | D_SMC             | 1        |                 |
| Diode     | D7                  | 12v Zener | SOD-123           | 1        |                 |
| Fuse      | F1                  | 15A       | 2410              | 1        | 0451015.MRL     |
| Fuse      | F2,F3,F4F5,F6       | 3A        | 1206              | 5        |                 |
| Connector | J1,J2               |           |                   | 2        | Molex_5569-06A2 |
| Connector | J13,J14,J15,J16     |           |                   | 4        | 1x01_2.54mm     |
| Connector | J17,J18             |           |                   | 2        | 1x03_2.54mm     |
| Connector | J19,J20,J21,J22     |           |                   | 4        | 1x02_2.54mm     |
| Mosfet    | Q1                  |           | TO-263-2L         | 1        | NCEP40PT15D     |

