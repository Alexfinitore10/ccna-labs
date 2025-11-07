# VLAN InterVLAN Lab

## Obiettivo
Spanning Tree Protocol study and test of all commands and optional features

## Topologia & Requisiti
- Simulator: Packet Tracer / EVE-NG / GNS3
- Dispositivi: <S1, S2, ...>
- Diagramma: `diagram.png`
- File lab: `topology.pkt`

## Passi Operativi
1. <studia come è stato deciso di svilupparsi il protocollo STP>
2. <Cambia il root bridge per ogni VLAN e tutte le porte>
3. <Utilizza le feature opzionali come il portfast o il bpdguard-loopguard-bpdfilter>

## Comandi Utili
Vedi `commands.txt`

## Verifiche
- [ ] Controlla lo spanning tree di ogni switch
- [ ] cambia il root bridge e inseriscilo come secondario o primario per VLAN
- [ ] inserisci il fastport e bpdguard per le porte che non hanno bisogno di inviare BPD message

## Risultati
- Screenshot: `results/`

## Troubleshooting
- <network performance or reachability performance for reaching other pcs on other vlans or internet>
