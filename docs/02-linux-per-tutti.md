# 🐧 Linux per tutti

## Cos'è Linux?

Linux è un **kernel**, il cuore di un sistema operativo. Intorno a questo kernel esistono centinaia di **distribuzioni** (dette anche "distro") che aggiungono programmi, interfacce grafiche e strumenti per creare un sistema operativo completo.

A differenza di Windows o macOS, Linux è:
- **Libero** — puoi installarlo su quanti PC vuoi, senza licenze
- **Aperto** — chiunque può vedere come funziona e modificarlo
- **Personalizzabile** — puoi scegliere esattamente come vuoi che si presenti e si comporti il tuo sistema

---

## Scegliere la distribuzione giusta

Una delle domande più comuni è: "Quale distro devo installare?"

La risposta dipende da tanti fattori:
- Quanta esperienza hai con i computer in generale
- Se hai mai usato il terminale
- Che hardware hai (un PC vecchio o nuovo?)
- Cosa vuoi fare con Linux (programmare, giocare, navigare, fare musica...)
- Quanto tempo vuoi dedicare alla configurazione iniziale

### Tipi di distribuzioni (in generale)

| Tipo | Caratteristiche | Esempi |
|------|-----------------|--------|
| Per principianti | Installazione guidata, interfaccia familiare, grande community | Ubuntu, Linux Mint, Zorin OS |
| Per chi vuole stabilità | Software testato, aggiornamenti lenti ma sicuri | Debian, Rocky Linux |
| Per chi ama personalizzare | Installazione minima, controllo totale | Arch Linux, Gentoo |
| Per hardware vecchio | Leggere, pensate per PC con poche risorse | Lubuntu, Xubuntu, Puppy Linux |
| Per il gaming | Driver preinstallati, ottimizzazioni per giocare | Pop!_OS, Nobara |
| Per scopi specifici | Pensate per hacking, privacy, multimedia, ecc. | Kali Linux, Tails, Ubuntu Studio |

### Come scegliere?

**Non esiste una distribuzione "migliore in assoluto".** Quella giusta per te dipende da cosa cerchi.

Il modo migliore per scegliere è:
1. **Raccontaci cosa cerchi** — sul nostro Discord o Reddit
2. **Spiega che hardware hai** (PC vecchio o nuovo? quanta RAM?)
3. **Dicci cosa vuoi fare** (giocare? programmare? solo navigare?)

I membri del club ti aiuteranno a trovare la distro più adatta alle tue esigenze.

> 💡 **Consiglio:** Se hai un PC con Windows e vuoi provare Linux senza cancellare nulla, puoi iniziare con una **macchina virtuale** (tipo VirtualBox) o creare una **chiavetta USB avviabile** per provare Linux senza installarlo.

---

## Installazione

Una volta scelta la distribuzione, ecco i passaggi principali per installarla.

### Metodi di installazione

| Metodo | Descrizione | Difficoltà |
|--------|-------------|------------|
| Macchina virtuale | Linux gira dentro una finestra su Windows/macOS. Non modifica il tuo sistema. | Facile |
| Live USB | Avvii Linux da una chiavetta USB senza installare. Puoi provarlo e poi decidere. | Facile |
| Dual boot | Linux si affianca a Windows/macOS. All'accensione scegli quale avviare. | Media |
| Installazione completa | Linux diventa l'unico sistema operativo sul PC. | Media |

### Guida rapida all'installazione (generale)

1. **Scarica l'ISO** della distribuzione scelta dal sito ufficiale
2. **Crea una chiavetta USB avviabile** usando strumenti come:
   - **Rufus** (Windows)
   - **BalenaEtcher** (Windows, macOS, Linux)
   - **Ventoy** (più avanzato, permette di mettere più ISO su una chiavetta)
3. **Avvia il PC dalla chiavetta USB** (di solito premendo F12, ESC o Canc all'accensione)
4. **Prova Linux in modalità live** (se la distro lo permette)
5. **Segui l'installatore** — scegli lingua, fuso orario, opzioni di partizionamento
6. **Riavvia** e rimuovi la chiavetta

> ⚠️ **Importante:** Se fai dual boot o installazione completa, **fai sempre un backup dei dati importanti** prima di iniziare.

---

## Terminale base

Il terminale è lo strumento più potente di Linux. Non averne paura — con pochi comandi si fanno già tantissime cose.

### Comandi essenziali

| Comando | Cosa fa | Esempio |
|---------|---------|---------|
| `pwd` | Mostra in che cartella sei | `pwd` → `/home/mario` |
| `ls` | Elenca file e cartelle | `ls -la` (dettagliato) |
| `cd` | Cambia cartella | `cd Documenti` |
| `mkdir` | Crea una nuova cartella | `mkdir progetti` |
| `rm` | Elimina file | `rm vecchio.txt` |
| `cp` | Copia file | `cp file.txt backup/` |
| `mv` | Sposta o rinomina | `mv vecchio.txt nuovo.txt` |
| `sudo` | Esegue un comando come amministratore | `sudo apt update` |
| `apt` | Gestisce i pacchetti (su Debian/Ubuntu) | `sudo apt install firefox` |

### Dove trovare aiuto

- `comando --help` — mostra le opzioni di base del comando
- `man comando` — apre il manuale completo (premi `q` per uscire)
- **Su Discord** — nel canale #🐧-linux-help puoi chiedere tutto ciò che vuoi

---

## Risoluzione problemi comuni

### "Linux non rileva il Wi-Fi"
- Alcuni chipset Wi-Fi richiedono driver proprietari
- Collega un cavo ethernet e cerca "driver [modello scheda] Linux"
- Su Ubuntu/Mint: vai in "Software e aggiornamenti" → "Driver aggiuntivi"

### "Schermo nero all'avvio"
- Può essere un problema con la scheda video NVIDIA
- Prova ad avviare con `nomodeset` (cerca su Google la procedura per la tua distro)

### "Non trovo un programma che usavo su Windows"
- Cerca l'alternativa open source: es. Photoshop → GIMP, Office → LibreOffice
- Alcuni programmi Windows girano con **Wine** o **Bottles**
- Per il gaming: **Steam** con Proton fa girare molti giochi Windows

### "Il terminale dice 'comando non trovato'"
- Il programma non è installato: cerca con `apt search [nome]` o equivalente
- Oppure hai sbagliato a scrivere — il terminale è molto preciso

---

## Dove approfondire

| Risorsa | Descrizione |
|---------|-------------|
| Il nostro Discord | Canale #🐧-linux-help — chiedi quello che vuoi |
| Il nostro Reddit | r/linuxistianonimi — discussioni e domande pubbliche |
| Arch Wiki | La wiki di Arch Linux è una delle migliori fonti di conoscenza, anche se non usi Arch |
| The Linux Documentation Project | Guide storiche e complete |
| YouTube | Cerca "Linux per principianti" — ci sono tantissimi tutorial in italiano |

---

Hai domande? Passa su Discord o Reddit e chiedi pure. Nessuna domanda è troppo semplice.

---

Ultimo aggiornamento: 21/04/2026**
