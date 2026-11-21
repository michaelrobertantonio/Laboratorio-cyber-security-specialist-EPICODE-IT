[README.md](https://github.com/user-attachments/files/35202935/README.md)
# Laboratorio Cyber Security Specialist — EPICODE 2024

Raccolta di esercitazioni pratiche svolte durante il percorso di studi **Cyber Security Specialist** con **EPICODE** (2024). I laboratori coprono networking, penetration testing, web security, analisi malware, reverse engineering, programmazione in C e governance (Business Continuity / Disaster Recovery).

## Nota metodologica

Ogni laboratorio è stato eseguito da me in prima persona durante il percorso con EPICODE: comandi, configurazioni, exploit e risultati sono frutto del mio lavoro. Ho scritto io anche le relazioni originali di ciascun laboratorio. La loro impaginazione, uniformità grafica e correzione grammaticale sono state realizzate con il supporto di uno strumento di intelligenza artificiale, a partire dai miei testi e screenshot originali.

## Struttura del repository

| Cartella | Contenuto |
|---|---|
| `01-Networking` | Subnetting, analisi IP, cattura e analisi traffico con Wireshark, scansione di rete con NMap |
| `02-Pentest` | Exploit con Metasploit (Windows XP, Telnet, vsftpd backdoor, Java RMI), attacco bruteforce con Hydra |
| `03-Web-Security` | SQL Injection (blind), XSS stored, mitigazioni per XSS e SQL Injection |
| `04-Malware-e-Reverse` | Analisi statica di malware, costrutti e debugging in Assembly, analisi argomenti di `main` in C, buffer overflow in C |
| `05-Governance` | Business Continuity Plan, Business Impact Analysis, Disaster Recovery Plan, progettazione di rete e preventivo |
| `06-Programmazione` | Calcolatrice, mini-videogioco, debugging in C |

## Elenco laboratori

| Laboratorio | Strumenti | Tipo |
|---|---|---|
| Esercitazione sul calcolo di subnet IP | Calcolo manuale | Individuale |
| Analisi del traffico di rete con Wireshark | Wireshark | Individuale |
| Scansione di rete con NMap | NMap | Individuale |
| Exploit MS08-067 su Windows XP | Metasploit | Individuale |
| Exploit del servizio Telnet | Metasploit | Individuale |
| Exploit backdoor vsftpd 2.3.4 | Metasploit | Individuale |
| Exploit vulnerabilità Java RMI (porta 1099) | Metasploit | Individuale |
| Attacco di bruteforce con Hydra | Hydra | Individuale |
| SQL Injection (blind) e XSS stored su DVWA | Burp Suite, sqlmap | Individuale |
| Mitigazione di attacchi XSS e SQL Injection | — | Individuale |
| Analisi statica di un file malware | CFF Explorer, md5deep | Individuale |
| Costrutti di un programma in Assembly | CFF Explorer | Individuale |
| Analisi malware: salti condizionali e diagramma di flusso | IDA (concettuale) | **Gruppo** |
| Analisi degli argomenti della funzione `main` in C | — | Individuale |
| Buffer Overflow in un programma C | GCC | Individuale |
| Programmazione di una calcolatrice in C | GCC | Individuale |
| Programmazione di un mini-videogioco in C | GCC | Individuale |
| Debugging di un programma in C | GCC | Individuale |
| Business Continuity Plan e Disaster Recovery Plan | — | **Gruppo** |
| Progettazione di rete e preventivo per un'azienda | — | Individuale |

I laboratori di gruppo riportano i nomi di tutti i componenti del team; il mio contributo è specificato nel rispettivo documento.

## Competenze esercitate

- Networking e subnetting
- Penetration testing con Metasploit, Hydra, sqlmap
- Analisi del traffico di rete (Wireshark, NMap)
- Analisi statica di malware e reverse engineering (Assembly, CFF Explorer)
- Programmazione in C e debugging
- Business Continuity, Business Impact Analysis, Disaster Recovery

## Ambiente di laboratorio

Tutti gli attacchi e gli exploit documentati sono stati eseguiti in un ambiente di laboratorio isolato (macchine virtuali Kali Linux, Metasploitable, Windows XP, DVWA), a scopo didattico nell'ambito del percorso EPICODE.
