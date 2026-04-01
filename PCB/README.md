# PCB:
All variants use the same 2 layer 1.6mm thick PCB. This folder contains production files that can be uploaded to a PCB service for manufacturing, JLCPCB is my go-to. PCB assembly is recommended unless you have capability to do SMD soldering with either a hot air station or reflow oven.
There is currently no option for a through-hole variant because the tranistor does not come in a TH package.


**Parameters for PCB manufacturing:**
- 2 Oz copper trace weight - This is a must for current rating
- 1.6mm PCB thickness

<br>

### PCB Notes:
- You can use either an LM2596S or and MP1584EN. Just move the mounting headers to the corresponding holes.
- Connectors J19, J20, J21, J22 are optional. Either used for additional power output, or testing.
- After assembly, set fan header output voltage **before** plugging any fans in.

<br>

### Buck Converter:
To power the 40mm chassis fans the main 24V rail needs to be stepped down to 12V. This can be done with either an LM2596S or MP1584EN, on the PCB there's header holes and labels for both. The LM2596S is much more popular, but the MP1584EN is newer and has less EMC. MP1584EN comes in multiple variants, **make sure to get the variable one so you're able to tune the fan voltage**.

<p float="center">
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/General/LM2596S.png" width="40%" /> 
  <img src="https://github.com/Shrike-Lab/MiniLab-PSU/blob/main/Images/General/MP1584EN.png" width="40%" /> 
</p>

### Wiring:
There are two harnesses per set of internal electronics, one for main power and one for the button. The drawings can be found [here](https://github.com/Shrike-Lab/MiniLab-PSU/tree/main/ASSEMBLY/DRAWINGS/Electrial).

| Part   | Connection | Link |
| Ring spade | 24V harness |


<br>

## PCB Component BOM:

| Type      | Key                  | Value     | Footprint         | Quantity | Component       | Commment         |
| --------- | -------------------- | --------- | ----------------- | -------- | --------------- | ---------------- |
| Capacitor | C1,C2,C5,C6,C7,C8,C9 | 470uF     | THT-CP_Radial_D10 | 6        | -               | -                |
| Capacitor | C3                   | 1uF       | 1206              | 1        | -               | -                |
| Capacitor | C4                   | 220nF     | 0603              | 1        | -               | -                |
| Capacitor | C10,C11,C12,C13,C14  | 1uF       | 1206              | 5        | -               | -                |
| Capacitor | C15,C16,C17,C18,C19  | .1uF      | 0603              | 5        | -               | -                |
| Resistor  | R1                   | 4.7k      | 1206              | 1        | -               | -                |
| Resistor  | R2                   | 47k       | 0603              | 1        | -               | -                |
| Resistor  | R3                   | 100       | 0603              | 1        | -               | -                |
| Resistor  | R4                   | 100k      | 0603              | 1        | -               | -                |
| Diode     | D1,D2,D3,D4,D5       | SMBJ26A   | D_SMB             | 5        | -               | -                |
| Diode     | D6                   | SMCJ26A   | D_SMC             | 1        | -               | -                |
| Diode     | D7                   |     Zener | SOD-123           | 1        | BZT52C12        | -                |
| Fuse      | F1                   | 15A       | 2410              | 1        | 0451020.MRL     | -                |
| Fuse      | F2,F3,F4F5,F6        | 3A        | 1206              | 5        | 1206FA-4A       | -                |
| Connector | J1,J2                | -         | Molex_5569-06A2   | 2        | Molex_5569-06A2 | Power and button |
| Connector | J13,J14,J15,J16      | -         | 1x01_2.54mm       | 4        | 1x01_2.54mm     | Buck converter   |
| Connector | J17,J18              | -         | Molex_2272031     | 2        | Molex_2272031   | Fans             |
| Connector | J19,J21,J22          | -         | 1x02_2.54mm       | 3        | 1x02_2.54mm     | Debug            |
| Connector | J20                  | -         | JST_PH-K_1x02     | 1        | JST_PH-K_1x02   | PSU sense        |
| Mosfet    | Q1                   | -         | TO-263-2L         | 1        | NCEP40PT15D     | -                |
