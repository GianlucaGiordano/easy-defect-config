# Informativa sulla privacy di easy-defect

Ultimo aggiornamento: 25 settembre 2026

easy-defect è un'estensione per Chrome che aiuta i tester a creare segnalazioni
di bug frontend e a inviarle al proprio tracker dei difetti.

## In breve

Lo sviluppatore di easy-defect **non riceve, non raccoglie e non conserva alcun
dato degli utenti**. L'estensione non ha un server proprio, non usa statistiche
d'uso né strumenti di tracciamento. I dati restano nel browser dell'utente
finché è l'utente stesso a inviarli al tracker che ha configurato.

## Dati trattati dall'estensione

Per svolgere la sua unica funzione, l'estensione tratta nel browser
dell'utente:

- **Contenuti del sito web**: screenshot della pagina e chiamate di rete
  fallite (status 4xx/5xx o errore di rete) con request e response complete,
  compresi gli header.
- **Attività dell'utente**: le ultime interazioni nella scheda (click, campi
  selezionati, navigazioni), usate per generare i passi di riproduzione. I
  valori digitati nei campi password non vengono mai registrati.
- **Informazioni di autenticazione**: l'utenza di test indicata dal tester nel
  report e il cookie di sessione del tracker, letto solo per autorizzare
  l'invio del report.
- **Impostazioni**: l'indirizzo del tracker e l'elenco degli host di test,
  salvati nella memoria locale del browser.

## Dove vanno i dati

I dati di una segnalazione vengono inviati **solo** quando l'utente preme
"Invia", e **solo** al tracker dei difetti configurato dall'utente (Rational
Team Concert), usando la sessione con cui l'utente è già autenticato. Quel
servizio è scelto e gestito dall'utente o dalla sua organizzazione e segue la
propria informativa sulla privacy.

L'estensione legge inoltre un file di configurazione pubblico per sapere se
può funzionare. La richiesta non contiene dati dell'utente.

I dati non vengono venduti, ceduti a terzi né usati per scopi diversi dalla
creazione della segnalazione.

## Conservazione

Le chiamate di rete e le interazioni restano in memoria nella scheda e vengono
cancellate all'invio della segnalazione o alla chiusura della pagina. Le
impostazioni restano nel browser finché l'utente non le modifica o non
disinstalla l'estensione.

## Uso previsto

easy-defect è pensata esclusivamente per ambienti di test. Poiché registra il
traffico di rete senza oscurarlo, non va usata su ambienti di produzione né
con dati personali reali.

## Modifiche

Eventuali modifiche a questa informativa saranno pubblicate su questa pagina,
con la data di aggiornamento.

