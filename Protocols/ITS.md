**Shen Jean Lim | [Home](https://shenjean.github.io) | [Biography](bio.md) | [Publications](pubs.md) | [News](news.md) | [Contact](contact.md) | [Protocols](protocols.md)**

# Protocol - PCR Protocol 
## Metabarcoding of the fungal internal transcribed spacer (ITS) region

- The fungal/microeukaryotic ITS region will be amplified with ITS3F/4R primers with Fluidigm tags attached to the 5’ end. 
- Primers and thermocycling conditions are based on the [protocol](https://www.zymoresearch.com/products/quick-its-plus-ngs-library-prep-kit-udi)
  for Zymo’s Quick-ITS Plus NGS Library Prep Kit
  
| Primer | Sequence |	Amplicon size | 
| ------ | -------- | ------------ |
| ITS3F  | *[CS1] - GCATCGATGAAGAACGCAG | 250-600 bp |
| ITS4R| **[CS2] - TCCTCCGCTTATTGATATGC | 250-600 bp | 

>*Fluidigm tag [CS1] (ACACTGACGACATGGTTCTACA)  
>**Fluidigm tag [CS2] (TACGGTAGCAGAGACTTGGTCT)

### DNA preparation

If yields are low, PCR reactions can be performed in duplicates or triplicates, then combined and purified.

| Reagent | Volume |
| ------- | ------ |
| PCR-grade water |	7.1 µL |
| AmpliTaq Gold 360 Master Mix (2x)	| 12.5 µL |
| Primer 515F (10 µM)	| 1.2 µL |
| Primer 806R (10 µM)	| 1.2 µL |
| GC enhancer	| 1.0 µL |
| Template DNA	| 2.0 µL |
| Total reaction volume	| 25.0 µL |

### Thermocycling conditions

| Temperature |	Time |	Repeat |
| ------- | ------ | ------ | 
| 95 °C	| 10 min	|
| 95 °C	| 30 s | x35 |
| 55 °C	| 30 s | x35 |
| 72 °C	| 90 s | x35 |
| 72 °C	| 10 min | |	
| 11 °C	| hold	| |

### Post-PCR

- From each reaction, 10 µL of PCR products will be visualized on a 2% (wt/vol) 1xSB agarose gel ran at 170V for 45 minutes
- The gel will be stained with ethidium bromide or SYBR Safe
- DNA samples that did not produce visible PCR products will be re-amplified using the original, undiluted DNA, using more template DNA, or increasing the number of cycles (max 42 cycles)
- PCR products will be purified using the Zymo Clean & Concentrator kits
- Purified PCR products will be quantified using the Qubit DNA HS assay (Invitrogen)
- Purificied PCR products will be diluted to 1-10 ng/uL, arranged in 96-well plate(s) and submitted, along with annotated gel images, for amplicon sequencing on the Illumina MiSeq 2x250 bp platform. 

