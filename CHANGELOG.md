# Changelog / Registro modifiche

All notable changes to LobeLab. Versions follow [Semantic Versioning](https://semver.org/).
Entries are in Italian; the application itself is in English and Italian.

Tutte le modifiche rilevanti di LobeLab. Le versioni seguono il [Semantic Versioning](https://semver.org/lang/it/).

## [Unreleased]
- Avvisi di nuova versione **su richiesta**: nel piè di pagina "🔔 Avvisami quando esce una nuova versione" attiva una notifica di sistema del browser (con il permesso dell'utente) quando sul sito compare una versione più recente. Il controllo usa il nuovo file `version.json` e avviene solo per chi ha attivato l'avviso.
- Numero di versione spostato dall'intestazione al piè di pagina, nella riga del copyright.
- Sotto il visualizzatore, al posto della spiegazione della scala colori, una scheda **Storia e approfondimenti** per ogni antenna (EN/IT), con il link a Wikipedia (voce italiana dove esiste, altrimenti inglese) e il rimando a *The ARRL Antenna Book*.
- Rimosso il titolo "Visualizzatore"; la nota sulla scala dBi passa nelle "Note sul modello".
- Sottotitolo che evidenzia lo scopo didattico: "Educational antenna radiation pattern simulator" / "Simulatore didattico di diagrammi di radiazione".
- Frase introduttiva riscritta senza il numero di antenne: descrive cosa fa la pagina (confronto in 3D dei diagrammi di radiazione, scala dB o dBi, sezione, antenna immagine).
- Ringraziamenti ad A.R.I. – Associazione Radioamatori Italiani e ai docenti del Corso Nazionale Aspiranti Radioamatori 2026: riga nel piè di pagina (EN/IT) e sezione nel README. Nella versione italiana il nome del corso è un link alla pagina del corso.

## [1.10.0] - 2026-10-16
- Interruttore **Scala assoluta (dBi)**: una scala comune a tutte le antenne, da −20 a +20 dBi, con moltiplicatori rispetto all'isotropica. Ogni solido è scalato sul guadagno di picco indicativo riportato nella descrizione.
- Descrizioni aggiornate: dipolo lungo ~7,5 dBi, loop magnetico ~−3 dBi, Yagi 3 e 9 elementi con il valore sopra il suolo (~11 e ~16 dBi) e, tra parentesi, quello in spazio libero.
- Pulsante **Salva immagine** (e tasto `S`): esporta in PNG la vista corrente con nome, descrizione, scala colori e crediti.
- **Tema scuro** di default; la scelta del tema viene ricordata.

## [1.9.0] - 2026-10-16
- Interfaccia in **inglese** di default, con l'**italiano** disponibile.
- Selettore della lingua con bandierine in alto a destra; la scelta viene ricordata e si può forzare con `?lang=it` / `?lang=en`.
- Tradotti anche nomi e descrizioni delle antenne, suggerimenti dei pulsanti ed etichette per l'accessibilità; numeri nel formato della lingua (0.5 / 0,5).

## [1.8.0] - 2026-10-16
- Il programma prende il nome **LobeLab** e viene preparato per la pubblicazione su GitHub.
- Autore: BBerry2020, con link al profilo GitHub.

## [1.7.0] - 2026-10-16
- Antenna e antenna immagine visibili solo in sezione.
- Tratto più sottile e tenue, in grigio scuro, coerente con il resto del disegno.

## [1.6.0] - 2026-10-16
- Antenna più leggibile in sezione: sempre in primo piano sul solido.
- Punto di alimentazione evidenziato; antenna immagine con bordo.

## [1.5.0] - 2026-10-16
- Aggiunto il **dipolo a V cornuta** (bracci a 90° rivolti verso l'alto, centro a λ/2). Ora le antenne sono 13.
- Il gruppo "Filari orizzontali" diventa "Dipoli filari".

## [1.4.0] - 2026-10-16
- A schermo intero: menu a tendina per scegliere l'antenna, raggruppato per tipologia.
- A schermo intero: interruttori Sezione, Immagine e Rotazione; fascia in basso con descrizione e legenda su due righe.
- Tutti i comandi restano sincronizzati con la pagina.
- Scala colori: accanto ai dB il moltiplicatore di potenza (×1, ×0,5, ×0,1, ×0,01, ×0,001).

## [1.3.0] - 2026-10-16
- Antenne riordinate dalla più semplice alla più complessa e raggruppate per tipologia.
- All'apertura si parte dall'isotropica in rotazione automatica.
- Zoom (pulsanti, rotella, pizzico su touch, tasti + − 0) e schermo intero (pulsante o tasto F).
- Su telefono la scala colori va sotto il solido e la vista si adatta ai riquadri verticali.

## [1.2.0] - 2026-10-16
- Licenza CC BY-SA 4.0; attribuzione suggerita; testo completo della licenza MIT di three.js.

## [1.1.1] - 2026-10-16
- Rimossa l'icona della pagina (favicon), da rifare.

## [1.1.0] - 2026-10-16
- Avvertenza sull'uso didattico; rimossa la nota sui simulatori NEC.

## [1.0.1] - 2026-10-16
- Correzione: la pagina non si blocca se il browser non offre `console.info` o altri metodi della console.

## [1.0.0] - 2026-10-16
- Prima versione: visualizzatore 3D di 12 antenne, scala colori in dB, vista in sezione, antenna immagine.

[1.10.0]: https://github.com/BBerry2020/lobelab/releases/tag/v1.10.0
[1.9.0]: https://github.com/BBerry2020/lobelab/releases/tag/v1.9.0
