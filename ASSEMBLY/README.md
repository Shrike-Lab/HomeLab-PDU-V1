# Assembly:
This section contains the bill of materials for each variant, as well as renders and exploded views of the sub-assemblies.

**All variants contain the following components:**

| Component          | Quantity | Link/Location | Source |
| ------------------ | -------- | ------------- | ------ |
| PDU PCB Ver 1.0    | 1        |               | Shrikelab kit or via PCB manufacturing service|
| USB-C 65W PD Board | 5        |               | Shrikelab kit or via online ( |
| Heatsink           | 5        |               |        |
| Buck Converter     | 1        |               |        |
| 16mm Button        | 1        |               |        |
| Button harness     | 1        |               | Comes with button |
| Power harness      | 1        |                |        |


<br>

## Sub-Assemblies:
There are two assemblies that are shared between the variants using a sheet metal housing.

<br>

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
| M3 Low Profile Bolt | 6       |               |        |
| M3 Plastic Washer  | 4        |               |        |

<br>

### IEC Plug:
Due to the extra depth allowed on full racks, all 19" variants use the IEC plug sub-assembly to allow for a detachable cable.
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/General/IEC-Bracket.png" width="45%" /> 
</p>

| Component          | Quantity | Link/Location |
| ------------------ | -------- | ------------- |
| IEC Plug           | 1        | [Digikey part link](https://www.digikey.com/en/products/detail/adam-tech/IEC-GS-1-100/9831135) |
| IEC Bracket        | 1        | [STL](https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/ASSEMBLY/CAD/Universal/IEC_Bracket.stl) |
| M3 Insert          | 4        |               |
| M3 Cap Head Bolt - 5mm  | 4   |               |

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



<br>

## 10 Inch - 3D Printed - Unibody:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/10in-Uni/10in-Uni-B.png" width="50%" /> 
</p>

#### Housing
| Item       | File Name          | Material           | Quantity | Link/Location |
| ---------- | ------------------ | ------------------ | -------- | ------------- |
| Body       | 10in_Uni-Body.stl  | 3D Print (ABS/ASA) | 1        |               |
| Tray       | 10in_Uni-Tray.stl  | 3D Print (ABS/ASA) | 1        |               |
| Side Panel | 10in_Uni-SidePanel | 3D Print (ABS/ASA) | 1        |               |

#### Hardware

<br>

## 10 Inch - 3D Printed - Modular:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/10in-Mod/10in-Mod-B.png" width="50%" /> 
</p>

#### Housing
| Item     | File Name             | Material           | Quantity | Link/Location |
| -------- | --------------------- | ------------------ | -------- | ------------- |
| Front    | 10in_Mod-Front.stl    | 3D Print (ABS/ASA) | 1        |               |
| Rear     | 10in_Mod-Rear.stl     | 3D Print (ABS/ASA) | 1        |               |
| Left     | 10in_Mod-Left.stl     | 3D Print (ABS/ASA) | 1        |               |
| Right    | 10in_Mod-Right.stl    | 3D Print (ABS/ASA) | 1        |               |
| Middle   | 10in_Mod-Middle.stl   | 3D Print (ABS/ASA) | 1        |               |
| Top_1    | 10in_Mod-Top_1.stl    | 3D Print (ABS/ASA) | 1        |               |
| Top_2    | 10in_Mod-Top_2.stl    | 3D Print (ABS/ASA) | 1        |               |
| Bottom_1 | 10in_Mod-Bottom_1.stl | 3D Print (ABS/ASA) | 1        |               |
| Bottom_2 | 10in_Mod-Bottom_2.stl | 3D Print (ABS/ASA) | 1        |               |

#### Hardware

<br>

## 10 Inch - Dual:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/10in-Dual/10in-Dual-B.png" width="50%" /> 
</p>

#### Housing

#### Hardware

<br>

## 19 Inch - Single:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/19in-Single/19in-Single-B.png" width="50%" /> 
</p>

#### Housing
[Link to the file location](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/CAD/19in_Single)
| Item    | File Name               | Material           | Quantity |
| ------- | ----------------------- | ------------------ | -------- |
| Tray    | 19in_Single-Tray.stp    | Sheel Metal        | 1        |
| Lid     | 19in_Single-Lid.stp     | Sheel Metal        | 1        |
| Front-1 | 19in_Single-Front_1.stl | 3D Print (ABS/ASA) | 1        |
| Front-2 | 19in_Single-Front_2.stl | 3D Print (ABS/ASA) | 1        |
| Back-1  | 19in_Single-Back_1.stl  | 3D Print (ABS/ASA) | 1        |
| Back-2  | 19in_Single-Back_2.stl  | 3D Print (ABS/ASA) | 1        |
| Divider | 19in_Single-Divider.stl | 3D Print (ABS/ASA) | 1        |


#### Hardware

<br>

## 19 Inch - Dual:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/19in-Dual/19in-Dual-B.png" width="50%" /> 
</p>

#### Housing

#### Hardware

<br>

## 19 Inch - SBS:
<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/19in-SBS/19in-SBS-B.png" width="50%" /> 
</p>

#### Housing

#### Hardware
