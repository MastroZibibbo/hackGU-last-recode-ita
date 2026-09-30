# .hack//G.U. Last Recode — Traduzione italiana

Traduzione italiana completa dei testi di **.hack//G.U. Last Recode** (edizione PC / Steam).

> **Versione 0.9 beta.** Il testo è completo, ma il gioco non è ancora stato collaudato
> in una partita intera. Cerco persone che lo provino e segnalino i difetti — vedi
> [Come segnalare un errore](#come-segnalare-un-errore).

## Da dove viene

Questa traduzione **non parte dall'inglese**: è derivata dalla traduzione spagnola di
**TranScene / [TraduSquare](https://tradusquare.es/)**, realizzata con il loro permesso
esplicito. Sono stati loro a fornire le tool e i file estratti. Il merito del lavoro di
base è tutto loro.

Per il passaggio dallo spagnolo all'italiano mi sono fatto aiutare da un'intelligenza
artificiale, sotto la mia supervisione: ogni scelta di resa è passata da me, con un
glossario tenuto aggiornato per la coerenza dei nomi e un controllo automatico su ogni
stringa per i codici di formattazione e la lunghezza delle righe.

## Cosa è tradotto

Tutto il testo del gioco: dialoghi e cinematiche dei quattro volumi, email, forum Apkallu,
menu, oggetti, equipaggiamento, arti, mostri, luoghi, missioni, trofei, carte di Crimson VS
e il Terminal Disc. Circa **56.000 blocchi di testo**.

Le immagini restano quelle originali inglesi: mostrano già le sigle HP e SP, che sono
quelle usate anche in questa traduzione.

## Requisiti

- .hack//G.U. Last Recode per PC (Steam)
- il file `hackGU_cmn_i.cpk` **originale**, non modificato

Se hai già applicato un'altra traduzione, ripristinalo prima da Steam:
*tasto destro sul gioco → Proprietà → File locali → Verifica integrità dei file di gioco*.

## Installazione

Scarica il pacchetto dalla sezione [Releases](../../releases) ed estrailo.

**Windows** — doppio clic su `installa-windows.bat`. Trova il gioco da solo, fa la copia
di sicurezza e applica la traduzione. Tieni i file della cartella insieme: l'installer usa
`installa-windows.ps1`, `xdelta3.exe` e il file `.xdelta`.

**Linux / Steam Deck** (modalità Desktop) — `bash installa-linux.sh`. Cerca il gioco anche
sulla scheda SD. Su SteamOS serve `xdelta3`, che si installa con
`sudo steamos-readonly disable && sudo pacman -S xdelta3`.

**A mano**, se preferisci:

```
xdelta3.exe -d -s hackGU_cmn_i.cpk hackGU_cmn_i_ITA.xdelta hackGU_cmn_i_nuovo.cpk
```

poi rinomina il file ottenuto in `hackGU_cmn_i.cpk` e mettilo nella cartella `cpk` del
gioco, al posto dell'originale (dopo averlo salvato da parte).

Il file corretto dopo la patch misura **175.024.377 byte**.

I salvataggi restano validi: la patch tocca soltanto i testi.

### Steam Deck

Funziona: la Deck esegue il gioco con Proton, quindi i file sono gli stessi di Windows e
la patch è identica.

## Disinstallazione

Rimetti al suo posto il file `.backup` creato dall'installer, oppure usa la verifica
integrità dei file di gioco su Steam.

## Come segnalare un errore

Servono soprattutto due cose, che si vedono solo giocando:

- **testo che esce dal riquadro** (l'italiano è più lungo dello spagnolo)
- **frasi che in contesto non tornano**

Basta uno screenshot (F12 su Steam) e due parole su dove succede: menu, email, quale scena.
Puoi scrivere nelle [Issues](../../issues) oppure nel thread su Games Translator.

## Crediti

**Traduzione italiana** — MastroZibibbo

**Traduzione spagnola di partenza** — TranScene / [TraduSquare](https://tradusquare.es/)
direzione del progetto: Shiryu · romhacking e strumenti: Hotaru ·
traduzione: Damon, Gerwulf, Óscar73, Shiryu · revisione: Leeg, Shiryu ·
grafica: Nakufox, Shiryu · betatesting: Leeg, Roli300, Shiryu ·
patcher: D3fau4, Leeg, Shiryu

**Strumenti** — GuTool (Artema Translations, per TranScene) · CRI Packed File Maker
(CRI Middleware) · [xdelta](https://github.com/jmacd/xdelta) (Joshua MacDonald, GPL)

**Gioco originale** — CyberConnect2 / BANDAI NAMCO Entertainment

## Note

Traduzione amatoriale, distribuita gratuitamente e senza scopo di lucro. Non è affiliata
né approvata da CyberConnect2 o BANDAI NAMCO Entertainment. Il gioco va acquistato
regolarmente.

La patch è un file di differenze: non contiene materiale originale del gioco e non
funziona senza una copia regolare.
