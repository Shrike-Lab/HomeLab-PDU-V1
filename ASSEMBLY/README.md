# Assembly:
This section contains the bill of materials for each variant, as well as renders and exploded views of the sub-assemblies.

- All trays mount to the racks with M5 hardware
- For 3D printing all files have been exported as an STL
- Blank parts have been exported as an STP to help editing
- Metal parts are exported as an STP
- As the metal housing lids require tapping, there is an engineering drawing in the [drawings folder](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/DRAWINGS/Hardware)
- Highly recommended to order extra insert and bolt hardware

**All variants contain the following components:**
| Component          |Link/Location | Source |
| ------------------ |------------- | ------ |
| PDU PCB Ver 1.0    | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/PCB/Minilab_PDU_V1.zip) | Shrikelab kit or buy PCB manufacturing service|
| 16mm Button        | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Electrial/Harness-Button.pdf)  | Shrikelab kit or buy online |
| Button harness     | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Electrial/Harness-Button.pdf)| Shrikelab kit or comes with button |
| Power harness      | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Electrial/Harness-Power.pdf) | Shrikelab kit or DIY|

### Drawings of components can be found here:
**Hardware:**
| Component          |Link/Location | Source |
| ------------------ |------------- | ------ |
| M3 Low Profile Bolt | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Hardware/Bolt-LowProfile.png) | - | 
| M3 Cap Head Bolt    | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Hardware/Bolt-CapHead.png) | - |
| M4 Low Profile Bolt | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Hardware/Bolt-LowProfile.png) | - |
| M4 Cap Head Bolt    | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Hardware/Bolt-CapHead.png) | - | 
| M3 Insert           | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Hardware/M3-Insert.pdf) | - |
**Electrical:**
| Component          |Link/Location | Source |
| ------------------ |------------- | ------ |
| MP1584EN | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Electrial/Buck_Board.png) | Online (Search term: MP1584EN Buck Converter)|
| Heatsink | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Electrial/Heatsink.png) | Online (Search term: 10x10x10mm Aluminium headsink) |
| PD Board | [Drawing](https://github.com/Shrike-Lab/HomeLab-PDU-V1/blob/main/ASSEMBLY/DRAWINGS/Electrial/PD_Board.png) | Online (Search term: DC to 65w fast charging USB-C board) |

<br>

## Sub-Assemblies:
There are two assemblies that are shared between the variants using a sheet metal housing.

### PCB Tray:
This PCB tray makes soldering the daughter boards easier, and allows the board to be installed and removed from the chassis easier.
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/General/PCB-Bracket.png" width="33%" /> 
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/General/PCB-Assembly.png" width="33%" />
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/General/PCB-SubAssembly.png" width="33%" />
</p>

| Component          | Quantity | Link/Location | Source |
| ------------------ | -------- | ------------- | ------ |
| PDU PCB Ver 1.0    | 1        | [STL](https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/PCB/1U_Minilab_PSU_V2.zip) |        |
| PCB Tray           | 1        | [STL](https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/ASSEMBLY/CAD/Universal/PCB_Tray.stl) |        |
| USB-C 65W PD Board | 5        | [Image](https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/ASSEMBLY/DRAWINGS/Electrial/Heatsink.png) |        |
| Heatsink           | 5        | [Drawing](https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/ASSEMBLY/DRAWINGS/Electrial/Heatsink.png) |        |
| PCB Reinforement   | 1        | [STL](https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/ASSEMBLY/CAD/Universal/Reinforcement_Bracket.stl) |        |
| Buck Converter     | 1        | [Image](https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/ASSEMBLY/DRAWINGS/Electrial/Buck_Board.png) |        |

<br>

### IEC Plug:
Due to the extra depth allowed on full racks, all 19" variants use the IEC plug sub-assembly to allow for a detachable cable.
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/General/IEC-Bracket.png" width="45%" /> 
</p>

| Component          | Quantity | Link/Location |
| ------------------ | -------- | ------------- |
| IEC Socket         | 1        | [Digikey part link](https://www.digikey.com/en/products/detail/adam-tech/IEC-GS-1-100/9831135) |
| IEC Bracket        | 1        | [STL](https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/ASSEMBLY/CAD/Universal/IEC_Bracket.stl) |
| IEC Spade Terminals | 5        | [Digikey part link](https://www.digikey.com/en/products/detail/molex/0190030011/279039) |
| IEC Fuse           | 1         | [Digikey part link](https://www.digikey.com/en/products/detail/littelfuse-inc/0232008-MXP/778029) |

<br>

### PCB Assembly Bracket:
If additional assitance is required during assembly, this bracket (Yellow) can be printed to hold the boards in place. It's then removed and replaced with the reinforcment bracket when the assembly is installed into a chassis.
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/General/PCB-Assembly-Bracket.png" width="45%" /> 
</p>

<br>

# Variant BOMs:

## 10 Inch - Single:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/10in-Single/10in-Single-B.png" width="50%" /> 
</p>

#### **Sub-Assemblies:**
| Assembly | Quantity |
| -------- | -------- |
| [PCB Tray](README.md#pcb-tray) | 1        |

#### **Housing:**
| Item  | File Name             | Material           | Quantity |
| ----- | --------------------- | ------------------ | -------- |
| Tray  | 10in_Single-Tray.stp  | Sheel Metal        | 1        |
| Lid   | 10in_Single-Lid.stp   | Sheel Metal        | 1        |
| Front | 10in_Single-Front.stl | 3D Print (ABS/ASA) | 1        |
| Back  | 10in_Single-Back.stl  | 3D Print (ABS/ASA) | 1        |
[Housing files are located here](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/CAD/10in_Single)

#### **Hardware**
| Item                | Length | Quantity |
| ------------------- | ------ | -------- |
| M3 Low Profile Bolt | 5mm    | 24       |
| M3 Low Profile Bolt | 8mm    | 2        |
| M3 Plastic Washer   | -      | 4        |
| M4 Low Profile Bolt | 5mm    | 4        |
| M3 Insert           | -      | 20       |

<br>

## 10 Inch - 3D Printed - Unibody:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/10in_3D_Unibody/10in_3D_Unibody-A.png" width="50%" /> 
</p>

#### **Sub-Assemblies:**
This variant contains no sub-assemblies still requires the [PCB reinforcement bracket](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/CAD/Universal/Reinforcement-Bracket.stl)

#### **Housing:**
| Item       | File Name          | Material           | Quantity |
| ---------- | ------------------ | ------------------ | -------- |
| Body       | 10in_Uni-Body.stl  | 3D Print (ABS/ASA) | 1        |
| Tray       | 10in_Uni-Tray.stl  | 3D Print (ABS/ASA) | 1        |
| Side Panel | 10in_Uni-SidePanel | 3D Print (ABS/ASA) | 1        |
[Housing files are located here](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/CAD/10in_3D_Unibody)

#### **Hardware**
| Item                | Length | Quantity |
| ------------------- | ------ | -------- |
| M3 Low Profile Bolt | 5mm    | 6        |
| M3 Low Profile Bolt | 8mm    | 2        |
| M3 Plastic Washer   | -      | 4        |
<br>

## 10 Inch - 3D Printed - Modular:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/10in_3D_Modular/10in_3D_Modular-B.png" width="50%" /> 
</p>

#### **Sub-Assemblies:**
This variant contains no sub-assemblies still requires the [PCB reinforcement bracket](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/CAD/Universal/Reinforcement-Bracket.stl)

#### **Housing:**
| Item     | File Name             | Material           | Quantity |
| -------- | --------------------- | ------------------ | -------- |
| Front    | 10in_Mod-Front.stl    | 3D Print (ABS/ASA) | 1        | 
| Rear     | 10in_Mod-Rear.stl     | 3D Print (ABS/ASA) | 1        |        
| Left     | 10in_Mod-Left.stl     | 3D Print (ABS/ASA) | 1        |     
| Right    | 10in_Mod-Right.stl    | 3D Print (ABS/ASA) | 1        |       
| Middle   | 10in_Mod-Middle.stl   | 3D Print (ABS/ASA) | 1        |     
| Top_1    | 10in_Mod-Top_1.stl    | 3D Print (ABS/ASA) | 1        |        
| Top_2    | 10in_Mod-Top_2.stl    | 3D Print (ABS/ASA) | 1        |       
| Bottom_1 | 10in_Mod-Bottom_1.stl | 3D Print (ABS/ASA) | 1        |         
| Bottom_2 | 10in_Mod-Bottom_2.stl | 3D Print (ABS/ASA) | 1        |    
[Housing files are located here](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/CAD/10in_3D_Modular)

#### **Hardware**
| Item                | Length | Quantity |
| ------------------- | ------ | -------- |
| M3 Cap Head Bolt    | 8mm    | 28       |
| M3 Cap Head Bolt    | 16mm   | 4        | 
| M3 Insert           | -      | 30       | 
| M4 Cap Head Bolt    | 5mm    | 7        |  
| M4 Low Profile Bolt | 3mm    | 1        |   
| M3 Low Profile Bolt | 5mm    | 2        |
| Plastic Washer      | -      | 2        |

<br>

## 10 Inch - Dual:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/10in-Dual/10in-Dual-B.png" width="50%" /> 
</p>

#### **Sub-Assemblies:**
| Assembly | Quantity |
| -------- | -------- |
| [PCB Tray](README.md#pcb-tray) | 2        |

#### **Housing:**
| Item  | File Name           | Material           | Quantity |
| ----- | ------------------- | ------------------ | -------- |
| Tray  | 10in_Dual-Tray.stp  | Sheel Metal        | 1        |
| Lid   | 10in_Dual-Lid.stp   | Sheel Metal        | 1        |
| Front | 10in_Dual-Front.stl | 3D Print (ABS/ASA) | 1        |
| Back  | 10in_Dual-Back.stl  | 3D Print (ABS/ASA) | 1        |
[Housing files are located here](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/CAD/10in_Dual)

#### **Hardware**
| Item                | Length | Quantity |
| ------------------- | ------ | -------- |
| M3 Low Profile Bolt | 5mm    | 32       |
| M3 Low Profile Bolt | 8mm    | 4        |
| M3 Plastic Washer   | -      | 8        |
| M3 Insert           | -      | 30       |

<br>

## 19 Inch - Single:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/19in-Single/19in-Single-B.png" width="50%" /> 
</p>

#### **Sub-Assemblies:**
| Assembly | Quantity |
| -------- | -------- |
| [PCB Tray](README.md#pcb-tray) | 1        |
| [IEC Plug](README.md#iec-plug) | 1        |

#### **Housing:**
| Item    | File Name               | Material           | Quantity |
| ------- | ----------------------- | ------------------ | -------- |
| Tray    | 19in_Single-Tray.stp    | Sheel Metal        | 1        |
| Lid     | 19in_Single-Lid.stp     | Sheel Metal        | 1        |
| Front-1 | 19in_Single-Front_1.stl | 3D Print (ABS/ASA) | 1        |
| Front-2 | 19in_Single-Front_2.stl | 3D Print (ABS/ASA) | 1        |
| Back-1  | 19in_Single-Back_1.stl  | 3D Print (ABS/ASA) | 1        |
| Back-2  | 19in_Single-Back_2.stl  | 3D Print (ABS/ASA) | 1        |
| Interal | 19in_Single-Internal.stl | 3D Print (ABS/ASA) | 1        |
| Divider | 19in_Single-Divider.stl | 3D Print (ABS/ASA) | 1        |

[Housing files are located here](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/CAD/19in_Single)

#### **Hardware**
| Item                | Length | Quantity |
| ------------------- | ------ | -------- |
| M3 Low Profile Bolt | 5mm    | 36       |
| M3 Plastic Washer   | -      | 4        |
| M3 Insert           | -      | 40       |
| M4 Low Profile Bolt | 5mm    | 4        |
| M3 Cap Head         | 8mm    | 10       |

<br>

## 19 Inch - Dual:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/19in-Dual/19in-Dual-B.png" width="50%" /> 
</p>

#### **Sub-Assemblies:**
| Assembly | Quantity |
| -------- | -------- |
| [PCB Tray](README.md#pcb-tray) | 2        |
| [IEC Plug](README.md#iec-plug) | 2        |

#### **Housing:**
| Item    | File Name             | Material           | Quantity |
| ------- | --------------------- | ------------------ | -------- |
| Tray    | 19in_Dual-Tray.stp    | Sheel Metal        | 1        |
| Lid     | 19in_Dual-Lid.stp     | Sheel Metal        | 1        |
| Front-1 | 19in_Dual-Front_1.stl | 3D Print (ABS/ASA) | 1        |
| Front-2 | 19in_Dual-Front_2.stl | 3D Print (ABS/ASA) | 1        |
| Back-1  | 19in_Dual-Back_1.stl  | 3D Print (ABS/ASA) | 1        |
| Back-2  | 19in_Dual-Back_2.stl  | 3D Print (ABS/ASA) | 1        |
| Divider | 19in_Dual-Divider.stl | 3D Print (ABS/ASA) | 3        |
[Housing files are located here](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/CAD/19in_Dual)

#### **Hardware**
| Item                | Length | Quantity |
| ------------------- | ------ | -------- | 
| M3 Low Profile Bolt | 5mm    | 42       |
| M3 Plastic Washer   | -      | 8        |
| M3 Insert           | -      | 48       |  
| M4 Low Profile Bolt | 5mm    | 14       |   
| M3 Cap Head         | 8mm    | 16       | 

<br>

## 19 Inch - Dual - SBS:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/19in-SBS/19in-SBS-B.png" width="50%" /> 
</p>

#### **Sub-Assemblies:**
| Assembly | Quantity |
| -------- | -------- |
| [PCB Tray](README.md#pcb-tray) | 2        |
| [IEC Plug](README.md#iec-plug) | 2        |

#### **Housing:**
| Item    | File Name                 | Material           | Quantity |
| ------- | ------------------------- | ------------------ | -------- |
| Tray    | 19in_Dual_SBS-Tray.stp    | Sheel Metal        | 1        |
| Lid     | 19in_Dual_SBS-Lid.stp     | Sheel Metal        | 1        |
| Front-1 | 19in_Dual_SBS-Front_1.stl  | 3D Print (ABS/ASA) | 1        |
| Front-2 | 19in_Dual_SBS-Front_2.stl | 3D Print (ABS/ASA) | 1        |
| Back-1  | 19in_Dual_SBS-Back_1.stl  | 3D Print (ABS/ASA) | 1        |
| Back-2  | 19in_Dual_SBS-Back_2.stl  | 3D Print (ABS/ASA) | 1        |
| Divider | 19in_Dual_SBS-Divider.stl | 3D Print (ABS/ASA) | 2        |
[Housing files are located here](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/CAD/19in_Dual_SBS)

#### **Hardware**
| Item                | Length | Quantity |
| ------------------- | ------ | -------- | 
| M3 Low Profile Bolt | 5mm    | 42       |
| M3 Plastic Washer   | -      | 8        | 
| M3 Insert           | -      | 48       |   
| M4 Low Profile Bolt | 5mm    | 12       |
| M3 Cap Head         | 8mm    | 16       |
