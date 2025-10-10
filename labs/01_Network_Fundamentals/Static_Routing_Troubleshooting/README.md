# Static Routing Troubleshooting Lab

## Obiettivo
Troubleshooting di static routing, dove due pc su reti diverse non riescono a connettersi tra di loro.

## Topologia & Requisiti
- Simulator: Packet Tracer
- Dispositivi: <S1, S2, R1, ...>
- Immagine: `/results/ping riuscito.png`
- File lab: `topology.pkt`

## Passi Operativi
Pc 1 e 2 non si riescono a pingarsi tra di loro

- Le interfacce del router 1 sono corrette, gli ip corrispondono alla loro interfaccia e sono up up
- S    192.168.3.0/24 [1/0] via 192.168.12.3
- Il problema sembra essere questa static route, che punta a un ip che non esiste all'interno della topologia il .3 .
- Ho eliminato il comando e impostato la rotta corretta
- Per il router 2, il rpoblema è che è stato sbagliata l'interfaccia di comunicazione per la LAN .3.0, ho proceduto a eliminare il      comando e a impostare la rotta corretta
- Per il router 3 le rotte sono corrette tranne l'ip dell'interfaccia che è completamente errato, l'ho modificato per renderlo conforme alla topologia.

- Ora i computer si riescono a connettere.


## Comandi Utili
Vedi `commands.md`

## Verifiche
- [x] Ping tra due host

## Risultati
- Screenshot: `results/`