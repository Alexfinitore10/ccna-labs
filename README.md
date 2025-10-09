# ccna-labs

Template di laboratorio **CCNA 200-301** pensato per:
- organizzare i miei laboratori e cose che ho imparato per **argomento**
- documentare **passi, comandi, verifiche** e **troubleshooting**
- creare un **portfolio pubblico** da mostrare su GitHub

## Status
Day 2 of Week 1

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


## Licenza
MIT — vedi `LICENSE`.
