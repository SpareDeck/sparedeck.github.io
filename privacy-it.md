---
title: Informativa sulla privacy di SpareDeck
permalink: /privacy-it
lang: it
---

# Informativa sulla privacy di SpareDeck

_In vigore dal 10 novembre 2026_ · [English](privacy)

SpareDeck trasforma un telefono o tablet inutilizzato in una pulsantiera per il tuo computer. È composto da due parti: l'**app SpareDeck** per Android (e una pagina web per gli altri dispositivi) e il **server SpareDeck** che installi sul tuo Mac o PC Windows.

**In breve:** SpareDeck non ha account, pubblicità, statistiche d'uso né tracciamento. Lo sviluppatore non gestisce server e non riceve nessun tuo dato. Il telefono comunica solo con il tuo computer, sulla tua rete locale.

## 1. Cosa salva l'app Android

Solo sul tuo dispositivo:

- i computer abbinati: nome, indirizzo di rete, porta, impronta del certificato e il token di accesso che il tuo computer ha dato a questo dispositivo;
- l'ultimo computer usato.

Questi dati non finiscono nei backup cloud (`allowBackup` disattivato). Toccando **Rimuovi** su un computer, o disinstallando l'app, vengono cancellati.

## 2. A cosa si collega l'app Android

- **Solo ai computer della tua rete locale** su cui gira SpareDeck. Li trova con la ricerca in rete locale (mDNS). Le connessioni usano HTTPS con un certificato creato sul tuo computer; ogni nuovo dispositivo va approvato sul computer.
- L'app invia al computer i comandi che tocchi e il **livello della batteria** del dispositivo (mostrato nel riquadro Batteries del computer).
- Non si collega a nessun server dello sviluppatore.

## 3. Permessi

| Permesso | A cosa serve | Dove vanno i dati |
|---|---|---|
| Fotocamera | La scheda **Phone**, solo quando la avvii: la fotocamera del dispositivo diventa una webcam per il computer. | Inviata direttamente al computer abbinato sulla rete locale. L'app non la salva. |
| Microfono | La scheda **Phone**, solo quando la avvii: il dispositivo diventa un microfono per il computer. | Inviato direttamente al computer abbinato sulla rete locale. L'app non lo salva. |
| Stato rete / Wi-Fi, multicast | Trovare i tuoi computer sulla rete locale. | Restano sulla rete locale. |
| Vibrazione | L'allarme del timer. | — |

Fotocamera e microfono vengono chiesti solo al primo uso di quelle funzioni, e puoi negarli o revocarli quando vuoi dalle impostazioni di Android.

## 4. Servizi di terze parti usati dall'app Android

- **Scansione del codice QR:** il pulsante **Scansiona QR** usa lo scanner di Google Play services. L'immagine viene elaborata sul dispositivo e l'app non ottiene mai l'accesso alla fotocamera per questo. Google Play services può raccogliere dati diagnostici secondo l'[informativa di Google](https://policies.google.com/privacy?hl=it).

## 5. Il server SpareDeck sul tuo computer

Salva le impostazioni, la disposizione dei tasti, l'elenco dei dispositivi approvati (i token sono salvati solo come hash) e un log nella cartella `.sparedeck` del tuo utente. Oltre ai tuoi dispositivi, contatta questi servizi:

- **Meteo:** se non imposti una città, ricava la posizione approssimativa della tua connessione con [ipapi.co](https://ipapi.co/privacy/) (o [ipwho.is](https://ipwho.is) come riserva), che vedono il tuo indirizzo IP pubblico. Poi chiede le previsioni a [Open-Meteo](https://open-meteo.com/en/terms#privacy) con quelle coordinate, o con il nome della città impostata. Impostando una città, la ricerca tramite IP non avviene.
- **Test di velocità Internet:** all'avvio e quando tocchi il riquadro Internet, scarica e invia dati di prova con lo [speed test di Cloudflare](https://www.cloudflare.com/privacypolicy/), che vede il tuo indirizzo IP pubblico.
- **In riproduzione / apertura app / scorciatoie** usano solo le app del tuo computer e non inviano nulla all'esterno.

## 6. Condivisione e vendita

Lo sviluppatore non riceve dati personali, quindi non ne vende né ne condivide. I dati arrivano ai servizi di terze parti indicati sopra solo quando usi la funzione corrispondente.

## 7. Minori

SpareDeck non è rivolto a minori di 13 anni e non raccoglie dati su di loro.

## 8. Scelte e cancellazione

- Su Android: rimuovi un computer dall'app, revoca i permessi dalle impostazioni o disinstalla l'app.
- Sul computer: revoca un dispositivo dal menu nella barra dei menu / area di notifica, oppure cancella la cartella `.sparedeck`.

Poiché lo sviluppatore non conserva dati su di te, non c'è nulla da richiederci: tutto resta sui tuoi dispositivi.

## 9. Modifiche

Se questa informativa cambia, la nuova versione sarà pubblicata a questo indirizzo con una nuova data di entrata in vigore.

## 10. Contatti

Domande: **sparedeckpolicy@protonmail.com**
