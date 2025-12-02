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

# Mendix UI

## 5.2 Nuova applicazione

Da Mendix Studio Pro si crea una nuova app dandole un nome e usando il pulsante apposito.

## Mendix Portal

Dall'interfaccia utente di Mendix Studio Pro, tramite l'apposito [pulsante](/images/Mendix%20UI/btn-portal.png) possiamo raggiungere il portale di Mendix.

Per riportare il layout alle sue impostazioni originali andare su View/Reset Layout...

## User Interface

L'interfaccia utente di Mendix Studio Pro contiene le seguenti componenti:

- [Control Bar](/images/Mendix%20UI/control-bar.png): la barra in alto
- [App Explorer](/images/Mendix%20UI/app-explorer.png): mostra tutte le risorse dell'applicazione
- [Page Explorer](/images/Mendix%20UI/page-explorer.png): mostra la struttara della pagina che si sta guardando
- [Editor](/images/Mendix%20UI/editor.png): visualizza come si presentà l'applicazione man mano che la si crea. 
Vi sono due modalità di editing: structure mode (più dettagliata) e design mode (mostra come viene visualizzata l'app in produzione). Per cambiare quale viene visualizzata di default bisogna andare su: Edit/Preferences/Work environment > Default Page Editor.
C'è anche la [X-ray](/images/Mendix%20UI/x-ray.png) mode per la modalità design mode per vedere più dettagli sugli elementi della pagina.
- Sul pannello di destra c'è il [Properties Pane](/images/Mendix%20UI/properties-pane.png), ovvero il pannello che mostra le proprietà dell'elemento selezionato all'interno della pagina. C'è anche un'altra modalità selezionabile, ovvero lo [Styling Pane](/images/Mendix%20UI/styling-pane.png), il pannello che mostra lo stile dell'elemento selezionato.
Sull'altro tab invece c'è il [Toolbox Pane](/images/Mendix%20UI/toolbox-pane.png) che contiene tutti i widgets o i building-blocks drag-droppabili direttamente sulla pagina.
- Sulla parte inferiore dell'interfaccia c'è il [Bottom-Pane](/images/Mendix%20UI/bottom-pane.png), ovvero il pannello che mostra gli errori, le modifiche ed i best practice recommender (un bot virtuale che ti aiuta nel migliorare le prestazioni del programma).

## Toolbox components

Ci sono tanti widgets all'interno del toolbox pane che si possono usare per creare la propria pagina, come bottoni, griglie, titoli ecc. Ora andremo a vedere quelli principali.

## 5.1 Importare un progetto

Per [importare](/images/Mendix%20UI/import-package.png) un progetto in Mendix Studio Pro basta andare su "File" e successivamente su "Import App Package..." e selezionare il file .mpk che si vuole importare

Se non ci si vuole connettere immediatamente al server si può selezionare di salvare il file nel disco locale. Successivamente si potrà andare su Version Control > Upload To Version Control Server... per connetterlo al server (se esiste, o crearne uno nuovo)

# Building blocks

Per poter creare dei blocchi di pagina abbiamo a disposizione i building blocks, dei template composti da più widgets già preimpostati per apparire bene.

## Pageheader with controls

Mostra il titolo, un bottone ed un pulsante che può essere utile per tornare indietro

# Widgets

## Data containers

I data containers sono dei contenitori di dati, ovvero hanno bisogno di una sorgente da cui prendere dei dati per mostrarli a schermo. 
Hanno dunque bisogno di un database da cui ottenere i dati.
Le fonti di dati possono essere di diverso tipo:

1. Tabelle del database
2. Microflow
3. Nanoflow
4. Associazioni

I data containers hanno una funzione "on click" che ci permette di modificare un oggetto già esistente cliccando sull'oggetto stesso. 

Double cliccando su un data container possiamo specificarne la data source, molto spesso si riferiscono alle entità presenti nel domain model.
Per selezionarlo più in fretta si può fare right click sul data container > Data source > Select data source...

### Gallery

La Gallery è un data container che può mostrare dati statici o dinamici.

Si possono inserire più oggetti nella stessa riga per ogni device su cui verrà eseguita la nostra applicazione specificandolo nel campo "columns" double cliccando sul data container.

## Structure

Questo tipo di widgets fanno da contenitore a tutti gli altri widgets presenti nel toolbox. Servono a spaziare i widgets tra di loro e poterli racchiudere all'interno di un ecosistema comune.

### Layout grid 2

Un [Layout Grid](/images/Widgets/layout-grid.png) è un contenitore che permette di avere spazio tra i suoi componenti interni (spatial structure).
Un Layout Grid può avere righe e colonne.

1. Righe: l'altezza di ogni riga equivale all'altezza della colonna di altezza massima all'interno della riga stessa.
Le righe possono essere infinite.

2. Colonne: occupano uno spazio che va in 1/12 della larghezza della pagina.
Il concetto è diverso per le colonne che assumono un comportamento diverso in base all'impostazione che gli si dà:

    - [Autofill](/images/Widgets/column-autofill.png): riempie tutto lo spazio (in larghezza) all'interno della riga per quanto riesce (rimuove gli spazi bianchi)
    - [Autofit](/images/Widgets/column-autofit.png): riempie lo spazio in base al contenuto che deve mostrare (da 0 a 12)
    - [Manual](/images/Widgets/column-manual.png): decidi te (in 1/12 dello spazio orizzontale) quanto deve occupare in larghezza quella colonna.

Si possono dunque avere tante righe con delle colonne di diverse dimensioni: [esempio](/images/Widgets/layout-grid-example.png).

## Text

Posso creare una casella di testo e cambiarne la proprietà render-mode dalle properties per renderla:

1. Text
2. Paragraph
3. Heading 1-6 (1 più grande, 6 più piccolo)

Double cliccando su una casella di testo posso modificarne il testo ed inserire un testo statico, o uno dinamico utilizzando delle variabili prese dagli attributi dell'oggetto della mia entità.

## Input elements

Gli input elements vengono utilizzati per la compilazione dei form. Sono formati da una label e da un input element, ovvero una casella all'interno della quale si può inserire un valore.

Si può indicare se si vuol mettere la label indicante il tipo di dato che si dovrà inserire all'interno dell'input element.

Si possono inserire dei valori di default all'interno delle caption, ovvero all'interno degli input elements.

### Text box

Sono dei campi di input all'interno dei quali si può inserire del testo, ovvero delle stringhe di caratteri.

### Date picker

Sono dei campi di input in cui si inserisce un dato sottoforma di data.

### Combo box

Sono dei campi che permettono di selezionare uno tra i valori indicati all'interno della dropdown.

Per saperne di più sulle combo box clicca [qui](https://docs.mendix.com/appstore/widgets/combobox/)

## Buttons

Ci sono tanti tipi diversi di [bottoni](/images/Widgets/buttons.png) che in realtà hanno solo funzionalità diverse ma che sono molto simili tra loro. Tutti i bottoni hanno una funzione onclick customizzabile.

Ad ogni bottone si può assegnare:

- Caption
- Icon
- Full width (ricopre tutta la larghezza disponibile)
- Size (grandezza del bottone)

Tips:

1. I bottoni possono avere delle azioni specifiche al right click.

2. Le pagine possono anche venir create direttamente quando si va a selezionare la pagina dall'action button del bottone.

Right cliccando su un bottone si può selezionare la pagina a cui porta.

Un bottone può:

1. Show a page: mostrare una pagina
2. Close page: chiudere una pagina
3. Create object: creare un oggetto (e aprire una pagina)
4. Save changes: salva le modifiche

### Button

Il button è un bottone generico che non fa niente ma può essere configurato per fare qualsiasi cosa.

### Create button 

È di default il bottone per creare degli oggetti che corrispondono a delle entità. Bisogna specificarne il data source.

Hanno due funzioni:

1. On click: serve per specificare che creeranno un oggetto di un'entità di nostra scelta

2. On click page: specifica la pagina che dovrà aprirsi. Di solito aprono le pagine "NewEdit" dell'entità che creiamo.

# Pages

Le pagine si aggiungono col tasto destro su un modulo e facendo "Add page..."

La documentazione per i layout e templates la trovi [qui](https://atlasdesignsystem.mendixcloud.com/p/dashboard).

## Name

Il nome della pagina deve rappresentarne il contenuto. La convenzione del nome è espressa [qui](/images/Pages/naming-convention.png).

Si può seguire [questo](https://docs.mendix.com/refguide10/dev-best-practices/) manuale per i best practices.

## Navigation Layout

Una pagina può essere di due tipi:

1. full-screen: la pagina occupat tutto lo schermo, in questo caso il menù di navigazione può trovarsi sia in cima che sulla sinistra.

2. pop-up: non occupa tutto lo schermo, di solito i form di compilazione vengono messi all'interno delle pop-up pages.

## Templates

Quando si crea una pagina si può scegliere il template (pagine di default con stili e widgets diversi a seconda del loro scopo)

### List

Una pagina del template List mostrerà al suo interno un data container contenente una Gallery.

## Responsive Pages

Mendix è molto performante siccome ha una funzionalità che permette agli elementi di una pagina di reimpostarsi in modo da "fittare" in uno schermo di una dimensione diversa. Si adeguano dunque al contenitore in cui si trovano.

Ovviamente si può strutturare la pagina manualmente in base al tipo di schermo che conterrà la nostra pagina.

Per poter modificare la nostra pagina per poter essere mostrata come vogliamo per un dispositivo che non è desktop faremo nel seguente modo:

1. Andiamo a cliccare il [pulsante](/images/Mendix%20UI/devices.png) del dispositivo che vogliamo customizzare
2. In questo modo avremo una [view](/images/Mendix%20UI/tablet.png) diversa
3. A questo punto gli elementi della pagina saranno disposti in modo diverso e noi potremo editarli double cliccandoci e selezionando il dispositivo a cui vogliamo effettuare la modifica: [esempio](/images/Mendix%20UI/custom-device.png)

## Overview pages

Le pagine di overview servono a far vedere tutti i record di un entità del nostro domain model.
Si collegano alle newedit pages tramite un create button dell'entità della pagina corrente.

## NewEdit pages

Le pagine newedit servono a creare delle istante di un entità specifica del nostro domain model. Contengono il form che contiene tutti i campi facoltativi e obbligatori dell'entità che stiamo creando o modificando.

# Bottom-pane

## Errors

Mendix Studio Pro rileva gli errori in tempo reale, quindi sei certo che una volta runnata l'app non potrai riscontrare errori che "rompono" l'applicazione.

Per identificare un errore si fa double click sull'errore e questo ti porterà alla pagina che contine l'errore.

## Stories

Possiamo vedere le user-stories andando su View/Stories e gestirle direttamente da Mendix Studio Pro.

# Mendix Team Server

Puoi scaricare una versione di un'applicazione di un progetto cui fai parte ed averne una stessa versione nella tua macchina locale.

Puoi modificare questa applicazione solo se ne hai diritti per poterla cambiare (Scrum Master o Business Engineer).

## Status & Changes

I cambiamenti che apporti all'applicazione la portano ad una versione "successiva" rispetto a quella presente nel server.

I tuoi file nella cartella di lavoro locale, nella sezione App Explorer, possono avere un'icona che rileva che sia avvenuto un cambiamento rispetto all'app presente nel server.
Trovi [qui](/images/) i dettagli.

All'interno dell'App Explorer puoi vedere un solo tipo di cambiamento che è avvenuto a quell'item.
Nel Changes Pane invece puoi vedere sia che quell'item è stato creato che modificato.

## Commit Changes

Una volta che le modifiche sono state apportate e si è implementata una funzionalità all'interno del progetto che sia consistente, seppur piccola, si può procedere a committare il lavoro fatto.

Mendix si occupa di updatare il tuo progetto se qualcun altro ha apportato modifiche allo stesso prima che tu abbia avuto l'opportunità di committare il tuo lavoro.

Dunque, dal pannello sottostante: Changes > Commit > Messaggio di Commit > Push (se non sono state apportate modifiche al progetto dopo che avevi pullato l'ultima versione) 

Altrimenti: Messaggio di Commit > Update > Push

Quando si committa qualcosa si possono checkare le user-stories riguardanti le funzionalità che sono state incorporate.

Per committare: Version Control/Commit

# Domain Model

Il domain model rappresenta la struttura su cui si fonda il nostro database.

Esso è composto dalle entità che rappresentano un oggetto ben definito. Ovvero che abbia degli attributi e dei data-types per quegli attributi.

Ogni entità definisce quindi le proprietà di quelli che saranno gli oggetti del modello stesso.

Le entità possono essere connesse tra loro tramite delle associazioni.

## Entities

Le entità rappresentano dei veri e propri oggetti di cui si possono definire degli attributi.

Una persona può essere un'entità con degli attributi specifici:

1. Nome
2. Cognome
3. DataDiNascita
4. LuogoDiNascita

Quando viene creata un'entità, oltre alle colonne che inseriamo manualmente, viene creata anche una colonna dedicata all'id, questa colonna viene nascosta e serve per identificare univocamente un record all'interno di quella tabella seppur tutti gli altri campi risultino identici.

Dunque l'entità Persona che abbiamo creato precedentemente avrà le seguenti colonne:

1. Id (non visibile all'utente)
2. Nome
3. Cognome
3. DataDiNascita
4. LuogoDiNascita

I nomi delle entità devono rispettare le seguenti regole:

1. Devono essere singolari.
2. Devono rispecchiare al meglio l'oggetto che rappresentano
3. Devono essere scritti in PascalCase

## Attributes

Gli attributi descrivono quindi le proprietà di un'entità.

La convenzione dei nomi degli attributi di un'entità è il PascalCase.

Ogni attributo può contenere un tipo di dato specifico, l'elenco degli attributi è specificato nel capitolo che segue.

All'interno dei text widgets che sono contenuti all'interno di un data container possiamo specificare gli attributi dell'entità da mostrare, che saranno diversi a seconda dell'oggetto salvato.

### Default values

Gli attributi possono avere dei valori di default.
Ci sono degli attributi di default che vanno imparati come ad esempio il valore di default per le date:

[%CurrentDateTime%]: che serve per inizializzare il campo alla data in cui si è compilato il form.

## Attribute data-types

I tipi di dato sono dei concetti predefiniti di dati.
Puoi trovare tutti i data-types su Mendix in [questo](/images/Domain%20Model/data-types.png) link

All'interno delle captions dei text widgets che si trovano all'interno dei data containers, si possono utilizzare le curly braces {} per specificare l'attributo dell'entità (per ogni oggetto della data view) che si vuole visualizzare.

## Associations

In Mendix, possiamo creare delle associazioni tra le entità, ciò significa che un oggetto di una certa entità è collegato ad i campi di un'altra entità tramite il collegamento degli id.
Quando si crea un'associazione viene generata una chiave esterna ad entrambe le entità, ognuna di queste viene collegata all'id dell'entità cui si collegano.

Le associazioni non richiedono che le entità da entrambe le parti vengano compilate.
Se un'entità è associata ad altre 5 entità, queste risultano essere facoltative, se si lavora solamente col domain model.

## Nested data

Si possono nestare informazioni inserendo una list view o una gallery all'interno di una data view (per ora questo è il metodo visto).

Per creare un oggetto associato ad un'entità occorre farlo selezionando l'entità attraverso l'associazione e non direttamente dal database!

### Associations-types

Ci sono più tipi di associazione:

- 1-*: la più comune è la one-to-many association, il che significa che un oggetto di un'entità può essere collegato a più oggetti di un'altra entità.

- 1-1: one-to-one association, significa che un oggetto di un'entità è collegato ad un solo oggetto di un'altra entità.

- \*-\*: many-to-many association, significa che un oggetto di una stessa entità è collegato a più oggetti di un'altra entità e viceversa.

[Qui](/images/Domain%20Model/associations-types.png) trovi esempi dettagliati.

Per creare una relazione all'interno del domain model basta selezionare un'entità, spostarsi sul bordo e draggare il pallino bianco su un'altra entità, di default creerà una one-to-many association (l'entità da cui parte sarà "many" e quella di arrivo "one")

Per invertire l'associazione basta fare click col destro > Reverse direction

# Navigation menu

Il menu di navigazione è quello che serve per navigare tra le pagine ovunque ci si trovi.

Per aggiungere delle pagine al menu di navigazione principale bisogna selezionare l'app all'app explorer/Navigation/New item e qui specificare le pagine che si vogliono mostrare, oltre che l'icona e la caption.

