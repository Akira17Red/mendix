# Mendix

## Indice

1. Prologo
    - 1.1 Introduzione
    - 1.2 Download

2. Documentazione

3. Mendix Portal
    - 3.1 Mendix Home
    - 3.2 Projects
    - 3.3 Scrum Team
    - 3.4 Mendix Team
    - 3.5 User Stories
    - 3.6 Agile methodology
    - 3.7 Wireframes

4. Project Management
    - 4.1 Sprint & User stories
    - 4.2 Epics
    - 4.3 Archives
    - 4.4 Importare user-stories

5. Mendix Studio Pro
    - 5.1 Importare un progetto
    - 5.2 Nuova applicazione
    - 5.3 UI

# Prologo

## 1.1 Introduzione

Mendix è un software che ti aiuta in tutti gli stadi di vita di un'applicazione, ti aiuta quindi nell'ALM (Application Lifecycle Management).

## 1.2 Download

Clicca [qui](https://marketplace.mendix.com/link/studiopro/11.0.0) per installare la versione 11 di Mendix Studio Pro.

# Documentazione

Clicca [qui](https://docs.mendix.com/) per la documentazione di Mendix.
Da Mendix Studio Pro puoi premere F1 per venir reindirizzato direttamente al link.

# Mendix Portal

## 3.1 Mendix Home

[Qui](https://home.mendix.com) puoi trovare tutte le diramazioni in cui si estende Mendix:

- [Mendix portal](https://sprintr.home.mendix.com/link/myapps), viene utilizzato per creare nuove applicazioni, lavorare su quelle esistenti e comunicare con il team di progetto.
- [Marketplace](https://marketplace.mendix.com/), da cui si può scaricare Mendix Studio Pro, dei custom widgets e delle features, ovvero interi moduli di Studio Pro. Da qui si possono anche caricare moduli custom per chiunque o per la nostra organizzazione.
- [Atlas UI](https://www.mendix.com/atlas/), viene utilizzato per avere dei template per poter rendere bella la nostra pagina.
- [Mendix Studio Pro](https://marketplace.mendix.com/link/studiopro), il software che viene utilizzato per programmare le nostre applicazioni.
- [Catalog](https://catalog.mendix.com/p/home), da qui si possono ottenere dei dati di altre applicazioni che possiamo utilizzare all'interno della nostra.
- [Support](https://support.mendix.com/hc/en-us), da qua si può chiedere aiuto se non riusciamo a risolvere un problema.
- [Mendix Community](https://community.mendix.com/link/home), qui puoi trovare la community di Mendix, parlare con altri sviluppatori e proporre idee per migliorare il software.
- [Mendix Documentation](https://docs.mendix.com/), qui puoi trovare la documentazione ufficiale di Mendix alla quale aggrapparti ogni qualvolta hai dubbi su un certo argomento o ti serve sapere come si fa una certa cosa.

## 3.2 Projects

All'interno del portale di Mendix si possono vedere tutti i progetti di cui si fa parte oltre che quelli che si ha creato. Ci si può muovere all'interno del portale di Mendix da Studio Pro tramite l'apposito [pulsante](/images/Mendix%20UI/btn-portal.png) sull'interfaccia utente

Si possono vedere 3 dei principali stadi di vita di un'applicazione nella navbar laterale dell'overview di un progetto nel portale di Mendix:

1. Project management (capture)
2. Feedback (collect feedback)
3. Deploy

## 3.3 Scrum Team

Un team su Mendix è composto da:

  1. Product Owner: colui che si interfaccia con il cliente per esprimere le esigenze di questo con il team di sviluppo
  2. Scrum Master: capo-progetto
  3. Dev team: developers

## 3.4 Mendix Team

Nella sezione General/Team dal portale di Mendix c'è il team che compone il progetto cui si sta lavorando.
I ruoli disponibili per ogni partecipante sono i seguenti:

1. Product Owner
2. Scrum Master
3. Business Engineer (developer)
4. Application Operator
5. Guest

Si può vedere l'intero team (oltre che aggiungere/togliere partecipanti e assegnare i ruoli) dal portale di Mendix del progetto nella sezione General/Team.

## 3.5 User stories

Le ***user stories*** descrivono le esigenze del cliente che la nostra applicazione deve essere in grado di fornire.

Il template di una user-story è il seguente:

Da {user type}, voglio che {what}, in modo che {business value}.

In cui:

- User type: indica il tipo di utente.
- What: identifica la funzionalità che deve essere introdotta per quell'utente
- Business value: identifica lo scopo che ha la funzionalità per l'utente finale.

Più user stories possono fare parte di un ***epic*** (una funzionalità del software che richiede più cose da fare).

Ogni nuova user-story viene aggiunta al product ***backlog***, una lista delle funzionalità che si possono implementare.

Quando una user-story non si riesce ad implementarla nello sprint corrente viene spostata nello sprint successivo.

Uno ***sprint*** è un periodo di tempo predefinito (di solito due settiamane) che serve per raggiungere un certo obiettivo.

## 3.6 Agile methodology

Quando stiamo sviluppando un progetto dobbiamo pensare a cosa ci siamo detti quando abbiamo parlato dei template delle user-stories.

Dobbiamo dunque definire 3 componenti fondamentali:

1. User type: dobbiamo sapere CHI utilizzerà la nostra applicazione.
2. Business value: quali saranno gli scopi della nostra applicazione, in linea generica.
3. What: cosa deve essere fatto per raggiungere tali scopi, a livello di funzionalità che la nostra applicazione deve offrire e l'organizzazione della squadra per la creazione del progetto.

## 3.7 Wireframes

I wireframes sono delle bozze di progetto che si possono scrivere su un foglio di carta e che servono per identificare le funzionalità principali che l'app deve possedere.
Servono per avere un'idea visiva di come dovrà essere l'app a grandi linee.

Si possono allegare dei documenti all'interno del portale di Mendix nella sezione General/Documents tramite il [pulsante](/images/Mendix%20Portal/documents.png) apposito.

# Project Management

## 4.1 Sprint & User stories

Da Project Management/Planning/3 pulsanti/[Start Sprint](/images/Mendix%20Portal/start-sprint.png) possiamo pianificare lo sprint corrente, fatto questo verremo reindirizzati alla sezione Project Management/Board, dunque e da qui possiamo aggiungere delle user stories per le 4 categorie principali dello sprint:

1. To Do (categoria obbligatoria)
2. In Progress
3. Testing
4. Done

Oppure possiamo creare delle user stories per altre 3 categorie:

1. Next Sprint
2. Refinement
3. Backlog

Ad ogni user-story conviene dare un punteggio di quanta fatica si impiegherà per completarla con la [Fibonacci Sequence](https://en.wikipedia.org/wiki/Fibonacci_sequence).

Tornando alla sezione Planning possiamo spostare le user stories ovunque vogliamo tra le categorie semplicemente trascinandole.

## 4.2 Epics

Gli epics sono dei gruppi di user-stories che possiamo aggiungere da 3 sezioni diverse:

1. Board
2. Planning
3. Epics

A prescindere da dove vengono create verranno aggiunte sempre e solamente nella sezione Epics, e potremo selezionare delle user-stories dal Planning o dalla Board e aggiungerle agli Epics che abbiamo creato.

## 4.3 Archives

Qui verranno aggiunte tutte le user stories che sono state completate, siccome una volta terminata una user-story possiamo checkarla come completata.

## 4.4 Importare user-stories

Per importare delle user stories all'interno del proprio progetto bisogna andare su Project Management/Planning/ellipsis menu [...]/Import Stories

# Mendix Studio Pro

## 5.1 Importare un progetto

Per [importare](/images/Mendix%20UI/import-package.png) un progetto in Mendix Studio Pro basta andare su "File" e successivamente su "Import App Package..." e selezionare il file .mpk che si vuole importare

## 5.2 Nuova applicazione

Da Mendix Studio Pro si crea una nuova app dandole un nome e usando il pulsante apposito.

## 5.3 UI

Dall'interfaccia utente di Mendix Studio Pro, tramite l'apposito [pulsante](/images/Mendix%20UI/btn-portal.png) possiamo raggiungere il portale di Mendix.