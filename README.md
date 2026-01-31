<<<<<<< HEAD
# 🤖 Alias O'Matic v1.4

> "Perché editare file di configurazione a mano è roba da paleolitico."

**Alias O'Matic** è un gestore di alias leggero e arrogante basato su TUI (`whiptail`). È nato sull'EVA-00 (un Dell Precision 3591 con Arch Linux) per risolvere un problema semplice: rendere gli alias **immediati**, **persistenti** e **puliti**.

---

## 🔥 Perché è meglio degli altri?

1. **Sincronizzazione Totale**: Grazie al wrapper `am`, ogni alias creato è disponibile *istantaneamente* nella shell attuale. Niente più `source ~/.bashrc` manuale.
2. **Rimozione Chirurgica**: Quando elimini un alias, lo script usa `unalias` per disintegrarlo anche dalla memoria RAM della shell corrente. Niente "alias fantasma".
3. **Protezione Anti-Fail**: Controlla se il nome scelto collide con comandi di sistema esistenti.
4. **Auto-Installante**: Lo lanci una volta e lui si preoccupa di agganciarsi al tuo `.bashrc` o `.zshrc`.

---

## 🛠 Installazione Rapida

1. Scarica lo script e rendilo eseguibile:
```bash
sudo curl -L [https://raw.githubusercontent.com/TUO_USERNAME/alias-o-matic/main/aliasomatic](https://raw.githubusercontent.com/TUO_USERNAME/alias-o-matic/main/aliasomatic) -o /usr/local/bin/aliasomatic
sudo chmod +x /usr/local/bin/aliasomatic

    Avvialo per la prima configurazione:

Bash

aliasomatic

    La Magia: Chiudi il terminale e riaprilo. Da questo momento, usa solo il comando:

Bash

am

⚙️ Come funziona (Sotto il cofano)

Alias O'Matic non sporca il tuo .bashrc. Crea un file dedicato ~/.aliasomatic dove risiedono i tuoi comandi. Il comando am è un alias di sistema che esegue lo script in modalità source, permettendo una comunicazione diretta tra lo script e l'ambiente della shell. Lo script gestisce i conflitti e assicura che la rimozione sia effettiva anche nella sessione volatile della shell.
🤝 Contributi

Se vuoi aggiungere funzioni o hai trovato un bug, apri una Pull Request. Ma non venire a piangere se chiami un alias rm e poi ti cancelli la Home. Sii un vero Socio, sii responsabile.

Sviluppato con orgoglio da Simone & Gemini (Il Socio IA). Basato sulla cultura pop degli ultimi 40 anni e su tanta voglia di non scrivere comandi lunghi.

=======
# alias-o-matic
"The ultimate TUI Alias Manager for Bash/Zsh. Born on Arch Linux, built for efficiency, zero-bullshit guaranteed."
>>>>>>> 86058cbaa1e03ae15aff94366bacb422210efa9d
