<div align="center">
  <img alt="Shrike Lab logo"
       src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/Logo/ShrikeLabCo_Footer_W_HiRes.png?raw=true"
       height="100">
  
  [Website](https://www.shrikelab.co) | [YouTube](https://www.youtube.com/@ShrikeLab)
  
</div>

# **ShrikeLab PSU V1** - 5 & 10 port USB-C PSUs for 10" and 19" racks
These PSUs are power delivery solutions for micro PC clusters and homelabs that suits both 10" and 19" racks. All varients are built around an off-the-shelf PSU featuring either 5 or 10 USB-C power delivery ports in either sheet metal, or 3D printed enclosures. 

<div align="center">
  <a
    href="https://www.Shrikelab.co" title="Kits and PCBs available now!">Kits and PCBs available now!
  </a>  
</div>

---

<p float="left">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/Logo/All_Iso_Render.png" width="100%" /> 
</p>

<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/Logo/All_Front.png" width="48%" /> 
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/Logo/All_Rear.png" width="48%" /> 
</p>


Mini and micro labs are a great solution for homelabbing, but the power delivery options are often bulky and hard to manage due to the need for an individual power brick per computer.
This project addressess this by consolidating power delivery for up to five 65W micro PCs into a single unit that fits in a standard 1U 10-inch rack mount. This differs from a conventional multi-port USB PD hub by not needing to re-negotiate any power delivery voltages when a unit is turned off or unpluggded, or when the power load across ports changes drastically. Also the packing is designed specifially with rack mounting in mind, with active cooling and power switching.

**Showcase & design video** [here](https://www.youtube.com/watch?v=8tTG0TBM7ts)

**Follow-up and testing video** [here](youtube.com)

### Features:
- Both 19" and 10" variants
- Up to 10 x 65W USB-C outputs
- 1U Height
- Active cooling
- Sheet metal housing or fully 3D printable



# Assembly:
## Components

| Part        | Quantity | Notes                                  | Link                                                                            |
| ----------- | -------- | -------------------------------------- | ------------------------------------------------------------------------------- |
| HRP-300-24  | 1        | Meanwell                               | https://www.digikey.com/en/products/detail/mean-well-usa-inc/HRP-300-24/7704305 |
| 16mm Button | 1        | Latching 24v                           | -                                                                               |
| 40mm Fan    | 2        | One unless the PSU fan is replaced too | -                                                                               |
| LM2596      | 1        | Buck converter                         | https://www.aliexpress.com/item/1005010001439374                                |
| Heatsinks   | 7        | 10mmx10mm                              | https://www.aliexpress.com/item/10000038519525                                  |
| PD Boards   | 5        |                                        | https://www.aliexpress.com/item/1005007016771773                                |


# Variants:

## 10 Inch - Single:
<p float="left">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/10in_Single/10in_Single-Iso.png" width="60%" /> 
</p>
**Housing:*

| Part                  | Source   | Quant | Link                                  |
| --------------------- | -------- | ----- | ------------------------------------- |
| 10in_Single-Tray.stp  | Metal    | 1     | CAD/10in_Single/10in_Single-Tray.stl  |
| 10in_Single-Lid.stp   | Metal    | 1     | CAD/10in_Single/10in_Single-Lid.stl   |
| 10in_Single-Front.stl | 3D Print | 1     | CAD/10in_Single/10in_Single-Front.stl |
| 10in_Single-Rear.stl  | 3D Print | 1     | CAD/10in_Single/10in_Single-Rear.stl  |
| PCB_Tray.stl          | 3D Print | 1     | CAD/Universal/PCB_Tray.stl            |

**Hardware:**
| Part | Source | Count | Link |
| ---- | ------ | ----- | ---- |
|      |        |       |      |


## 10 Inch - 3D Printed:
<p float="left">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/10in_3D/10in_3D-Iso.png" width="60%" /> 
</p>

**Housing:**
| Part                 | Source   | Quant | Link                             |
| -------------------- | -------- | ----- | -------------------------------- |
| 10in_3D-Bottom_1.stl | 3D Print | 1     | CAD/10in_3D/10in_3D-Bottom_1.stl |
| 10in_3D-Bottom_2.stl | 3D Print | 1     | CAD/10in_3D/10in_3D-Bottom_2.stl |
| 10in_3D-Front.stl    | 3D Print | 1     | CAD/10in_3D/10in_3D-Front.stl    |
| 10in_3D-Left.stl     | 3D Print | 1     | CAD/10in_3D/10in_3D-Left.stl     |
| 10in_3D-Mid.stl      | 3D Print | 1     | CAD/10in_3D/10in_3D-Mid.stl      |
| 10in_3D-Rear.stl     | 3D Print | 1     | CAD/10in_3D/10in_3D-Rear.stl     |
| 10in_3D-Right.stl    | 3D Print | 1     | CAD/10in_3D/10in_3D-Right.stl    |
| 10in_3D-Top_1.stl    | 3D Print | 1     | CAD/10in_3D/10in_3D-Top_1.stl    |
| 10in_3D-Top_2.stl    | 3D Print | 1     | CAD/10in_3D/10in_3D-Top_2.stl    |

**Hardware:**
| Part               | Source | Quant | Link |
| ------------------ | ------ | ----- | ---- |
| M3 Threaded Insert |        | TBD   |      |
| M4 10MM Bolt       |        | TBD   |      |
| M3 12mm Bolt       |        | TBD   |      |


### 10 Inch - Dual External:
<p float="left">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/10in_Dual/10in_Dual-Iso.png" width="60%" /> 
</p>

**Housing:**
| Part                | Source   | Quant | Link                              |
| ------------------- | -------- | ----- | --------------------------------- |
| 10in_Dual-Tray.stp  | Metal    | 1     | CAD/10in_Dual/10in_Dual-Tray.stp  |
| 10in_Dual-Lid.stp   | Metal    | 1     | CAD/10in_Dual/10in_Dual-Lid.stp   |
| 10in_Dual-Front.stl | 3D Print | 1     | CAD/10in_Dual/10in_Dual-Front.stl |
| 10in_Dual-Rear.stl  | 3D Print | 1     | CAD/10in_Dual/10in_Dual-Rear.stl  |
| PCB_Tray.stl        | 3D Print | 2     | CAD/Universal/PCB_Tray.stl        |

**Hardware:**
| Part | Source | Count | Link |
| ---- | ------ | ----- | ---- |
|      |        |       |      |
|      |        |       |      |
|      |        |       |      |


### 19 Inch - Single:
<p float="left">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/19in_Single/19in_Single-Iso.png" width="60%" /> 
</p>

**Housing:**
| Part                    | Source   | Count | Link                                    |
| ----------------------- | -------- | ----- | --------------------------------------- |
| 19in_Single-Tray.stp    | Metal    | 1     | CAD/19in_SIngle/19in_Single-Tray.stp    |
| 19in_Single-Lid.stp     | Metal    | 1     | CAD/19in_Single/19in_Single-Lid.stp     |
| 19in_Single-Front_1.stl | 3D Print | 1     | CAD/19in_Single/19in_Single-Front_1.stl |
| 19in_Single-Front_2.stl | 3D Print | 1     | CAD/19in_Single/19in_Single-Front_2.stl |
| 19in_Single-Rear_1.stl  | 3D Print | 1     | CAD/19in_Single/19in_Single-Rear_1.stl  |
| 19in_Single-Rear_2.stl  | 3D Print | 1     | CAD/19in_Single/19in_Single-Rear_2.stl  |
| 19in_Single-Divider.stl | 3D Print | 1     | CAD/19in_SIngle/19in_Single-Divider.stl |
| IEC_Bracket.stl         | 3D Print | 1     | CAD/Universal/IEC_Bracket.stl           |
| PCB_Tray.stl            | 3D Print | 1     | CAD/Universal/PCB_Tray.stl              |

**Hardware:**
| Part | Source | Count | Link |
| ---- | ------ | ----- | ---- |
|      |        |       |      |
|      |        |       |      |
|      |        |       |      |


### 19 Inch - Dual:
<p float="left">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/IMG/19in_Dual/19in_Dual-Iso.png" width="60%" /> 
</p>

**Housing:**
| Part                  | Source   | Count | Link                                |
| --------------------- | -------- | ----- | ----------------------------------- |
| 19in_Dual-Tray.stp    | Metal    | 1     | CAD/19in_Dual/19in_Dual-Tray.stp    |
| 19in_Dual-Lid.stp     | Metal    | 1     | CAD/19in_Dual/19in_Dual-Lid.stp     |
| 19in_Dual-Front_1.stl | 3D Print | 1     | CAD/19in_Dual/19in_Dual-Front_1.stl |
| 19in_Dual-Front_2.stl | 3D Print | 1     | CAD/19in_Dual/19in_Dual-Front_2.stl |
| 19in_Dual-Rear_1.stl  | 3D Print | 1     | CAD/19in_Dual/19in_Dual-Rear_1.stl  |
| 19in_Dual-Rear_2.stl  | 3D Print | 1     | CAD/19in_Dual/19in_Dual-Rear_2.stl  |
| IEC_Bracket.stl       | 3D Print | 2     | CAD/Universal/IEC_Bracket.stl       |
| PCB_Tray.stl          | 3D Print | 2     | CAD/Universal/PCB_Tray.stl          |

**Hardware:**
| Part | Source | Count | Link |
| ---- | ------ | ----- | ---- |
|      |        |       |      |
|      |        |       |      |
|      |        |       |      |


# PCB:
All variants use the same 2 layer 1.6mm PCB. 'PCB' folder contains production files that can be uploaded to a PCB service like JLCPCB or PCBway. PCB assembly is recommended unless you have capability to do reflow, or hot air soldering.
There is currently no option for a through-hole variant because the tranistor does not come in that package.

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












