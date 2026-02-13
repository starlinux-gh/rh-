# Contributing to RH+

Grazie per il tuo interesse nel contribuire a **RH+**!  
Questo progetto mira a creare una piattaforma di assistenza remota sicura, etica e multi‑device.  
Per mantenere qualità, coerenza e sicurezza, ti chiediamo di seguire le linee guida riportate qui sotto.

---

##  Principi fondamentali

RH+ si basa su tre pilastri:

1. **Sicurezza** — ogni contributo deve rispettare standard elevati di protezione dei dati e delle sessioni remote.  
2. **Trasparenza** — il codice deve essere leggibile, documentato e verificabile.  
3. **Etica** — nessuna funzionalità deve compromettere la privacy o il controllo dell’utente.

---

##  Segnalare un problema (Issue)

Prima di aprire una issue:

- verifica che il problema non sia già stato segnalato  
- includi una descrizione chiara e riproducibile  
- specifica piattaforma, versione, log rilevanti  
- per problemi di sicurezza, **non aprire issue pubbliche**  
  - invia invece una segnalazione privata ai maintainer

### Tipologie di issue accettate

- **Bug report**  
- **Feature request**  
- **Domande tecniche**  
- **Proposte di miglioramento**  
- **Segnalazioni di sicurezza (private)**

---

##  Proporre una Pull Request (PR)

Prima di inviare una PR:

1. Assicurati che esista una issue collegata.  
2. Discuti la soluzione proposta se il cambiamento è significativo.  
3. Mantieni la PR focalizzata su un singolo argomento.  
4. Aggiorna la documentazione se necessario.  
5. Assicurati che il codice sia testato e funzioni su più piattaforme (dove applicabile).

### Linee guida per le PR

- usa un branch dedicato  
- nomina il branch in modo chiaro, es.:

feature/authentication-api
fix/windows-agent-crash
docs/update-readme

- scrivi commit message significativi  
- evita modifiche non correlate nella stessa PR  
- rispetta gli standard di sicurezza del progetto

---

##  Standard di codice

Poiché RH+ è un progetto multi‑piattaforma, gli standard saranno definiti per ogni componente.  
In generale:

- codice leggibile e commentato  
- nessuna dipendenza non necessaria  
- evitare funzioni che possano compromettere privacy o sicurezza  
- seguire le convenzioni del linguaggio usato  
- mantenere una struttura coerente delle cartelle

Gli standard specifici saranno aggiunti man mano che i moduli del progetto prenderanno forma.

---

##  Test e qualità

Ogni contributo deve:

- includere test (dove applicabile)  
- non introdurre regressioni  
- rispettare gli standard di sicurezza  
- essere verificato su almeno una piattaforma target

---

##  Sicurezza

RH+ è un progetto che tratta accesso remoto e controllo dei dispositivi.  
Per questo motivo:

- nessun codice che permetta accessi nascosti o non autorizzati  
- nessuna funzionalità di sorveglianza occulta  
- nessun bypass dei consensi dell’utente  
- nessun logging invasivo o non dichiarato  
- nessuna dipendenza da librerie non affidabili

Le segnalazioni di sicurezza devono essere inviate **privatamente** ai maintainer.

---

##  Codice di condotta

Tutti i contributori devono:

- rispettare gli altri membri della community  
- mantenere un linguaggio professionale  
- evitare comportamenti tossici o discriminatori  
- collaborare in modo costruttivo  
- accettare feedback tecnici senza personalizzazioni

Un file `CODE_OF_CONDUCT.md` sarà aggiunto in seguito.

---

##  Roadmap e discussioni

Le discussioni strategiche avvengono tramite:

- issue etichettate come `discussion`  
- milestone  
- roadmap ufficiale nel README

Se vuoi proporre una nuova direzione, apri una issue di tipo **proposal**.

---

##  Come iniziare

1. Fai un fork della repository.  
2. Crea un branch per la tua modifica.  
3. Implementa la tua soluzione seguendo le linee guida.  
4. Invia una pull request.  
5. Partecipa alla revisione del codice.

---

Hai deciso di contribuire? Se "YES"
Grazie per il contributo a RH+  
La tua partecipazione aiuta a costruire una piattaforma di assistenza remota più sicura, etica e universale.

