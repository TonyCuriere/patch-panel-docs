# Patch panel – Documentazione rack

Tool web per documentare i **patch panel** di un armadio rack e stampare un foglio **A4 orizzontale** da attaccare al rack.

È un singolo file HTML: nessuna installazione, nessun server, nessun account. I dati restano nel tuo browser.

**▶ Usalo online:** https://tonycuriere.github.io/patch-panel-docs/

## Funzionalità

- **Più patch panel per rack**, da 1 a 48 porte ciascuno, con nome e numerazione continua o ripartita da 1. Oltre le 72 porte il documento prosegue su più fogli, senza mai spezzare un pannello.
- **Disegno del prospetto frontale** generato automaticamente; le porte patchate sono barrate. Clic su una porta del disegno per compilarla.
- **Tabella per ogni porta**: etichetta (dove porta), porta switch, stato patch.
- **Porte switch predefinite** (1/0/1…1/0/48, 2/0/1… per ogni switch dello stack), modificabili a mano.
- **Più documenti** salvati automaticamente nel browser (`localStorage`), con duplicazione e cambio rapido.
- **Importa / Esporta** in JSON, per backup o per passare i documenti a un collega.
- **Stampa o salva PDF** direttamente dal browser.

## Come si usa

1. Apri il link qui sopra (oppure scarica `index.html` e aprilo con Chrome, Edge o Firefox).
2. Imposta i patch panel nel pannello laterale: nome, numero di partenza e numero di porte.
3. Compila il foglio: etichette, porte switch e stato patch (clic sulla cella **Patch**).
4. Premi **Stampa o salva PDF** e imposta: A4 orizzontale, margini *Nessuno*, scala *100%*.

> I dati sono salvati solo nel browser che stai usando. Usa **Esporta** per farne un backup o spostarli su un altro computer.

## Contribuire

Segnalazioni e proposte sono benvenute: apri una [issue](../../issues) o una pull request.

## Licenza

Distribuito con licenza [MIT](LICENSE).
