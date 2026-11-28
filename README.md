# M7880H Intercom Module · Communication

Ward-Beck Systems M7880H, 1994|27. Wiki page: [M7880H on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.COMMUNICATION.M7880H-Intercom-Module/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 4 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 2 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 7 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 2 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 2 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Circuit description

From [1994 - M7880H - M7880H - 14-246-02-003 - COMPONENT LAYOUT.wp](MANUALS/1994%20-%20M7880H%20-%20M7880H%20-%2014-246-02-003%20-%20COMPONENT%20LAYOUT.wp) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

2 Parts List 2-1 to 2-23 Drawings:

Schematic B 14-246-02-003 Component Layout B 14-246-06-003

B SA14-247H Logic Assembly

1 Circuit Description 1-12 Parts List 2-1 to 2-33 Drawings:

Schematic B 14-247-02-002 Component Layout B 14-247-06-002

**SECTION PAGE**

C SA14-270G Controller Assembly

1 Circuit Description 1-1 to 1-22 Parts List 2-1 to 2-53 Drawings:

Schematic B 14-270-02-006/1 Schematic B 14-270-02-006/2 Component Layout B 14-270-06-006

D SA14-271 Audio Assembly

1 Circuit Description 1-1 to 1-32 Parts List 2-1 to 2-11 3 Drawings:

Schematic B 14-271-02-001 Component Layout B 14-271-06-001

E Lambda Power Supply

1 General (LVT-39-Series) 1-1 to 1-22 Parts List 2-1 A. Preamplifier Section:

Gain:

Dynamic Mic Input: 78 dB to 48 dB +/-1 dB (Transducer Gain +8 dBm operation). Headset Mic Input: 48 dB to 18 dB +/-1 dB (Transducer Gain +8 dBm operation). External Line Input: 18 dB to -2 dB +/-1 dB (Bridging Gain +8 dBm operation).

Frequency Response: +/-1 dB 100 Hz to 5 kHz

Noise: (measured over a 20 Hz to 20 kHz band­width).

Dynamic Mic Input: -118 dBm EIN at maximum sensitivity. -120 dBm typical.

Headset Mic Input: 50 to 65 dB below +8 dBm over the 30 dB sensitivity range. External Line Input: 65 to 75 dB below +8 dBm over the 30 dB sen­sitivity range.

Harmonic Distortion:

Less than 0.25% 100 Hz to 5 kHz at limiting threshold (+12 dBm output +8 dBm operation). Less than 0.25% 100 Hz to 5 kHz at +22 dBm output level with limiter off. Less than 1% 100 Hz to 5 kHz with 20 dB of limiting and &quot;normal&quot; release time.

Input Levels:

Dynamic Mic: -70 dBm to -40 dBm nominal.

Headset Mic: -40 dBm to -10 dBm nominal.

External Line: -10 dBm to +10 dBm nominal.

Input Impedances:

Dynamic Mic: 600 ohms or greater unbalanced.

Headset Mic: 600 ohm or greater unbalanced.

External Line: 10000 ohms or greater balanced.

Source Impedance:

Dynamic and Headset Mics: 150 ohms balanced/unbalanced. External Line: 600 ohms or less balanced.

Output Level: +8 dBm nominal (+4 dBm optional).

+24 dBu maximum 5K ohm load.

+22 dBm maximum 600 ohm load.

Output Impedance: 60 ohms, actively balanced.

Load Impedance: 600 ohms, or greater balanced.

Limiter:

Range: 30 dB.

Slope: 3:1 nominal at threshold, approaching 10:1 at 20 dB of limiting. Threshold: Set 4 to 5 dB above nominal operating level.(results ina constant output of +4 or +8 VU under dynamic con­ditions). Attack Time: 10 milliseconds nominal.

Release Time: 3 seconds &quot;normal&quot;.

1.5 seconds &quot;fast&quot;.

B. Speaker/Headset Amplifier:

Gain:

to Speaker Output: +25 dB +/-1 dB (bridging gain).

to Headset Output: +10 dB +/-1 dB (bridging gain).

Frequency Response: +/-1 dB 50 Hz to 8 kHz.

+/-0.5 dB 100 Hz to 5 kHz.

Noise: (measured over a 20 Hz to 20 kHz band­width).

Speaker Output: 80 dB below 3 watts.

Headset Output: 70 dB below +8 dBm.

Harmonic Distortion: Less than 0.25% 100 Hz to 5 kHz at 3 watts output for the speaker amplifier into an 8 ohm load and to +22 dBm output into 600 ohms for the headset amplifier.

Input Level: +8 dBm nominal (+4 dBm optional), +24 dBu maximum. (from matrix).

Input Impedance: 10,000 ohms or greater balanced.

Source Impedance: 600 ohms or less balanced.

Output Levels:

Speaker Output: 200 mW nominal 3 watts maximum.

Headset Output: +8 dBm nominal (+4 dBm optional) +22 dBm maximum.

Output Impedances:

Speaker Output: Less than 1 ohm unbalanced.

Headset Output: 60 ohms actively balanced.

Load Impedances:

Speaker Output: 8 ohms unbalanced.

Headset Output: 600 ohms balanced or greater.

C. Control Functions:

Programmable External Inputs:

Standard TTL Logic Levels: +5 volts max.

+0.5 volts min.

Programmable External Outputs:

Open Collector Drive: Source voltage 25 volts max.

Sink current 25 mA max.

External Data and Address Lines:

Standard TTL Logic Levels: +5 volts max.

+0.5 volts min.

Power Requirements: 115/230V AC 50 to 60 Hz 50 VA.

Ambient Temperature: 0 to 50 degrees Celsius.

Dimensions: 19.00&quot; wide x 3.46&quot; high x 9.75 deep.

(482 mm x 88 mm x 248 mm)

Weight: 11 lbs (5 kg).

SA14-270G Controller Assembly WBS SA14-270G

SA14-271 Audio Assembly &quot; SA14-271

SA14-246H Key Switch Assembly &quot; SA14-246H

SA14-247H Logic Assembly &quot; SA14-247H

P/S 1 Power Supply Lambda LVT-39E-144

LF1 Line Filter Curtis F3000AA06

CORD ACCord Belden 17237

F1 Fuse, 1.5 Amp S.B. Buss MDL 1.5

MIC Microphone Shure VR300

R2 Potentiometer 5K 'A' Clarostat WBS 10-049

SPKR Speaker CTS 3A2479

247J6 Connector, 16S (8x2) Socket 3M 3452-6000

**271J2 &quot; &quot; &quot; &quot;**

246J6 Connector, 12 Pin Socket Panduit CE100F26-12 247J8 &quot; 3 Pin Socket &quot; CE100F22-3

270J1 &quot; 3 Pin Socket &quot; CE100F22-3 270J7 &quot; 12 Pin Socket &quot; CE100F26-12

271J3 &quot; 12 Pin Socket &quot; &quot; 271J5 &quot; 12 Pin Socket &quot; &quot; 271J6 &quot; 6 Pin Socket &quot; CE100F22-6

271J4 Connector, Mini Housing Berg 65039-033 Connector Pins &quot; PV-47712

271J8 Connector, Mini Housing &quot; 65039-033 Connector Pins &quot; PV-47712

J1 Connector, 9 Pin Female TEEE NEZ 9S-E

J2 Connector, 15 Pin Female &quot; NAZ 15S-E (Supplied upon request)

J6 Connector, 25 Pin Female TEEE NBZ 25S-E (Supplied upon request)

**USED ON DESCRIPTION MFG MFG PART NUMBER**

Cable 16 Conductor Ribbon Cable 3M 3365/16 T&amp;B/Ansley 171-16 Cord ACCord Strain Relief Heyco 5P4

F1 Fuseholder Buss HKP

MIC Microphone Gooseneck 7&quot; (180mm) Neutrik GN18 Gooseneck Insulating Washer (2per) HH Smith 2667 &quot; Mic Adapter WBS A9794 &quot; Panel Adapter &quot; A9795 &quot; Panel Adapter Nut &quot; 3/8-24 NF HEX NUT

R2 Knob, Black 10mm Elma 021-2225 Cap, Black 10mm &quot; 040-1625

247J8 Cover, 3 Position End Panduit EC100F-3

270J1 &quot; 3 Position End &quot; EC100F-3 270J7 &quot; 12 Position End &quot; EC100F-12 271J3 &quot; 12 Position End &quot; EC100F-12 271J5 &quot; 12 Position End &quot; EC100F-12 271J6 &quot; 6 Position End &quot; EC100F-6

246J6 Cover, 12 Position End Panduit EC100F-12

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1cQEOMt_AydrUDUui29N9qAHrcHKVFe0U/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1cQEOMt_AydrUDUui29N9qAHrcHKVFe0U" width="240" alt="1994 - M7880H - DOC - 940294-01-001 - PER CUSTOMER REVISION.jpg"></a><br><sub>1994|27 · DOC - 940294-01-001 - PER CUSTOMER REVISION · <a href="SCHEMATICS/1994%20-%20M7880H%20-%20DOC%20-%20940294-01-001%20-%20PER%20CUSTOMER%20REVISION%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1994 - M7880H - DOC - 940294-01-001 - PER CUSTOMER REVISION.kicad_sch](KICAD/1994%20-%20M7880H%20-%20DOC%20-%20940294-01-001%20-%20PER%20CUSTOMER%20REVISION.kicad_sch)
- [M7880H.kicad_sym](KICAD/M7880H.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
