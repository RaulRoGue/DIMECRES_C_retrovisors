View this project on [CADLAB.io](https://cadlab.io/project/28966). 

# DIMECRES_C_retrovisors
## Autors
- Nom 1 (@RaulRoGue)
- Nom 2 (@usuariGitHub)
## Versió - v1.0 ## Curs - Assignatura de Disseny de PCBs amb KiCad - [Curs 2024-2025]

## Objectiu
Dissenyar una pcb que controli el plegament/desplegament del retrovisor, l'ajust del mirall amb motors,
la pcb també ha d'incloure un sensor que detecti els punts morts, un calefactor per evitar l'entelament
i una llum indicadora de direcció.

## Requisits i especificacions
- 3 motors (moviment de mirall vertical i horitzontal, i plegat del retrovisor) amb
els seus finals de carrera.
- Calefactor del mirall.
- Sensor digital de detecció d’angle mort i llum indicadora.

## Diagrama de blocs
![Diagrama blocs](DiagramaBloquesV2.svg)
## Taula de components
| Descripció | Manufacturer Number | Package | Datasheet | Proveïdor | Unitats |
|------------|--------------------|---------|----------|----------|---------|
| Driver | L298N | Multipower15 | [Enllaç](https://www.mouser.es/datasheet/2/389/l298-1849437.pdf) | Mouser | 1 |
| Microcontrolador|PIC18F258|SOIC-28|[Enllaç](https://www.mouser.es/datasheet/2/268/41159e-3443038.pdf)| Mouser | 1 |
| CAN Transceiver|TJA1042T/3/CM,118| Soic-8 |[Enllaç](https://www.mouser.es/datasheet/2/302/TJA1042-3103146.pdf)| Mouser | 1 |
| Rele SPDT| FN01B | | [Enllaç](https://docs.rs-online.com/df01/0900766b8158318b.pdf) | RS Amidata | 2 | 
| Rele DPDT | G6S-2F| | [Enllaç](https://docs.rs-online.com/f19f/0900766b813679a7.pdf) | Rs Amidara | 1 | 
| OpAmp | ADA4511-2 | Soic-8 |[Enllaç](https://www.analog.com/media/en/technical-documentation/data-sheets/ada4511-2.pdf) | Analog Devices | 1 |
| Conv. DC/DC Buck | LM2596 | TO-263  | [Enllaç](https://www.ti.com/lit/ds/symlink/lm2596.pdf?ts=1742644968953&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252Fes-mx%252FLM2596) | Texas Instruments | 1 | 
| Regulador | LT1117 | TO-252 | [Enllaç](https://www.ti.com/lit/ds/symlink/lm1117.pdf?ts=1742626115453&ref_url=https%253A%252F%252Feu.mouser.com%252F) | Texas Instruments | 1 |
| Diode Schottky | SS3P5 | SMP | [Enllaç](https://www.vishay.com/docs/88997/ss3p5.pdf)| Mouser | 1 | 
## Funcionalitats
- [ ] Funció 1
- [ ] Funció 2
- [ ] Funció 3

## Historial de canvis 
| Data | Autor | Branch | Descripció |
|------|------|--------|------------| 
| 2025-03-20 | Raul | `main` | Creació del projecte |
| 2025-03-21 | Raul | `main` | LLista materials | 
