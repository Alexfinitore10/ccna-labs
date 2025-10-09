# Automation Intro Lab

## Obiettivo
REST/JSON; backup config con Ansible (concettuale)

## Topologia & Requisiti
- Simulator: Packet Tracer / EVE-NG / GNS3
- Dispositivi: <S1, S2, R1, ...>
- Diagramma: `diagram.png`
- File lab: `topology.pkt` (o .unl/.net)

## Passi Operativi
1. <configura VLAN 10/20 e trunk 802.1Q>
2. <crea SVI e abilita ip routing>
3. <verifica con ping/traceroute>

## Comandi Utili
Vedi `commands.txt`

## Verifiche
- [ ] Ping tra host VLAN 10 ↔ VLAN 20
- [ ] `show interfaces trunk` corretto
- [ ] `show ip route` con rotte corrette

## Risultati
- Screenshot: `results/`
- Capture: `results/*.pcap`

## Troubleshooting
- <errori comuni e fix>
