
## 📦 Repository Nativo **JÐWØ®LÐ ØS**

### L'alternativa all'AUR è qui.

Benvenuto nel centro di distribuzione ufficiale dei pacchetti per **JDWorld OS**. 

Scarica i pacchetti atomici .jdw ufficiali esenti da AUR e Bloatware ed installali sul tuo Arch Linux (o based Arch Linux) con il **[JDWorld OS Package Manager Universale](https://github.com/JDWorld/jdwos-pm)**

## L'Apocalisse dell'AUR e la reazione della Ragione

Dopo l'attacco della supply chain che ha colpito l'AUR, ho preso l'unica decisione sensata, logica e responsabile: **fare tabula rasa**. Ho piallato ogni PC in rete, cambiato ogni password e ridotto l'architettura all'osso. 

Oggi il mio sistema gira su Arch Linux puro con:
* **956 pacchetti totali** (0 Bloatware)
* **0 pacchetti AUR** (Vade Retro!)
* **0 Flatpak, Snap o AppImage**

## Il formato nativo .jdw

Invece di piangere sulle ceneri di `makepkg`, con l'aiuto di Google AI ho dato vita a un'architettura di packaging proprietaria e modulare. Ogni estensione del mio menù in **[PyQt6](https://jdworld.github.io/jdworldos/jdw_pkg/jdwos-stm)** o per il progetto **JÐWØ®LÐ ØS**, viene compressa in un file `.jdw` che include:
1. `install.sh` - Gestione lineare dell'installazione
2. `remove.sh` - Rimozione atomica senza residui
3. `jdw-package.info` - La scheda tecnica in stile Arch Web

Niente database pesanti, niente rallentamenti, niente compilazioni infinite e nessun repository di terze parti da aggiungere (la logica è integrata nel core). Tutto ciò che serve come dipendenza viene prelevato direttamente dai repository ufficiali stabili di Arch Linux.

### 🛠️ Istruzioni di Installazione/Rimozione rapida

Grazie al nuovo **[JDWorld OS Package Manager Universale](https://github.com/JDWorld/jdwos-pm)**, puoi installare questo pacchetti direttamente dal cloud senza scaricare nulla a mano. Apri il terminale e digita:

```bash
sudo jdw-install nome-pacchetto.jdw
```

Per la rimozione chirurgica:
```bash
sudo jdw-remove nome-pacchetto
```
