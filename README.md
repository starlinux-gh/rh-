# RH+  
**Remote Help Plus — Cross‑Device Remote Assistance Platform**

RH+ è una piattaforma di assistenza remota progettata per funzionare ovunque: Windows, Linux, macOS, Android, Symbian e altri dispositivi.  
Offre autenticazione centralizzata, ruoli distinti (utente e administrator), sessioni sicure e strumenti per installazioni guidate e supporto tecnico.  
Un framework moderno per un accesso remoto etico, controllato e multi‑device.

---

##  Visione del progetto

RH+ nasce per creare un nuovo standard nell’assistenza remota:  
un ecosistema trasparente, sicuro e governabile, dove utenti e amministratori collaborano senza frizioni.

L’obiettivo è fornire un ambiente in cui:

- l’utente mantiene sempre il controllo del proprio dispositivo  
- l’amministratore può intervenire in modo rapido, sicuro e tracciabile  
- la piattaforma garantisce protezione, chiarezza e interoperabilità  

---

##  Caratteristiche principali

- **Supporto multi‑piattaforma**  
  Windows, Linux, macOS, Android, Symbian e altri dispositivi compatibili.

- **Autenticazione centralizzata**  
  Sign‑up, sign‑in e logout con gestione sicura delle sessioni.

- **Ruoli distinti**  
  - *Utente finale*: richiede supporto e concede l’accesso.  
  - *Computer Administrator*: gestisce dispositivi, sessioni e assistenza.

- **Sessioni remote sicure**  
  Avvio solo con consenso esplicito dell’utente, crittografia end‑to‑end, possibilità di interrompere in qualsiasi momento.

- **Installazioni guidate**  
  L’amministratore può assistere l’utente durante setup, configurazioni e troubleshooting.

- **Audit e trasparenza**  
  Log delle sessioni, storico degli accessi, tracciabilità delle operazioni.

---

##  Architettura degli accessi e dei ruoli

### Utente
- Installa il client RH+ sul proprio dispositivo.  
- Effettua sign‑up/sign‑in.  
- Concede o rifiuta l’accesso remoto.  
- Può interrompere la sessione in qualsiasi momento.

### Computer Administrator
- Accede alla console di gestione.  
- Visualizza i dispositivi associati.  
- Richiede l’avvio di una sessione remota.  
- Fornisce supporto tecnico, installazioni e configurazioni.

### Supervisore (opzionale)
- Gestisce policy, permessi e configurazioni globali.  
- Supervisiona l’attività degli amministratori.

---

##  Sicurezza e privacy

RH+ è progettato con un approccio **privacy‑first**:

- Crittografia TLS per tutte le comunicazioni.  
- Possibile crittografia end‑to‑end delle sessioni remote.  
- Nessuna connessione senza consenso esplicito dell’utente.  
- Indicatori visivi chiari durante l’accesso remoto.  
- Log delle sessioni per trasparenza e compliance.  
- Possibilità di revocare dispositivi o sessioni compromesse.

---

##  Piattaforme supportate

### Windows
- Supporto completo per controllo remoto, installazioni e diagnostica.

### Linux
- Supporto per le principali distribuzioni (Ubuntu, Debian, Fedora, Arch).  
- Funzionalità variabili in base ai permessi.

### macOS
- Richiede autorizzazioni di accessibilità e screen recording.

### Android
- Controllo remoto (dove supportato), visualizzazione schermo, assistenza guidata.

### Symbian / Altri
- Funzionalità limitate (monitoraggio, assistenza base).

---

##  Modello di autenticazione

- **Sign‑up**: creazione account, verifica email, associazione dispositivo.  
- **Sign‑in**: autenticazione con token sicuri, supporto 2FA.  
- **Logout**: chiusura sessione locale e invalidazione token.  
- **Sessioni remote**: avvio su richiesta dell’admin, conferma dell’utente.

---

##  Flussi tipici d’uso

### 1. Richiesta di supporto
1. L’utente installa RH+ e accede.  
2. Apre una richiesta di assistenza.  
3. L’amministratore riceve la notifica.  
4. Richiede l’accesso remoto.  
5. L’utente accetta → sessione attiva.

### 2. Gestione dispositivi
- L’amministratore vede lo stato dei device (online/offline).  
- Può avviare sessioni, consultare log, revocare accessi.

### 3. Revoca e sicurezza
- L’utente può revocare un dispositivo associato.  
- L’amministratore può disattivare un device compromesso.

---

##  Installazione (placeholder)

Le istruzioni di installazione verranno aggiunte man mano che i client per le varie piattaforme saranno disponibili.

---

##  Roadmap

- [ ] Definizione API di autenticazione  
- [ ] Prototipo client Windows  
- [ ] Console web per amministratori  
- [ ] Logging e audit  
- [ ] Supporto Android  
- [ ] Crittografia end‑to‑end  
- [ ] Policy avanzate per organizzazioni  

---

##  Licenza

La licenza del progetto sarà definita in una fase successiva.

---

##  Contributi

I contributi sono benvenuti.  
Linee guida per contribuire saranno aggiunte in seguito.

---

##  Missione del progetto

RH+ vuole ridefinire l’assistenza remota come un atto di fiducia reciproca:  
un ambiente dove la tecnologia non invade, ma accompagna;  
dove la sicurezza non limita, ma protegge;  
dove l’utente resta sovrano del proprio dispositivo.

