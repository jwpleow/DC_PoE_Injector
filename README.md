# 802.3at PoE Injector, Mode B, using DC power input

It's too hard to find a midspan injector that takes in DC voltage.. (e.g. Phihong POE30D-1ATP-R / POE20D-1AF-R is a little hard to get a hold of)   

## JLCPCB Manufacturing Notes
Designed for the 4 Layer `JLC04161H-7628` - For 100Ohm impedance - 0.127mm trace spacing, 0.1402mm trace width

## Core Components

### Ethernet
| Part Name | Description | Datasheet | JLCPCB |
| - | - | - | - |
| TPS23861 | 802.3at Quad Port Power-over-Ethernet PSE Controller | [Datasheet](https://www.ti.com/lit/ds/symlink/tps23861.pdf)  | [JLCPCB](https://jlcpcb.com/partdetail/TexasInstruments-TPS23861PWR/C93245) | 
| SM51625EL | LAN 10/100/1000 Base-T (PoE++) Transformer | [Datasheet](https://wmsc.lcsc.com/wmsc/upload/file/pdf/v2/lcsc/2306061201_BOURNS-SM51625EL_C5357757.pdf) | [JLCPCB](https://jlcpcb.com/partdetail/Bourns-SM51625EL/C5357757) |
| R-RJ45R08P-C000 | RJ45, Horizontal, Shielded with LED | [Datasheet](https://wmsc.lcsc.com/wmsc/upload/file/pdf/v2/lcsc/1912111437_Ckmtw-Shenzhen-Cankemeng-R-RJ45R08P-C000_C386757.pdf) | [JLCPCB](https://jlcpcb.com/partdetail/360864-R_RJ45R08PC000/C386757) |


### Power
| Part Name | Description | Datasheet | JLCPCB |
| - | - | - | - |
| TPS7B8233QDGNRQ1 | 2.5-40V input, 3.3V 300mA output LDO | [Datasheet](https://www.ti.com/lit/ds/symlink/tps7b82-q1.pdf)  | [JLCPCB](https://jlcpcb.com/partdetail/TexasInstruments-TLV709A33DBVR/C21574006 ) | 
| LM5155QDSSRQ1 | Boost Converter | [Datasheet](https://www.ti.com/lit/ds/symlink/lm5155-q1.pdf) | [JLCPCB](https://jlcpcb.com/partdetail/TexasInstruments-LM5155QDSSRQ1/C1849528) |

## References
- [TPS23861 Datasheet](https://www.ti.com/lit/ds/symlink/tps23861.pdf)
- [TPS23861 Evaluation Module](https://www.ti.com/lit/ug/sluuay8e/sluuay8e.pdf)
- [TPS23861 Power-On Considerations](https://www.ti.com/lit/an/slva723/slva723.pdf)
- [MAX5945EV Kit](https://www.analog.com/media/en/technical-documentation/data-sheets/MAX5945EVKIT-MAX5945EVSYS.pdf)




