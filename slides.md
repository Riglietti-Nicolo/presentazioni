---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Perché conoscere l'economia
info: |
  # presentazione gpo
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
# transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# ELEMENTI DI ECONOMIA E ORGANIZZAZIONE DI IMPRESA

GPO

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

---

# PERCHÉ CONOSCERE L'ECONOMIA?

<br>

- l'economia studia i beni economici che hanno la caratteristicha di essere:
    - **limitati**: minor quantità rispetto a quella necessaria
    - **utili**: sono in grado di soddisfare i bisogni
    - **accessibili**: deve essere possibili procurarseli

- Gli economisti studiano il modo in cui le famiglie, le imprese e lo stato interagiscono nei **sistemi economici**

---

# Microeconomia e macroeconomia


- l'**economia politica** è una scienza che cerca di rispondere a 3 domande:

    - In che modo i soggetti economici prendono le loro decisioni?
    - In che modo i soggetti economici si relazionano e interagiscono tra di loro?
    - Da che cosa viene influenzata l'economia nel suo complesso?


- **MICROECONOMIA**:  si occupa delle scelte individuali dei soggetti economici:
    - i consumatori
    - le imprese
    - lo Stato e la Pubblica Amministrazione 

- **MACROECONOMIA**:  si occupa dell'analisi a livello aggregato delle seguenti tematiche economiche:
    - crescita economica 
    - l'inflazione
    - la disoccupazione

---
layout: two-cols
layoutClass: gap-16
---

# Crescita economica
| **METODO DELLA SPESA** | **METODO DEL VALORE AGGIUNTO** | **METODO DEI REDDITI** |
|:--------------------:|:--------------------------:|:-------------------:|
| PIL <br> = <br> CONSUMI <br> + <br> INVESTIMENTI <br> + <br> SPESA PUBBLICA <br> + <br> ESPORTAZIONI NETTE | PIL <br> = <br> SOMMA <br> <br> oppure: <br><br> PIL <br> = <br> RICAVO <br> - <br> SPESA| PIL <br> = <br> RETRIBUZIONI <br> + <br> REDDITI DA CAPITALE |

::right::

<div class="crescita_economica">

- **PIL**: variabile utilizzata per misurare la richezza di un paese
- **Metodo della spesa**: determina il PIL dal lato della domanda
- **Metodo del valore aggiunto**: determina il PIL dal lato dell'offerta
- **Metodo dei redditi**: studia l'indicatore dal punto di vista dei fattori produttivi utilizzati 
</div> 

<style>
  .crescita_economica {
    margin-top: 30%;
    margin-left: 10%;
  }
</style>

---

# L'inflazione

- **Inflazione**: aumento continuo dei prezzi e determina il potere d'acquisto
  - Incide sul **potere d'acquisto**, le **retribuzioni** non aumentano con l'aumentare dei prezzi

<br>

- **Deflazione**: fenomeno inverso che comporta la diminuzione dei prezzi 

<div class="inflazione">
  Gli economisti ritengono che un tasso di inflazione moderato intorno al 2% sia indice di buono stato di salute 
</div>

![image](https://www.soldionline.it/pictures/2020/01/17/inflazione-europa-dicembre-2019.jpeg)


<style>
  .inflazione {
    margin-top: 3%;
    box-shadow: 0px 0px 10px 0px gray;
    width: 800px;
    border-radius: 10px;
    padding: 10px;
  }
</style>

---
level: 2
---

# Il tasso di occupazione

- Un individuo è considerato **disoccupato** se non ha lavoro ma è in cerca di occupazione

- **Tasso di occupazione**: rapporto tra il numero di individui in cerca di occupazione e la forza lavoro

- La disoccupazione può essere:
    - **frizionale**
    - **ciclica**
    - **strutturale**

![image](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcRQ5oSqSncY_3Qxmet-xiMl0uu_uctMd0JpvP7mQ7zmLS3uWQM-)

<style>
  img {
    width: 34rem;
    margin-left: 17%;
  }
</style>

---

# IL MERCATO

- Luogo in cui sono effettuati scambi commerciali
- I soggetti del mercato:
  - **Compratori**: consumatori finali e imprese
  - **Venditori**: imprese che vendono servizi e/o beni e lavoratori

<br>

## Le tipologie di mercato

<br>

- A seconda della numerosità dei venditori esistono varie tipologie di mercato:
  - **Concorrenza perfetta**
  - **Monopolio**
  - **oligopolio**
  - **Concorrenza monopolistica**

<style>
  h2 {
    color: #5D8392;
  }
</style>

---
layout: two-cols
layoutClass: gap-16
---
# La domanda

- Quantità totale di beni e servizi richiesta dai consumatori

- fattori che influenzano la domanda (oltre al prezzo):
  - **Gusti del consumatore**
  - **Prezzi di altri beni**
  - **reddito**
  - **leggi dello Stato**

<br>

::right::

# L'offerta

- Quantità totale di beni e servizi offerti dal produttore

- fattori che influenzano l'offerta (oltre al prezzo):
  - **Costo dei fattori produttivi**
  - **Il miglioramento nelle tecnologie di produzione dei beni**
  - **leggi dello Stato**

---

# L'equilibrio tra domanda e offerta

- Per il venditore:
  - Il prezzo di vendita **soddisfacente** quando copre tutti i costi di produzione e garantisce un margine di profitto

- Per l'acquirente:
  - Il prezzo di vendita è **adeguato** se il rapporto tra la qualità percepita e il prezzo pagato è accettabile

<div class="mercato"> <b> Equilibrio del mercato </b>: quando la quantità che gli acquirenti sono disposti a comprare è esattamente uguale a quella che i venditori sono disposti a produrree vendere a quel determinato prezzo </div>


<style>
  .mercato{
    margin-top: 7%;
    box-shadow: 0px 0px 10px 0px gray;
    width: 800px;
    border-radius: 10px;
    padding: 10px;
    margin-left: 2%;
  }
</style>
---

# COME, CHE COSA E PER CHI PRODURRE?


<div class="grid grid-rows-[auto_1fr] gap-8 h-full">
  
  <div class=" text-xl space-y-2">
    <p>La produzione è un processo di trasformazione che comprende:</p>
    <ul class="text-left font-normal list-disc list-inside">
      <li><strong>La trasformazione materiale</strong></li>
      <li><strong>Il trasferimento dei beni nello spazio</strong></li>
      <li><strong>Il trasferimento dei beni nel tempo</strong></li>
    </ul>
</div>

  <div class="grid grid-cols-2 gap-8">
    <div>
      <h3>I soggetti della produzione</h3>
      <ul class="text-left font-normal list-disc list-inside">
        <li><strong>Il fornitore</strong></li>
        <li><strong>Il cliente</strong></li>
      </ul>
    </div>
    <div>
      <h3>I beni e i servizi</h3>
      <p>I beni si differenziano nei servizi in quanto: </p>
      <ul class="text-left font-normal list-disc list-inside">
        <li>I beni possono essere conservati mentre i beni sono immateriali</li>
        <li>I beni possono essere trasformati in altri beni mentre nei servizi è il cliente che può essere trasformato (servizi di formazione)</li>
      </ul>
    </div>
  </div>
</div>

---

# La produzione e i fattori produttivi

- **Produzione**: processo di formazione dei beni e servizi di cui dispone l'impresa in altri beni e servizi

- Gli **fattori produttivi** sono elementi necessari per la produzione, identificati come:
  - **Le risorsse naturali**
  - **Il lavoro**
  - **Il capitale**

- Si possono identificare altri 2 fattori produttivi :
  - **L' imprenditorialità**
  - **Lo Stato**

---

# IL CONCETTO DI VALORE NELL'IMPRESA

- Un'impresa è un sistema sociale non spontaneo e aperto
- Attinge dall'ambiente circosatante gli **input** e li trasforma per ottenere degli **output**

- Gli output vengono immessi nell'ambiente a disposizione di persone che cedono denaro per averli

![image](https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Catena-del-valore-di-Porter.svg/1200px-Catena-del-valore-di-Porter.svg.png)

<style>
  img {
    width: 34rem;
    margin-left: 17%;
  }
</style>

---

# Il valore nell'impresa: i ricavi, i costi e i profitti

- **L'obiettivo di un'impresa** è soddisfare i bisogni del cliente producendo beni o servizi 

- Per garantire la propria esistenza nel lungo periodo deve **creare valore**

- **Ricavo ( R )**: vendita di un bene o servizio

- **Costo ( C )**: quando si acquista un fattore produttivo
  - **costi fissi**
  - **costi variabili**
  - **costo totale**

- differenza tra ricavi e costi = **profitto o utile ( U )**

- **Perdite ( P )**: se i ricavi sono inferiori ai costi 
  - se i ricavi sono maggiori si realizza un *profitto o utile* 

---

# Il valore nell'impresa: i ricavi, i costi e i profitti

- attraverso i sistemi di contabilità si registra e si controlla il rapporto ricavo-costo.
  - **constabilità generale**
  - **contabilità analitica o industriale**
  
- L'azienda si può suddividere in:
  - **centri di profitto**
  - **centri di costo**

---

# L'IMPORTANZA DEI PROCESSI AZIENDALI

- Un **processo** è una sequenza di attività finalizzate a trasformare un input in un output

- Esistono diverse tipologie di processi: 
  - **Processi di direzione**
  - **Processi operativi**
  - **Processi di supporto**
  - **Processi primari**
  - **Processi di supporto**

---

# LA STRUTTURA ORGANIZZATIVA

- Ogni impresa deve definire la propria struttura organizzativa
- i principali modelli organizzativi sono:
  - **il modello funzionale**
  - **il modello divisionale**
  - **il modello matrica**

<br>

- Tra i modelli più nuovi troviamo il **modello circolare o flat**

![image](https://www.ionos.it/startupguide/fileadmin/StartupGuide/Screenshots_2018/IT-struttura-organizzativa4.png)
<style>
  img {
    width: 430px;
    margin-left: 58%;
    margin-top: -5%;
  }
</style>
---

# I SISTEMI INFORMATIVI

- Sono una funzione dell'organizzazione aziendale
- Gestiscono l'hardware, il software e le infrastrutture di comunicazione
- forniscono assistenza agli finale

<br>

# Nuove organizzazioni e modelli di riferimento 

- Le imprese tendono a instaurare partnership al fine di concentrare le risorse sul proprio core  businessed esternalizzare parte delle attività 

- con l'avvento della rete le imprese hanno modificato il modo di lavorare 

- La rete abbatte le barriere geografiche e temporali e offre alle imprese numerose opportunità di crescita e innovazione

