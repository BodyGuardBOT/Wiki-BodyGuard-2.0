# WIKI UFFICIALE DI BODYGUARD 2.0

**USCITA VERISONE 2.0 Venerdì alle 18:00**

# **Dashboard Web**

La **Dashboard Web** è l'interfaccia grafica ufficiale di BodyGuard, progettata per offrire una gestione completa e intuitiva del bot direttamente dal browser, senza l'uso di comandi testuali.

**Accesso**

Accedi alla dashboard all’indirizzo: [https://bodyguardbot.net/dashboard](https://bodyguardbot.net/dashboard)

**Funzionalità disponibili**

Una volta effettuato il login con Discord, potrai:

* Gestire i moduli di protezione: Anti-Raid, Anti-Link, Anti-Nuke
* Configurare Staff Guard con whitelist e permessi personalizzati
* Creare e ripristinare backup in pochi clic
* Attivare o gestire il piano Premium
* Monitorare i log degli eventi e ricevere notifiche importanti

**A chi è rivolta**

La dashboard è pensata per tutti gli utenti, anche senza esperienza tecnica. Ogni sezione include descrizioni chiare e impostazioni guidate.

> Usa la Dashboard per avere il pieno controllo del tuo server in modo semplice, veloce e visivo.

Una procedura guidata ti assiste passo dopo passo nella configurazione del bot direttamente su Discord.

# FUNZIONI

# **Anti-Raid**

Il modulo Anti-Raid rileva automaticamente attività sospette legate a un afflusso anomalo di utenti o a comportamenti tipici degli attacchi di massa. Quando attivato, il sistema può:

* Rilevare join sospetti in serie
* Notificare l’owner o lo staff designato
* Attivare la modalità di protezione punendo i join anomali

L’Anti-Raid può essere gestito anche dalla Dashboard Web, con impostazioni dettagliate e soglie di attivazione personalizzabili.

# **Anti-Link**

Questo modulo consente di bloccare automaticamente i messaggi contenenti link non autorizzati. È utile per contrastare spam, flood, phishing e inviti a server esterni.

Funzionalità principali:

* Blocco link configurabile
* Whitelist di ruoli e utenti
* Log automatico dei messaggi bloccati
* Notifiche allo staff

È possibile personalizzare il comportamento tramite il menu di setup o la dashboard.

# **Anti-Nuke migliorato**

Il modulo Anti-Nuke protegge il server da azioni distruttive compiute da membri con permessi elevati. Include il monitoraggio in tempo reale di eventi critici come:

* Eliminazione/Creazione/aggiornamento massiva di canali
* Rimozione/Creazione/aggiornamento di ruoli
* Ban/kick multipli in pochi secondi
* Modifiche alle impostazioni del server
* Eliminazione/Creazione/aggiornamento massiva di Webhook

Il sistema interviene automaticamente bloccando l’utente responsabile, ripristinando i danni (se possibile) e inviando notifiche allo staff.
L’Anti-Nuke è completamente configurabile tramite la Dashboard Web.

# **Backup potenziati**

Il sistema di backup permette di salvare l’intera configurazione del server (ruoli, canali, permessi, emoji, ecc.). Con la versione 2.0:

* È possibile creare backup manuali in qualsiasi momento
* I backup sono più rapidi, stabili e precisi
* Aumentati gli slot dei backup:

  **Piano   /  Slot**
    Free    /  20
    Gold    /  100
    Cristal  /  500

# **Backup automatici** (Cristal)

Gli utenti con piano Cristal possono attivare backup automatici giornalieri o settimanali. Questa funzione garantisce una copia di sicurezza sempre aggiornata, senza interventi manuali.

È possibile gestire la frequenza e il numero di backup da conservare direttamente dalla Dashboard Web.

# **Staff Guard** (Premium)

La funzionalità Staff Guard consente di controllare e limitare l’uso dei comandi di moderazione (ban, kick, mute, ecc.) solo a ruoli o utenti autorizzati. È pensata per evitare abusi, moderare lo staff e migliorare la sicurezza interna del server.

**Modalità di funzionamento**

Ogni comando sensibile viene eseguito solo se il ruolo dello staff è presente nella whitelist Staff Guard. In caso contrario, l’azione viene bloccata e registrata nei log.

**Livelli di accesso**

* **Gold:**

  * Accesso base alla Staff Guard.
  * Puoi impostare una whitelist di ruoli autorizzati a usare i comandi di moderazione.
  * Log di ogni azione di moderazione da parte dello staff e blocco automatico dell'azione non autorizzata.

* **Cristal:**
  * Possibilità di impostare un **cooldown** per i comandi di moderazione, limitando l’uso ripetuto in breve tempo.
  * Opzione per richiedere l’**approvazione di un superiore** prima dell’esecuzione di azioni sensibili (es. ban, kick).
    Esempio: quando un membro dello staff tenta di bannare un utente, quest’ultimo viene messo temporaneamente in timeout e la richiesta viene inviata a un approvatore designato. Se l’approvazione viene concessa, il ban viene eseguito; se viene rifiutata, il timeout viene revocato senza procedere al ban.
  * Tutto ciò che è incluso nel piano Gold.

Tutte le impostazioni di Staff Guard possono essere gestite dal menu setup o direttamente tramite la Dashboard Web.

## Piani Premium

BodyGuard offre due livelli di abbonamento Premium: **Gold** e **Cristal**, pensati per garantire strumenti professionali di protezione e gestione avanzata del server.

**Premium Gold – €1,99/server/mese**

Ideale per server piccoli e medi che desiderano un primo livello di sicurezza avanzata. Include:

* Staff Guard base
* Log in DM (solo per l'owner)
* Fino a 100 backup completi
* Badge Premium Gold
* Supporto prioritario

> È un abbonamento leggero ma potente, pensato per una gestione sicura e reattiva del tuo server.

**Premium Cristal – €4,99/server/mese**

Pensato per server con esigenze più complesse e strutturate. Include tutto ciò che offre Gold, più:

* Fino a 500 backup completi
* Backup automatici programmabili
* Staff Guard avanzata (limiti azioni staff, richieste approvazione)
* Notifiche DM multiple (fino a 5 utenti)
* Badge Premium Cristal
* Tutti i vantaggi del piano Gold inclusi

> È il livello massimo di protezione disponibile.

**Attivazione e gestione**

Puoi attivare un piano Premium direttamente da Discord, attraverso i comandi integrati o la Dashboard Web. L'abbonamento è valido per un solo server, ma può essere acquistato più volte per usarlo su più server.
Premium --> https://www.bodyguard.net/premium

**Prova gratuita**

Con il comando `/prova_premium`, puoi attivare una prova gratuita per testare le funzionalità Premium prima dell'acquisto.

**Cosa succede se non rinnovi?**

Se non rinnovi l’abbonamento:

* Le funzioni Premium verranno disattivate automaticamente.
* I backup superiori al limite Free verranno conservati per un breve periodo, poi eliminati.
* Tutte le impostazioni verranno salvate, pronte per essere riattivate se torni Premium.

I piani Premium si attivano direttamente tramite il bot in Discord, senza passaggi complicati.

**Supporto prioritario** (Gold, Cristal)
Gli utenti premium ricevono assistenza tecnica più rapida e dedicata rispetto agli utenti free.

# Stay safe. Stay protected.




