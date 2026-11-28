# M463 Submaster Module · Summing

Ward-Beck Systems M463, 1972|5. Wiki page: [M463 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M463.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 200 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 18 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 16 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 371 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 3 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 46 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 90 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [6 topics](FORUM.md): what owners and technicians said about it.

## Circuit description

From [1974 - M463 - Submaster Module (2).pdf](MANUALS/1974%20-%20M463%20-%20Submaster%20Module%20(2).pdf) pages 4-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**14 46 3 SUBMASTER MODULE**

The M463 is a combination SUBMA STER/ EQUALIZER module. designed to accept combined or mixed feeds fro ll previously assigned mix ing channel inputs. As maybe required, &quot; the unit processes the mixed sign 4l, equalizes it and routes it to the appropriate points within the console system.

Input and Summing Amplifier The signal originating from the exte rn e t llIixi ng network is a flfll 1e d to the edge connector Pl, pins 1 4nd A and subsequently connects tot he summing current nodes of the 4-14 1 summing an pl 1 t t e r. to facilitate a e e ute testing. 4 direct input is provided on Pl. pins 17 and U.

EQUALIZER Sect ion The out put of the 4-141 summing a mpl i f teri s routed to one of the nor lllally closed contact s of the EQUALIZER INSERT switch SIl13 t o allow bn lSsing of the equalizer. Additionally. the 4-141 output is fed to Zl. the first of four cascaded s umm1ng ampl Hiers Zl through Z4.

Zl through Z4 serve e s mix ing and isolation amplifiers. They are used to.. r x the flrim4ry input signal with a correction signal derived from the outputs of the 4-126 filter networks. resulting i n nfs 1ng or lowering the level of selected portions oft he a ud tc spectrum. Additionally, they iso late the fOte r networks from each otlie rand prevent tnt er-ac t ton between thee, resulting inaccurate and rep eatable equalizing performance. Tlie CUT/BOOST controls R21. R22 and R23 feed an f n-phe s e o r outof-phase proportional signal to the buffer amplifiers Z5, Z6 and Z8 respectively. The level of the signal fed to the buffers is dependent on the CUT/B OOST control setting with maxi lllum level occurring at either end of the potenti ometer. and a null setting at the potenti omete r mid -position. Full clockwise or full counterclockwise potent io meter settings wn l

result i n the maximum equal t ze t tun of +15 dB and -15 dB respect

ive l y.

WAR O - BeCKS YS TEMS L.T O.

**&quot;463 SUBMASTER MOO ULE**

The outputs of buffer IlIplffiers 25, 26 and 28 are routed to the 4-126 printed circuit baird whf ch contains three bandpass filters corresponding touch oft he three sections of the equal her. Each bandpus filter passes only I portion oft he slgnl l delivered to ft f r o~ the buffer, with the center frequency and band width deter.fned by the FREQUENCY, -Qand PEAK/SHElF controls.

HIGH FREQUENCY equal f zat f on is cont fnu ous l y I dj us t l ble frail 1.6 t o 25 kHz and Is controlled by Rl/R 2. R21 deter _ines the aacu n t of CUT o r BOO ST. A total range frO Il -15 to +15 dB 15 provided. Vittl SWll depressed the unit w111 produce a high frequency SHELVING Characteristic. When SW l l i s released, both positive or negat h e PEAKING can be obt a1ne d. The Q control RJ is effe c the only with SWll int he PEAKING mode and covers a Q-fac tor range of 2 ~ o 10.

Ttle MID FREQUENCY e q ue t t ze t ten is adjusted by R4/R 5. covering a frequency range f roll O. 4 to 6.4 kHz. CUT/B OOST is controlled by R22. R6 adjusts the Q-hcto r. s est t tve or negathe bell shaped PEAK ING equa lfzation i s applicable i n thea i d frequency range.

The LOW FREQUENCY equalf zatlon operates s i aUa r ty t o the high frequency section. R1/R8 Idj usts the frequency range fro a 25 to 400 Hz. CUT o r 800S Tare controlled by R23, Q by R9 and SW12 dete rllines the c ho fce of efther SHElVING or PEAt:IfiI G chlra cteristics.

The three signals which lu ve the 4-126 filter are &quot;ce r-rect tea sfgnalse it her i n-phase or 180 degreu evr-e e-snase with the equllfz e r t n put and bl ndpas s l i.t ted as deter ained by the equalf zer sectfo n and controls etti ngs. These c orr e c tfo n s 1gna ls are then sUlilied together with the pr t a ary (Inpu t) s l gnl l by the operational uplift er s n, Z2 Ind Z4 thus for _lng the eq ul ltzed outputs fg nal.

TIlts concept o f I dd fng a corrections 1gna l together wft h the

Inc o_i ng signal t o for.. the equalized signal is directly

responsible fort he low nofse and dtsto r tio n capabilities of

this unit.

**&quot; 46 3 SU8MASTE R MOO ULE**

The cOlllpound signal as generated along thee nt ire processing chaln appears a t the output of Z4. Fro. here it is routed to one oft he nor.all y open contacts oft he EQUALIZER I HSERT switch SV13.

Thus, with SV13 depressed, the equal l zed signal i s fed tot he output a.pl if1e r 8 l 09A. Ina dd i t ion, as SV13 is depressed, the LED indicator is activated.

8 l 09A Output Alll pl i ff e randI NSERT Tile 8-109 A upl ifhr raises the s 1gna l to -10 d81ll nomlnally. TIle output is acthely balanced Ind fed to the &quot; insert poln t &quot; at p1n s 22 Ind Z of module connector PI. Tilts point is usually connected to a ' normal led' set of insert jacks, with the outputs 1de connected to tile subma ste r fader.

The output o f the balanced fad er 15 returned tot he 1I0 dule o n p l ns 14 and R of PI. Thl teed fort he PREFADE REVER8ERATION SENO (RS), the PREfADE FOLDSAC K (f 8) and the PREfAOE PU811 C ADDRESS (PAl channels 15 bro u9ht out at PI, pins 20 Ind X and originates nor lllllll y fr oe the inputs tee of the fll.de r.

An uternal slate lnp ut is provided a t connector P2, pins 8 ud J. TIles hte signll l ls injected fn place of tile r e guh r signal when r ehy Kl is llctivued. Tri. pot RI42 serves to cllltbrate the shte tevet.

8-10if 800sterAliplifier Thls a. plf fie rope rates with I 9a1n of 33 dB. It recovers tile IS dB ~1 n-ha nd · loss incurred by the fll.de r llnd provides addft10 na1 9a 1n t o produce a nOlllinll level of +8 dBIl llt its

output.

**,. 46 3 SU8MASTER MODULE**

OIRECT Output A DIRECT output from the 8-I09F alllplf f h r is provided a t connector P2. pins 12 lind N. Aside from other uses within a given console system, the DIRECT output feeds the sub llaster VU meter and serves as the take off point for monitoring. Master Outputs and PAN Control Two left and two right outputs area lso being fed by the 8-I09F output signal. They He routed vfa PAN switch SWI4 and PAN control R24 to R27, followed by four MASTER ASSIGNMENT SWITCHES SW22 t o SW2S. the master outputs are connected to tile appropriate e eec t e output terminals vfa sUlllming network resistors t o be combined wittl feeds from others ubnes te r lIIixing che nne t s. Auxiliary Outputs Ina ddit ion, a SOLO output is av ai hble via SWI6. to allow selective monitoring of tile particular submaster cn anne t. Ottler feeds originating from tile 8 -109F all pli fie r lire supplied to ttl e POSTFADE RS. FB lind PA channels.

PRE/ POST Selector Switches and Level Controls PRE/POST selection o f the RS. FB and PA channels Is facilitated by switches SWIg, SWl8 and SW4 respectively; each switch is fol l cwed by its asso cfated level control. The outputs of the level controls are fed to the summing outputs vh individual assignment switches. Following the assignment switches, tll ese outputs are fed to their appropriate mixing buses via sUlllming resistors.

Auxll iar y Control Functions DC control contacts are provided on the SOLO and PA ASsignments witches t o permit e x t erna l muting and selective control functions

a s.may be required.

1'4 46 3 SUB&quot;'ASTER &quot;'OOUl E

Power Supply Oecoup lfno An. ct h e power supply decoupl1ng network consisting o f Ql through Q6 provides. high degree of 1so lat 1on be twun the 1'4 463. nd the t25 volt SI.Ipply rails. Transistors Q5 and Q6 sene as current.0n 1tors and will 11_1t the current flowing through the pass t rans15tors Q3 and Q4 1n the event that excess t ve power supply de •• nds should arise as I result of cOllponent failure.

**I- ' ·5**

WAR C -BECK SYSTEMS LTC.

fREQUENcy RESPONSE CHARACIERISTICS Mlt63 SUBHAS TER MOQULE

LOll FREOUENCY section Hade: SHELVING.

CUT/B OOST: i15 dB.

FREQUENCY: 25 l 400 Hz •

**· I - I**

7 If

**I I-- I**

LOW FREQUENCY sect fan

**I~ I**

Mode: PEAKING.

CUT/BOOST: t I5 dB.

FREQUENCY: 2Sl400Hz.

Q: 2.

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWDMyanJjTnJoekU/view?resourcekey=0-ad_b0ZQ8NLAWO88HRQBvzg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWDMyanJjTnJoekU&resourcekey=0-ad_b0ZQ8NLAWO88HRQBvzg" width="240" alt="1972 - M463 - Taken apart.jpg"></a><br><sub>1972|5 · Taken apart</sub></td></tr>
</table>

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVjRyVjctOVNkZUk/view?resourcekey=0-UhSr-4Q1CevU8wg9QW5Dng" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVjRyVjctOVNkZUk&resourcekey=0-UhSr-4Q1CevU8wg9QW5Dng" width="240" alt="1972 - M463 - 463-04-002 - OUTPUT AMP UPPER LEGEND.jpg"></a><br><sub>1972|5 · 463-04-002 - OUTPUT AMP UPPER LEGEND · <a href="MECHANICAL/1972%20-%20M463%20-%20463-04-002%20-%20OUTPUT%20AMP%20UPPER%20LEGEND%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaE5qaUtTbE1YOWM/view?resourcekey=0-BoEGZfVrticX7CdXIuh7cw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaE5qaUtTbE1YOWM&resourcekey=0-BoEGZfVrticX7CdXIuh7cw" width="240" alt="1972 - M463 - 463-04-020 - BETWEEN ASS IGNED MIXING BUSES LEFT AND RIGHT.jpg"></a><br><sub>1972|5 · 463-04-020 - BETWEEN ASS IGNED MIXING BUSES LEFT AND RIGHT · <a href="MECHANICAL/1972%20-%20M463%20-%20463-04-020%20-%20BETWEEN%20ASS%20IGNED%20MIXING%20BUSES%20LEFT%20AND%20RIGHT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQnI5MDF3UkFZaTA/view?resourcekey=0-IlcN8WLcBK-d1DNyAvWQiA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQnI5MDF3UkFZaTA&resourcekey=0-IlcN8WLcBK-d1DNyAvWQiA" width="240" alt="1972 - M463 - 463-04-020 - WHEN DEPRESSED THIS SWITCH INSERTS THE EQUALIZER SECTION.jpg"></a><br><sub>1972|5 · 463-04-020 - WHEN DEPRESSED THIS SWITCH INSERTS THE EQUALIZER SECTION · <a href="MECHANICAL/1972%20-%20M463%20-%20463-04-020%20-%20WHEN%20DEPRESSED%20THIS%20SWITCH%20INSERTS%20THE%20EQUALIZER%20SECTION%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1976 - 463-04-008 - M463M SUB MASTER MODULE ASSEMBLY (LAYOUT) - DRN MING - ISS 1.jpg`

## 3-D model

[`MECHANICAL/M463.stl`](MECHANICAL/M463.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M463)

- **Size:** 67.36 × 419.28 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 26 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M463 - front panel.svg`)
- the drawn panel is 0.11 wide to high, the size 0.16: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M463.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY0RYdnd6S0R2b0E/view?resourcekey=0-NIqC7mf092vsemt-MaxrjA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY0RYdnd6S0R2b0E&resourcekey=0-NIqC7mf092vsemt-MaxrjA" width="240" alt="1972 - M463 - 4-126-02-001 - IOK COMBINED COMBINED VALUE VALUE.jpg"></a><br><sub>1972|5 · 4-126-02-001 - IOK COMBINED COMBINED VALUE VALUE · <a href="SCHEMATICS/1972%20-%20M463%20-%204-126-02-001%20-%20IOK%20COMBINED%20COMBINED%20VALUE%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVlQ1Q3lYUmIxZXM/view?resourcekey=0-KTwsAjr-XqhOR-PEEwXT6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVlQ1Q3lYUmIxZXM&resourcekey=0-KTwsAjr-XqhOR-PEEwXT6w" width="240" alt="1972 - M463 - 4-126-06-001 - CTO LMZOIN.jpg"></a><br><sub>1972|5 · 4-126-06-001 - CTO LMZOIN · <a href="SCHEMATICS/1972%20-%20M463%20-%204-126-06-001%20-%20CTO%20LMZOIN%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVlJwbjMtMlNJOUU/view?resourcekey=0-Q_T3XDi35hFaR9vw3EbUFg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVlJwbjMtMlNJOUU&resourcekey=0-Q_T3XDi35hFaR9vw3EbUFg" width="240" alt="1972 - M463 - 4-136-06-010 - PIN ESLOLICKD USDOJ ITI ABXEPKM.jpg"></a><br><sub>1972|5 · 4-136-06-010 - PIN ESLOLICKD USDOJ ITI ABXEPKM · <a href="SCHEMATICS/1972%20-%20M463%20-%204-136-06-010%20-%20PIN%20ESLOLICKD%20USDOJ%20ITI%20ABXEPKM%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQVJ1SnF5R2RUV1k/view?resourcekey=0-VXJOFiZkWck4Su1cbJ0AHw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQVJ1SnF5R2RUV1k&resourcekey=0-VXJOFiZkWck4Su1cbJ0AHw" width="240" alt="1972 - M463 - 4-141-02-001 - CZO LEVELCAL.jpg"></a><br><sub>1972|5 · 4-141-02-001 - CZO LEVELCAL · <a href="SCHEMATICS/1972%20-%20M463%20-%204-141-02-001%20-%20CZO%20LEVELCAL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb2pSd3lLU0plUE0/view?resourcekey=0-FqkY--co36WgJmHk5yNDXw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb2pSd3lLU0plUE0&resourcekey=0-FqkY--co36WgJmHk5yNDXw" width="240" alt="1972 - M463 - 4-141-06-001 - ARE FACTORY SELECTED.jpg"></a><br><sub>1972|5 · 4-141-06-001 - ARE FACTORY SELECTED · <a href="SCHEMATICS/1972%20-%20M463%20-%204-141-06-001%20-%20ARE%20FACTORY%20SELECTED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUWFrSVBzalJNSFE/view?resourcekey=0-Ui_nqAkOEd3xhDPdexkcEw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUWFrSVBzalJNSFE&resourcekey=0-Ui_nqAkOEd3xhDPdexkcEw" width="240" alt="1972 - M463 - 463-01-001 - INSERT INSERT JACKS FADER.jpg"></a><br><sub>1972|5 · 463-01-001 - INSERT INSERT JACKS FADER · <a href="SCHEMATICS/1972%20-%20M463%20-%20463-01-001%20-%20INSERT%20INSERT%20JACKS%20FADER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbGszT3Bxd0NZaUU/view?resourcekey=0-QP6utKr2WV2l0Cii5UOC_w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbGszT3Bxd0NZaUU&resourcekey=0-QP6utKr2WV2l0Cii5UOC_w" width="240" alt="1972 - M463 - 463-02-001 - SUB MASTER MODULE.jpg"></a><br><sub>1972|5 · 463-02-001 - SUB MASTER MODULE · <a href="SCHEMATICS/1972%20-%20M463%20-%20463-02-001%20-%20SUB%20MASTER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNTRJdm5fdTItMk0/view?resourcekey=0-n2ykGr4RyXfIAaveAaLPDQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNTRJdm5fdTItMk0&resourcekey=0-n2ykGr4RyXfIAaveAaLPDQ" width="240" alt="1972 - M463 - 8-109-02-002 - NOMINAL VALUE.jpg"></a><br><sub>1972|5 · 8-109-02-002 - NOMINAL VALUE · <a href="SCHEMATICS/1972%20-%20M463%20-%208-109-02-002%20-%20NOMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRnBUU3VnUWpDUnc/view?resourcekey=0-I4h8-sqkBS8fycAhfR2NGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRnBUU3VnUWpDUnc&resourcekey=0-I4h8-sqkBS8fycAhfR2NGA" width="240" alt="1972 - M463 - 8-109-02-002 - RII RIZ.jpg"></a><br><sub>1972|5 · 8-109-02-002 - RII RIZ · <a href="SCHEMATICS/1972%20-%20M463%20-%208-109-02-002%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOGE5WUlBNWZWSkU/view?resourcekey=0-kZn3VvvSH_M5ynmeBEgEyg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOGE5WUlBNWZWSkU&resourcekey=0-kZn3VvvSH_M5ynmeBEgEyg" width="240" alt="1972 - M463 - 8-109-02-007 - NDMINAL VALUE.jpg"></a><br><sub>1972|5 · 8-109-02-007 - NDMINAL VALUE · <a href="SCHEMATICS/1972%20-%20M463%20-%208-109-02-007%20-%20NDMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQVFoTHpnTTFLam8/view?resourcekey=0-bj6pRQPg0GEUjtp_F-xdKw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQVFoTHpnTTFLam8&resourcekey=0-bj6pRQPg0GEUjtp_F-xdKw" width="240" alt="1972 - M463 - 8-109-02-007.jpg"></a><br><sub>1972|5 · 8-109-02-007 · <a href="SCHEMATICS/1972%20-%20M463%20-%208-109-02-007%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDNGY0JzbTdJR1E/view?resourcekey=0-DHgnfQAtURSmM7t-V1lE0w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDNGY0JzbTdJR1E&resourcekey=0-DHgnfQAtURSmM7t-V1lE0w" width="240" alt="1972 - M463 - 8-109-06-002 - OUTPUT AMPLIFIER.jpg"></a><br><sub>1972|5 · 8-109-06-002 - OUTPUT AMPLIFIER · <a href="SCHEMATICS/1972%20-%20M463%20-%208-109-06-002%20-%20OUTPUT%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc050NXdjWkotMGc/view?resourcekey=0-gbwolyYC8sdK-6bjMs4JUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc050NXdjWkotMGc&resourcekey=0-gbwolyYC8sdK-6bjMs4JUw" width="240" alt="1972 - M463 - 8-109-06-002.jpg"></a><br><sub>1972|5 · 8-109-06-002 · <a href="SCHEMATICS/1972%20-%20M463%20-%208-109-06-002%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSkxRUXFZVzNrb28/view?resourcekey=0-Bozs6T9leN20FVMEv07xNg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSkxRUXFZVzNrb28&resourcekey=0-Bozs6T9leN20FVMEv07xNg" width="240" alt="1972 - M463 - 8-109-06-007 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1972|5 · 8-109-06-007 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1972%20-%20M463%20-%208-109-06-007%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNjgyNXVYSGd5azA/view?resourcekey=0-8tdnfzOhbB2wPMcRUYBA2g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNjgyNXVYSGd5azA&resourcekey=0-8tdnfzOhbB2wPMcRUYBA2g" width="240" alt="1972 - M463 - 8-109-06-007.jpg"></a><br><sub>1972|5 · 8-109-06-007 · <a href="SCHEMATICS/1972%20-%20M463%20-%208-109-06-007%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSWw0eDQzYURHRHc/view?resourcekey=0-dYCCB1VeoJLGecY1zJ_OUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSWw0eDQzYURHRHc&resourcekey=0-dYCCB1VeoJLGecY1zJ_OUw" width="240" alt="1974 - M463 - 4-126-06-001 - MODIICKD USED.jpg"></a><br><sub>1974|7 · 4-126-06-001 - MODIICKD USED · <a href="SCHEMATICS/1974%20-%20M463%20-%204-126-06-001%20-%20MODIICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQnpSR0d3ZDhVLTA/view?resourcekey=0-_3aC9q6lnIoQlSbh_ncGig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQnpSR0d3ZDhVLTA&resourcekey=0-_3aC9q6lnIoQlSbh_ncGig" width="240" alt="1974 - M463 - 4-141-02-001 - TORY SELECTED IAL VALUE.jpg"></a><br><sub>1974|7 · 4-141-02-001 - TORY SELECTED IAL VALUE · <a href="SCHEMATICS/1974%20-%20M463%20-%204-141-02-001%20-%20TORY%20SELECTED%20IAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcnFtS3NPTjBzQ1E/view?resourcekey=0--Y1D16p5fSLLItx1yrYx1A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcnFtS3NPTjBzQ1E&resourcekey=0--Y1D16p5fSLLItx1yrYx1A" width="240" alt="1974 - M463 - 4-141-06-001 - SUMMING AMPLIFIER.jpg"></a><br><sub>1974|7 · 4-141-06-001 - SUMMING AMPLIFIER · <a href="SCHEMATICS/1974%20-%20M463%20-%204-141-06-001%20-%20SUMMING%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1wZCVGxuBiECq98ZAOfZgmLVAFW1ybbgv/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1wZCVGxuBiECq98ZAOfZgmLVAFW1ybbgv" width="240" alt="1976 - 463-02-004 - D SUB-MASTER MODULE - DRN AF - ISS 2.jpg"></a><br><sub>1976|9 · 463-02-004 - D SUB-MASTER MODULE - DRN AF - ISS 2 · <a href="SCHEMATICS/1976%20-%20463-02-004%20-%20D%20SUB-MASTER%20MODULE%20-%20DRN%20AF%20-%20ISS%202%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1yH-Sp8Mr1h3xvKEgbbvsIMPWJ8-Y1iXY/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1yH-Sp8Mr1h3xvKEgbbvsIMPWJ8-Y1iXY" width="240" alt="1976 - 463-02-005 - E SUB-MASTER MODULE - DRN AF - ISS 2.jpg"></a><br><sub>1976|9 · 463-02-005 - E SUB-MASTER MODULE - DRN AF - ISS 2 · <a href="SCHEMATICS/1976%20-%20463-02-005%20-%20E%20SUB-MASTER%20MODULE%20-%20DRN%20AF%20-%20ISS%202%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/19hJ5ZnZoSKrSSMLQF-PRGUw6aagmu-AB/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=19hJ5ZnZoSKrSSMLQF-PRGUw6aagmu-AB" width="240" alt="1976 - 463-02-006 - F SUB-MASTER MODULE - DRN AF - ISS 2.jpg"></a><br><sub>1976|9 · 463-02-006 - F SUB-MASTER MODULE - DRN AF - ISS 2 · <a href="SCHEMATICS/1976%20-%20463-02-006%20-%20F%20SUB-MASTER%20MODULE%20-%20DRN%20AF%20-%20ISS%202%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVWx0Q1JOX2VrSXM/view?resourcekey=0-ys3_38pcNWWJa6bbtaNyag" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVWx0Q1JOX2VrSXM&resourcekey=0-ys3_38pcNWWJa6bbtaNyag" width="240" alt="1976 - M463 - 4-126-02-001 - EQUALIZER FILTER.jpg"></a><br><sub>1976|9 · 4-126-02-001 - EQUALIZER FILTER · <a href="SCHEMATICS/1976%20-%20M463%20-%204-126-02-001%20-%20EQUALIZER%20FILTER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYnlvcFdITzAxVTg/view?resourcekey=0-O3VWfqgipAPpnc2r_zmIlg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYnlvcFdITzAxVTg&resourcekey=0-O3VWfqgipAPpnc2r_zmIlg" width="240" alt="1977 - M463 - 463-01-001 - YSOLO CONTROL SOLO COMMON CONTROL.jpg"></a><br><sub>1977|10 · 463-01-001 - YSOLO CONTROL SOLO COMMON CONTROL · <a href="SCHEMATICS/1977%20-%20M463%20-%20463-01-001%20-%20YSOLO%20CONTROL%20SOLO%20COMMON%20CONTROL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1AZsDXxALYXnlzTzpku-3V8adViWwAbcq/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1AZsDXxALYXnlzTzpku-3V8adViWwAbcq" width="240" alt="1982 - 463-02-015 - M463R MASTER MODULE SCHEMATIC - DRN JP - ENG ELJ.jpg"></a><br><sub>1982|15 · 463-02-015 - M463R MASTER MODULE SCHEMATIC - DRN JP - ENG ELJ · <a href="SCHEMATICS/1982%20-%20463-02-015%20-%20M463R%20MASTER%20MODULE%20SCHEMATIC%20-%20DRN%20JP%20-%20ENG%20ELJ%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1h7IdVAqUHQydV3Bry686m78wOFuVaYCj/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1h7IdVAqUHQydV3Bry686m78wOFuVaYCj" width="240" alt="19xx - M463 - DOC - 463-02-009 - SUBMA STER MODULE SCHEMATIC.png"></a><br><sub>19xx - M463 - DOC - 463-02-009 - SUBMA STER MODULE SCHEMATIC · <a href="SCHEMATICS/19xx%20-%20M463%20-%20DOC%20-%20463-02-009%20-%20SUBMA%20STER%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1MUl9-qDpXCLWqU4xNPW5l8djmxaOBC-B/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1MUl9-qDpXCLWqU4xNPW5l8djmxaOBC-B" width="240" alt="19xx - M463 - DOC - 463-02-019 - SUBMASTER MODULE SCHEMATIC.png"></a><br><sub>19xx - M463 - DOC - 463-02-019 - SUBMASTER MODULE SCHEMATIC · <a href="SCHEMATICS/19xx%20-%20M463%20-%20DOC%20-%20463-02-019%20-%20SUBMASTER%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1in_ZcpJtmlhQJBvkPt-m8X824wVc1EH3/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1in_ZcpJtmlhQJBvkPt-m8X824wVc1EH3" width="240" alt="19xx - M463 - DOC - 463-02-020 - BYBTEMB DALHM EHNE.png"></a><br><sub>19xx - M463 - DOC - 463-02-020 - BYBTEMB DALHM EHNE · <a href="SCHEMATICS/19xx%20-%20M463%20-%20DOC%20-%20463-02-020%20-%20BYBTEMB%20DALHM%20EHNE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1974 - 4-126-06-001 - 4-126 EQUALIZER FILTER COMPONENT ASSEMBLY - DRN DM - ISS 2.jpg`, `1974 - 4-141-02-001 - 4-141 SUMMING AMPLIFIER SCHEMATIC - DRN DM - ISS 7.jpg`, `1974 - LB 463-02 - SUB-MASTER SCHEMATIC - DRN DM.jpg`, `1976 - 4-109-02-004 - 4-109C BOOSTER AMPLIFIER SCHEMATIC - DRN PWC - ISS 2.png`, `1976 - 4-126-02-001 - 4-126 EQUALIZER FILTER AMPLIFIER SCHEMATIC - DRN GEB - ISS 4.jpg`, `1976 - 463-02-007 - M463M SUBMASTER (SUMMING struck) MODULE SCHEMATIC - ISS 1.jpg`, `1977 - 463-01-001 - SUBMASTER MODULE FUNCTIONAL DIAGRAM - DRN PKM - ISS 2.jpg`, `1977 - 463-01-003 - M463B SUBMASTER MODULE FUNCTIONAL DIAGRAM - DRN PKM - ISS 2.jpg`, `1978 - 463-06-001 - M463J SUBMASTER MODULE COMPONENT LAYOUT - DRN GEB - ENG GEB - ISS 1.jpg`, `1978 - 8-109-02-002 - 8-109A OUTPUT AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.jpg`, `1978 - 8-109-02-007 - 8-109F BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.jpg`, `1979 - 463-01-010 - SUBMASTER MODULE FUNCTIONAL DIAGRAM - DRN PKM - ISS 2.jpg`, `1980 - 463-01-011 - M463L SUBMASTER MODULE FUNCTIONAL DIAGRAM - DRN VINCE - ISS 1.jpg`, `1980 - 463-01-016 - SUBMASTER MODULE FUNCTIONAL DIAGRAM - DRN VINCE - ISS 1.jpg`, `19xx - 4-141-02-001.jpg`, `19xx - 463-01-001.jpg`, `19xx - 463-02-019 - M463AB SUBMASTER MODULE SCHEMATIC - DRN HM - ISS 1.jpg`, `19xx - 463-02-020 - AC MASTER MODULE SCHEMATIC - DRN HM - ENG HM.jpg`, `19xx - 463-06-001.jpg`, `19xx - 463-06-028 - M463AC MASTER MODULE COMPONENT LAYOUT - DRN HM - ISS 1.jpg`, `19xx - 8-109-02-002.jpg`, `19xx - 8-109-02-007.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLWhBQW1NTVBXVjQ/view?resourcekey=0-_ZmADunQ90o7-Py5fxQx1A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLWhBQW1NTVBXVjQ&resourcekey=0-_ZmADunQ90o7-Py5fxQx1A" width="240" alt="1972 - M463 - 4136-06-010 - COMPONENT NQTES LEGEND CONNECTOR PIN MOUNTED.jpg"></a><br><sub>1972|5 · 4136-06-010 - COMPONENT NQTES LEGEND CONNECTOR PIN MOUNTED · <a href="PINOUTS/1972%20-%20M463%20-%204136-06-010%20-%20COMPONENT%20NQTES%20LEGEND%20CONNECTOR%20PIN%20MOUNTED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeXFxWDFZRnNOdGs/view?resourcekey=0-qzgJB5RaqLqZtXkGx3AEHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeXFxWDFZRnNOdGs&resourcekey=0-qzgJB5RaqLqZtXkGx3AEHQ" width="240" alt="1972 - M463 - 463-04-002 - KELE CONNECTOR REAR VIEW.jpg"></a><br><sub>1972|5 · 463-04-002 - KELE CONNECTOR REAR VIEW · <a href="PINOUTS/1972%20-%20M463%20-%20463-04-002%20-%20KELE%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M463 - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | IC (INTERNALLY CONNECTED) | other |  | high |
| 2 | GND | ground |  | high |
| 3 | LEFT 1 OUT | out | LEFT 1 OUT | high |
| 4 | LEFT 2 OUT | out | LEFT 2 OUT | high |
| 5 | RIGHT 1 OUT | out | RIGHT 1 OUT | high |
| 6 | RIGHT 2 OUT | out | RIGHT 2 OUT | high |
| 7 | GND | ground |  | high |
| 8 | SLATE IN | in | SLATE IN | high |
| 9 | N/C | nc |  | high |
| 10 | IC (INTERNALLY CONNECTED) | other |  | high |
| 11 | IC (INTERNALLY CONNECTED) | other |  | high |
| 12 | DIRECT OUTPUT | out | DIRECT OUTPUT | high |
| 13 | IC (INTERNALLY CONNECTED) | other |  | high |
| 14 | IC (INTERNALLY CONNECTED) | other |  | high |
| 15 | SLATE CONTROL | control_in | SLATE CONTROL | high |
| 16 | IC (INTERNALLY CONNECTED) | other |  | high |
| 17 | IC (INTERNALLY CONNECTED) | other |  | high |
| 18 | CTL COM | ground |  | high |
| 19 | -25 V | power |  | high |
| 20 | 25V COM | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| A | IC (INTERNALLY CONNECTED) | other |  | high |
| B | GND | ground |  | high |
| C | LEFT 1 OUT | out | LEFT 1 OUT | high |
| D | LEFT 2 OUT | out | LEFT 2 OUT | high |
| E | RIGHT 1 OUT | out | RIGHT 1 OUT | high |
| F | RIGHT 2 OUT | out | RIGHT 2 OUT | high |
| H | GND | ground |  | high |
| J | SLATE IN | in | SLATE IN | high |
| K | N/C | nc |  | high |
| L | IC (INTERNALLY CONNECTED) | other |  | high |
| M | IC (INTERNALLY CONNECTED) | other |  | high |
| N | DIRECT OUTPUT | out | DIRECT OUTPUT | high |
| P | IC (INTERNALLY CONNECTED) | other |  | high |
| R | IC (INTERNALLY CONNECTED) | other |  | high |
| S | N/C | nc |  | high |
| T | PA CONTROL | control_in | PA CONTROL | high |
| U | IC (INTERNALLY CONNECTED) | other |  | high |
| V | SOLO CONTROL | control_in | SOLO CONTROL | high |
| W | IC (INTERNALLY CONNECTED) | other |  | high |
| X | IC (INTERNALLY CONNECTED) | other |  | high |
| Y | +24 V | power |  | high |
| Z | IC (INTERNALLY CONNECTED) | other |  | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSzlzUkttWXhORmM/view?resourcekey=0-Sv2UACvOwZVMLWMga6gTug" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSzlzUkttWXhORmM&resourcekey=0-Sv2UACvOwZVMLWMga6gTug" width="240" alt="1972 - M463 - P001 - Title Page.jpg"></a><br><sub>1972|5 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ3doLW1CUURuRmM/view?resourcekey=0-ssiv_nPNdqFxO2N8xF_kSw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ3doLW1CUURuRmM&resourcekey=0-ssiv_nPNdqFxO2N8xF_kSw" width="240" alt="1972 - M463 - P003 - 1-1.jpg"></a><br><sub>1972|5 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZUhBQ2Jfc1JBaTg/view?resourcekey=0-TqR2fRFrp67LoAXF4MdiJQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZUhBQ2Jfc1JBaTg&resourcekey=0-TqR2fRFrp67LoAXF4MdiJQ" width="240" alt="1972 - M463 - P004 - 2-1.jpg"></a><br><sub>1972|5 · P004 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZC1rSHBHMl9vLUk/view?resourcekey=0-faXNWwIjIwftwRGEjx_OHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZC1rSHBHMl9vLUk&resourcekey=0-faXNWwIjIwftwRGEjx_OHA" width="240" alt="1972 - M463 - P005 - 2-2.jpg"></a><br><sub>1972|5 · P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVZ0LVV5ak1SSlU/view?resourcekey=0-qJypPxEFnHXVCet787xIGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVZ0LVV5ak1SSlU&resourcekey=0-qJypPxEFnHXVCet787xIGw" width="240" alt="1972 - M463 - P006 - 2-3.jpg"></a><br><sub>1972|5 · P006 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaW9GOUUzWnBDZWs/view?resourcekey=0--vDOm_i7Sim_dCIozZ8U9w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaW9GOUUzWnBDZWs&resourcekey=0--vDOm_i7Sim_dCIozZ8U9w" width="240" alt="1972 - M463 - P007 - 2-4.jpg"></a><br><sub>1972|5 · P007 - 2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcUsyTkJCNC1FYjg/view?resourcekey=0-zoDtqU6I5kTANi_5vcHqIQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcUsyTkJCNC1FYjg&resourcekey=0-zoDtqU6I5kTANi_5vcHqIQ" width="240" alt="1972 - M463 - P008 - 2-5.jpg"></a><br><sub>1972|5 · P008 - 2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2pObENmTDBfYnM/view?resourcekey=0-PicO8GG_41qqpzFz79yDvw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2pObENmTDBfYnM&resourcekey=0-PicO8GG_41qqpzFz79yDvw" width="240" alt="1972 - M463 - P009 - 3-1.jpg"></a><br><sub>1972|5 · P009 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMlJDcnVKbVZFb0E/view?resourcekey=0-vG9TBOJ7ruOVHIvykbeK6Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMlJDcnVKbVZFb0E&resourcekey=0-vG9TBOJ7ruOVHIvykbeK6Q" width="240" alt="1972 - M463 - P010 - 3-2.jpg"></a><br><sub>1972|5 · P010 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaDRFMEY1c1NNbHc/view?resourcekey=0-_4OYsCOtcYPMAYMsQurlKQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaDRFMEY1c1NNbHc&resourcekey=0-_4OYsCOtcYPMAYMsQurlKQ" width="240" alt="1972 - M463 - P011 - 3-3.jpg"></a><br><sub>1972|5 · P011 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM1BQVGp6NFhCMnc/view?resourcekey=0-OM4hK1nqoyXNDt5ZnNoMuQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM1BQVGp6NFhCMnc&resourcekey=0-OM4hK1nqoyXNDt5ZnNoMuQ" width="240" alt="1972 - M463 - P012 - 4-1.jpg"></a><br><sub>1972|5 · P012 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYkVzamJCbUt3eW8/view?resourcekey=0-IfecNu_8W1eXeNNrfZzB6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYkVzamJCbUt3eW8&resourcekey=0-IfecNu_8W1eXeNNrfZzB6w" width="240" alt="1972 - M463 - P013 - 4-2.jpg"></a><br><sub>1972|5 · P013 - 4-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTjIyMWJKXzRFSjA/view?resourcekey=0-GdlACk0Ww6mgt7xHgRUERw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTjIyMWJKXzRFSjA&resourcekey=0-GdlACk0Ww6mgt7xHgRUERw" width="240" alt="1972 - M463 - P014 - 4-3.jpg"></a><br><sub>1972|5 · P014 - 4-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd1RBR08wMDQ5VXM/view?resourcekey=0-qf-pQ0CYQvnWaGyX9TrlXQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd1RBR08wMDQ5VXM&resourcekey=0-qf-pQ0CYQvnWaGyX9TrlXQ" width="240" alt="1972 - M463 - P015 - 4-4.jpg"></a><br><sub>1972|5 · P015 - 4-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbXNBVUg1SzNhOHM/view?resourcekey=0-i9NXO04fEBqHMJqMaXH12w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbXNBVUg1SzNhOHM&resourcekey=0-i9NXO04fEBqHMJqMaXH12w" width="240" alt="1972 - M463 - P016 - 4-5.jpg"></a><br><sub>1972|5 · P016 - 4-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbWF1V1VEQVRFYW8/view?resourcekey=0-0amGN5sJ8fR3fGlBMg77Zg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbWF1V1VEQVRFYW8&resourcekey=0-0amGN5sJ8fR3fGlBMg77Zg" width="240" alt="1972 - M463 - P017 - 4-6.jpg"></a><br><sub>1972|5 · P017 - 4-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbVlCR001X2NFMG8/view?resourcekey=0-ZtSTquPm-vyTyZTBgDzsKA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbVlCR001X2NFMG8&resourcekey=0-ZtSTquPm-vyTyZTBgDzsKA" width="240" alt="1972 - M463 - P018 - 4-7.jpg"></a><br><sub>1972|5 · P018 - 4-7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKanQ4cHVvX0REakk/view?resourcekey=0-Zjr33UvIaNFIPfELHHP9Hg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKanQ4cHVvX0REakk&resourcekey=0-Zjr33UvIaNFIPfELHHP9Hg" width="240" alt="1972 - M463 - P019 - 8-109.jpg"></a><br><sub>1972|5 · P019 - 8-109</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWGRrU1hsc3oyR3M/view?resourcekey=0-3x6PyvUO4VPDoXC9DNGPAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWGRrU1hsc3oyR3M&resourcekey=0-3x6PyvUO4VPDoXC9DNGPAA" width="240" alt="1972 - M463 - P020 - 8-109-1-1.jpg"></a><br><sub>1972|5 · P020 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdVBteFA5V09KbmM/view?resourcekey=0-HABgyTguTCME4biQGJ5IWQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdVBteFA5V09KbmM&resourcekey=0-HABgyTguTCME4biQGJ5IWQ" width="240" alt="1972 - M463 - P021 - 8-109-1-2.jpg"></a><br><sub>1972|5 · P021 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa293TDlxWFJIQjA/view?resourcekey=0-dlsRpaOUbKuGvBy6qH9V6Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa293TDlxWFJIQjA&resourcekey=0-dlsRpaOUbKuGvBy6qH9V6Q" width="240" alt="1972 - M463 - P022 - 8-109-1-3.jpg"></a><br><sub>1972|5 · P022 - 8-109-1-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKck0ya24zeDFFdm8/view?resourcekey=0-8PtKGQrP_xn1Ct-4ejGhcA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKck0ya24zeDFFdm8&resourcekey=0-8PtKGQrP_xn1Ct-4ejGhcA" width="240" alt="1972 - M463 - P023 - 8-109-2-1.jpg"></a><br><sub>1972|5 · P023 - 8-109-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTjl2WFNtcS0zZzQ/view?resourcekey=0-jpyA44m0lHWbdSFZNfoBig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTjl2WFNtcS0zZzQ&resourcekey=0-jpyA44m0lHWbdSFZNfoBig" width="240" alt="1972 - M463 - P024 - 8-109-2-2.jpg"></a><br><sub>1972|5 · P024 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcURXV0x4QzhUTkU/view?resourcekey=0-JHQNGZ2iPSmHfzL7eyttvg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcURXV0x4QzhUTkU&resourcekey=0-JHQNGZ2iPSmHfzL7eyttvg" width="240" alt="1972 - M463 - P025 - 8-109-2-3.jpg"></a><br><sub>1972|5 · P025 - 8-109-2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM0w1NXhZb0NHUEk/view?resourcekey=0-6XA95zGD6dwHscUk7gB80A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM0w1NXhZb0NHUEk&resourcekey=0-6XA95zGD6dwHscUk7gB80A" width="240" alt="1972 - M463 - P026 - 8-109-2-4.jpg"></a><br><sub>1972|5 · P026 - 8-109-2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUmp0UHR3c1N0elE/view?resourcekey=0-XYgz2J5QzJC-tROf9xclOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUmp0UHR3c1N0elE&resourcekey=0-XYgz2J5QzJC-tROf9xclOQ" width="240" alt="1972 - M463 - P027 - 8-109-2-5.jpg"></a><br><sub>1972|5 · P027 - 8-109-2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0ZHTE1sUF9HcVE/view?resourcekey=0-HDpw3XMh0DYlLyFEDyEUCg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0ZHTE1sUF9HcVE&resourcekey=0-HDpw3XMh0DYlLyFEDyEUCg" width="240" alt="1972 - M463 - P030 - LB463-02-001 01.jpg"></a><br><sub>1972|5 · P030 - LB463-02-001 01</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZE13WFp3c0RaYVU/view?resourcekey=0-vCU5FOUxq88oD8W-kDpQ0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZE13WFp3c0RaYVU&resourcekey=0-vCU5FOUxq88oD8W-kDpQ0Q" width="240" alt="1972 - M463 - P030 - LB463-02-001 02.jpg"></a><br><sub>1972|5 · P030 - LB463-02-001 02</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmFyZzNkRC03a1E/view?resourcekey=0-2u6JNd137o-cKbddjbW7VQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmFyZzNkRC03a1E&resourcekey=0-2u6JNd137o-cKbddjbW7VQ" width="240" alt="1972 - M463 - P030 - LB463-02-001 03.jpg"></a><br><sub>1972|5 · P030 - LB463-02-001 03</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLUtWT051NEJtQVk/view?resourcekey=0-7FnnLt-pDAbnFmtT6hgr6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLUtWT051NEJtQVk&resourcekey=0-7FnnLt-pDAbnFmtT6hgr6w" width="240" alt="1972 - M463 - WAAD-BECK ZABM.jpg"></a><br><sub>1972|5 · WAAD-BECK ZABM</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNE9iaEJNRXVKblE/view?resourcekey=0-d9nGvmuU7Daj8TH7ROiYAg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNE9iaEJNRXVKblE&resourcekey=0-d9nGvmuU7Daj8TH7ROiYAg" width="240" alt="1974 - M463 - Submaster Module (2).pdf"></a><br><sub>1974|7 · Submaster Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMGNaR0s0LW52eTQ/view?resourcekey=0-K3imCJiiDWBN1h1hkaf65g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMGNaR0s0LW52eTQ&resourcekey=0-K3imCJiiDWBN1h1hkaf65g" width="240" alt="1974 - M463 - Submaster Module.pdf"></a><br><sub>1974|7 · Submaster Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT21zQXk2OW9CZWs/view?resourcekey=0-18IZEHg89Oth7bXIcbFt-Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT21zQXk2OW9CZWs&resourcekey=0-18IZEHg89Oth7bXIcbFt-Q" width="240" alt="1979 - M463 - P002.jpg"></a><br><sub>1979|12 · P002</sub></td></tr>
</table>

Not on Google Drive yet: `M463 - P030 - LB463-02-001 04.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1972 - M463 - 4-126-02-001 - IOK COMBINED COMBINED VALUE VALUE.kicad_sch](KICAD/1972%20-%20M463%20-%204-126-02-001%20-%20IOK%20COMBINED%20COMBINED%20VALUE%20VALUE.kicad_sch)
- [1972 - M463 - 4-141-02-001 - CZO LEVELCAL.kicad_sch](KICAD/1972%20-%20M463%20-%204-141-02-001%20-%20CZO%20LEVELCAL.kicad_sch)
- [1972 - M463 - 463-01-001 - INSERT INSERT JACKS FADER.kicad_sch](KICAD/1972%20-%20M463%20-%20463-01-001%20-%20INSERT%20INSERT%20JACKS%20FADER.kicad_sch)
- [1972 - M463 - 463-02-001 - SUB MASTER MODULE.kicad_sch](KICAD/1972%20-%20M463%20-%20463-02-001%20-%20SUB%20MASTER%20MODULE.kicad_sch)
- [1972 - M463 - 8-109-02-002 - NOMINAL VALUE.kicad_sch](KICAD/1972%20-%20M463%20-%208-109-02-002%20-%20NOMINAL%20VALUE.kicad_sch)
- [1972 - M463 - 8-109-02-002 - RII RIZ.kicad_sch](KICAD/1972%20-%20M463%20-%208-109-02-002%20-%20RII%20RIZ.kicad_sch)
- [1972 - M463 - 8-109-02-007 - NDMINAL VALUE.kicad_sch](KICAD/1972%20-%20M463%20-%208-109-02-007%20-%20NDMINAL%20VALUE.kicad_sch)
- [1972 - M463 - 8-109-02-007.kicad_sch](KICAD/1972%20-%20M463%20-%208-109-02-007.kicad_sch)
- [1974 - 4-141-02-001 - 4-141 SUMMING AMPLIFIER SCHEMATIC - DRN DM - ISS 7.kicad_sch](KICAD/1974%20-%204-141-02-001%20-%204-141%20SUMMING%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%207.kicad_sch)
- [1974 - LB 463-02 - SUB-MASTER SCHEMATIC - DRN DM.kicad_sch](KICAD/1974%20-%20LB%20463-02%20-%20SUB-MASTER%20SCHEMATIC%20-%20DRN%20DM.kicad_sch)
- [1974 - M463 - 4-141-02-001 - TORY SELECTED IAL VALUE.kicad_sch](KICAD/1974%20-%20M463%20-%204-141-02-001%20-%20TORY%20SELECTED%20IAL%20VALUE.kicad_sch)
- [1974 - M463 - Submaster Module (2) p31.kicad_sch](KICAD/1974%20-%20M463%20-%20Submaster%20Module%20(2)%20p31.kicad_sch)
- [1974 - M463 - Submaster Module (2) p50.kicad_sch](KICAD/1974%20-%20M463%20-%20Submaster%20Module%20(2)%20p50.kicad_sch)
- [1974 - M463 - Submaster Module (2) p54.kicad_sch](KICAD/1974%20-%20M463%20-%20Submaster%20Module%20(2)%20p54.kicad_sch)
- [1974 - M463 - Submaster Module p31.kicad_sch](KICAD/1974%20-%20M463%20-%20Submaster%20Module%20p31.kicad_sch)
- [1974 - M463 - Submaster Module p42.kicad_sch](KICAD/1974%20-%20M463%20-%20Submaster%20Module%20p42.kicad_sch)
- [1974 - M463 - Submaster Module p50.kicad_sch](KICAD/1974%20-%20M463%20-%20Submaster%20Module%20p50.kicad_sch)
- [1974 - M463 - Submaster Module p54.kicad_sch](KICAD/1974%20-%20M463%20-%20Submaster%20Module%20p54.kicad_sch)
- [1976 - 4-109-02-004 - 4-109C BOOSTER AMPLIFIER SCHEMATIC - DRN PWC - ISS 2.kicad_sch](KICAD/1976%20-%204-109-02-004%20-%204-109C%20BOOSTER%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20PWC%20-%20ISS%202.kicad_sch)
- [1976 - 4-126-02-001 - 4-126 EQUALIZER FILTER AMPLIFIER SCHEMATIC - DRN GEB - ISS 4.kicad_sch](KICAD/1976%20-%204-126-02-001%20-%204-126%20EQUALIZER%20FILTER%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ISS%204.kicad_sch)
- [1976 - 463-02-004 - D SUB-MASTER MODULE - DRN AF - ISS 2.kicad_sch](KICAD/1976%20-%20463-02-004%20-%20D%20SUB-MASTER%20MODULE%20-%20DRN%20AF%20-%20ISS%202.kicad_sch)
- [1976 - 463-02-005 - E SUB-MASTER MODULE - DRN AF - ISS 2.kicad_sch](KICAD/1976%20-%20463-02-005%20-%20E%20SUB-MASTER%20MODULE%20-%20DRN%20AF%20-%20ISS%202.kicad_sch)
- [1976 - 463-02-006 - F SUB-MASTER MODULE - DRN AF - ISS 2.kicad_sch](KICAD/1976%20-%20463-02-006%20-%20F%20SUB-MASTER%20MODULE%20-%20DRN%20AF%20-%20ISS%202.kicad_sch)
- [1976 - 463-02-007 - M463M SUBMASTER (SUMMING struck) MODULE SCHEMATIC - ISS 1.kicad_sch](KICAD/1976%20-%20463-02-007%20-%20M463M%20SUBMASTER%20(SUMMING%20struck)%20MODULE%20SCHEMATIC%20-%20ISS%201.kicad_sch)
- [1976 - M463 - 4-126-02-001 - EQUALIZER FILTER.kicad_sch](KICAD/1976%20-%20M463%20-%204-126-02-001%20-%20EQUALIZER%20FILTER.kicad_sch)
- [1977 - 463-01-001 - SUBMASTER MODULE FUNCTIONAL DIAGRAM - DRN PKM - ISS 2.kicad_sch](KICAD/1977%20-%20463-01-001%20-%20SUBMASTER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20PKM%20-%20ISS%202.kicad_sch)
- [1977 - 463-01-003 - M463B SUBMASTER MODULE FUNCTIONAL DIAGRAM - DRN PKM - ISS 2.kicad_sch](KICAD/1977%20-%20463-01-003%20-%20M463B%20SUBMASTER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20PKM%20-%20ISS%202.kicad_sch)
- [1977 - M463 - 463-01-001 - YSOLO CONTROL SOLO COMMON CONTROL.kicad_sch](KICAD/1977%20-%20M463%20-%20463-01-001%20-%20YSOLO%20CONTROL%20SOLO%20COMMON%20CONTROL.kicad_sch)
- [1978 - 8-109-02-002 - 8-109A OUTPUT AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.kicad_sch](KICAD/1978%20-%208-109-02-002%20-%208-109A%20OUTPUT%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [1978 - 8-109-02-007 - 8-109F BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.kicad_sch](KICAD/1978%20-%208-109-02-007%20-%208-109F%20BOOSTER%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [1979 - 463-01-010 - SUBMASTER MODULE FUNCTIONAL DIAGRAM - DRN PKM - ISS 2.kicad_sch](KICAD/1979%20-%20463-01-010%20-%20SUBMASTER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20PKM%20-%20ISS%202.kicad_sch)
- [1980 - 463-01-011 - M463L SUBMASTER MODULE FUNCTIONAL DIAGRAM - DRN VINCE - ISS 1.kicad_sch](KICAD/1980%20-%20463-01-011%20-%20M463L%20SUBMASTER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20VINCE%20-%20ISS%201.kicad_sch)
- [1980 - 463-01-016 - SUBMASTER MODULE FUNCTIONAL DIAGRAM - DRN VINCE - ISS 1.kicad_sch](KICAD/1980%20-%20463-01-016%20-%20SUBMASTER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20VINCE%20-%20ISS%201.kicad_sch)
- [1982 - 463-02-015 - M463R MASTER MODULE SCHEMATIC - DRN JP - ENG ELJ.kicad_sch](KICAD/1982%20-%20463-02-015%20-%20M463R%20MASTER%20MODULE%20SCHEMATIC%20-%20DRN%20JP%20-%20ENG%20ELJ.kicad_sch)
- [19xx - 4-141-02-001.kicad_sch](KICAD/19xx%20-%204-141-02-001.kicad_sch)
- [19xx - 463-01-001.kicad_sch](KICAD/19xx%20-%20463-01-001.kicad_sch)
- [19xx - 463-01-011.kicad_sch](KICAD/19xx%20-%20463-01-011.kicad_sch)
- [19xx - 463-02-019 - M463AB SUBMASTER MODULE SCHEMATIC - DRN HM - ISS 1.kicad_sch](KICAD/19xx%20-%20463-02-019%20-%20M463AB%20SUBMASTER%20MODULE%20SCHEMATIC%20-%20DRN%20HM%20-%20ISS%201.kicad_sch)
- [19xx - 463-02-020 - AC MASTER MODULE SCHEMATIC - DRN HM - ENG HM.kicad_sch](KICAD/19xx%20-%20463-02-020%20-%20AC%20MASTER%20MODULE%20SCHEMATIC%20-%20DRN%20HM%20-%20ENG%20HM.kicad_sch)
- [19xx - 8-109-02-002.kicad_sch](KICAD/19xx%20-%208-109-02-002.kicad_sch)
- [19xx - 8-109-02-007.kicad_sch](KICAD/19xx%20-%208-109-02-007.kicad_sch)
- [19xx - M463 - DOC - 463-02-009 - SUBMA STER MODULE SCHEMATIC.kicad_sch](KICAD/19xx%20-%20M463%20-%20DOC%20-%20463-02-009%20-%20SUBMA%20STER%20MODULE%20SCHEMATIC.kicad_sch)
- [19xx - M463 - DOC - 463-02-019 - SUBMASTER MODULE SCHEMATIC.kicad_sch](KICAD/19xx%20-%20M463%20-%20DOC%20-%20463-02-019%20-%20SUBMASTER%20MODULE%20SCHEMATIC.kicad_sch)
- [19xx - M463 - DOC - 463-02-020 - BYBTEMB DALHM EHNE.kicad_sch](KICAD/19xx%20-%20M463%20-%20DOC%20-%20463-02-020%20-%20BYBTEMB%20DALHM%20EHNE.kicad_sch)
- [M463.kicad_sym](KICAD/M463.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
