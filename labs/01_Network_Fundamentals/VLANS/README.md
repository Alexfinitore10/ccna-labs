# VLAN creation LAb
## Obiettivo
Creare delle VLAN in un piccolo network e fare in modo che ogni pc di vlan diversa comunichi

## Topologia & Requisiti
- Simulator: Packet Tracer
- Dispositivi: <S1, S2, R1, ...>
- Immagine: `/results/topology.png`
- File lab: `Day 16 Lab - VLANs (Part 1).pkt`

## Passi Operativi
1. Configurare l'indirizzo IP/subnet mask corretti su ciascun PC.
Impostato l'indirizzo del gateway come ULTIMO indirizzo UTILIZZABILE della subnet.

2. Create tre connessioni tra R1 e SW1.
Configurato un'interfaccia su R1 per ciascuna VLAN.

3. Configurare le interfacce di SW1 nelle VLAN appropriate.
Memorizzare le interfacce che si connettono a R1!
Nominare le VLAN
(Ingegneria, Risorse Umane, Vendite)

4. Eseguito un ping tra i PC per verificare la connettività.
Inviato un ping broadcast da un PC (pingato l'indirizzo di broadcast della subnet)
e verificato quali dispositivi PC ricevono il broadcast
(utilizzato la "Modalità Simulazione" di Packet Tracer)


## Comandi Utili
Vedi `commands.md`

## Verifiche
- [x] Ping tra due host

## Risultati
- Screenshot: `results/image.png`