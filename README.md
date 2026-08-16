# Bilancio Casa

Gestionale domestico pensato per iPhone. I dati sono memorizzati esclusivamente nel browser tramite `localStorage`.

## Funzioni

- stipendio e patrimonio iniziale per ogni mese;
- spese fisse, variabili e tempo libero con categorie;
- piano debito da 930 € entro dicembre 2026 (186 € al mese);
- fondo assicurazione da 600 € per maggio 2027 (66,67 € al mese da agosto ad aprile);
- calcolo automatico del budget ancora spendibile;
- archivio dei mesi e riporto del saldo;
- esportazione e importazione del backup JSON;
- icona e configurazione per l'installazione sulla schermata Home.

## Avvio

Richiede Node.js 22 o successivo.

```bash
npm ci
npm run dev
```

Per creare la versione di produzione:

```bash
npm run build
```

Su iPhone aprire il sito in Safari e scegliere **Condividi → Aggiungi alla schermata Home**.

## Dati

La cancellazione dei dati del sito da Safari elimina anche i dati dell'app. Usare regolarmente **Dati → Esporta backup** e conservare il file in iCloud Drive.
