# ccna-labs

Template di laboratorio **CCNA 200-301** (intensivo, 6 settimane) pensato per:
- organizzare i tuoi lab per **argomento** (VLAN, OSPF, NAT, ACL, ecc.)
- documentare **passi, comandi, verifiche** e **troubleshooting**
- creare un **portfolio pubblico** da mostrare su GitHub e ai recruiter

> Suggerimento: mantieni ogni lab **riproducibile** (topologia, config, output `show`, screenshot/pcap) e chiudi con una **checklist** di criteri di completamento.

## Struttura
```
ccna-labs/
├── README.md
├── .gitignore
├── LICENSE
├── docs/
│   └── CONTRIBUTING.md
├── templates/
│   ├── README_lab_template.md
│   ├── commands_template.txt
│   └── checklist_template.md
└── labs/
    ├── 01_Network_Fundamentals/
    ├── 02_LAN_Switching/
    ├── 03_Routing_OSPF/
    ├── 04_IP_Services/
    ├── 05_Security/
    ├── 06_Wireless/
    └── 07_Automation/
```

## Come usare il template
1. Duplica una cartella **lab esempio** oppure usa i **template**:
   - `templates/README_lab_template.md` → copia in `labs/<area>/<nome_lab>/README.md`
   - `templates/commands_template.txt` → copia in `.../commands.txt`
   - `templates/checklist_template.md` → copia in `.../CHECKLIST.md`
2. Salva i file **Packet Tracer** (`.pkt`) o EVE-NG/GNS3 nella cartella del lab.
3. Aggiungi **screenshot** e **pcap** in `results/`.
4. Spunta la **checklist** prima di passare al lab successivo.

## Quick start (GitHub)
```bash
git init
git add .
git commit -m "feat: inizializza ccna-labs template"
git branch -M main
git remote add origin https://github.com/<tuo-utente>/ccna-labs.git
git push -u origin main
```

## Licenza
MIT — vedi `LICENSE`.
