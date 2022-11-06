---
theme: default
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
marp: true
---
<!-- _paginate: false -->
![bg](img/Chapter_html0.png)

---

# HTML

__Hyper Text Markup Language__

È il linguaggio standard per la creazione di pagine web

Descrive la struttura delle pagine

Identifica una serie di elementi strutturati

La sua interpretazione necessita di un browser

---

# HTML – strumenti

Il portale che useremo durante il corso è

[https://codepen\.io](https://codepen.io/)

_CodePen is a social development environment. At its heart\, it allows you to write code in the browser, and see the results of it as you build. A useful and liberating online code editor for developers of any skill\, and particularly empowering for people learning to code. We focus primarily on front-end languages like HTML, CSS, JavaScript, and preprocessing syntaxes that turn into those things._

Iscrivetevi e seguite il profilo creato apposta per il corso

[https://codepen\.io/matteobaccan](https://codepen.io/matteobaccan)

---

# HTML – strumenti

Editor

Codepen.io

Notepad

Notepad++

VisualStudio Code

Va bene qualsiasi editor\, non visuale\, meglio se con syntax highlighter e code completion

Le slide e i sorgenti del corso\, liberamente ispirati a [https://www\.w3schools\.com](https://www.w3schools.com/) e costantemente aggiornati\, sono disponibili a questo indirizzo

[https://github\.com/matteobaccan/CorsoHTML](https://github.com/matteobaccan/CorsoHTML)

---
# HTML - Esempio

\<\!DOCTYPE html>
\<html lang="it">
\<head>
\<title>Titolo della pagina\</title>
\</head>
\<body>

\<h1>Intestazione\</h1>

\<p>Lorem ipsum dolor sit amet\, consectetur adipiscing elit\. Praesent laoreet hendrerit neque sed sagittis\. Donec sodales pharetra convallis\. Morbi sagittis orci vel erat cursus\, et pretium risus porttitor\.\</p>

\</body>
\</html>

---
# HTML - Elementi

TAG

__<nometag> contenuto </nometag>__

Un tag è identificato da una sequenza di caratteri\, con una sintassi di apertura e chiusura

All’interno del tag viene poi inserito il suo contenuti\, che a sua volta potrebbe essere del testo o altri tag

---
# HTML - Elementi

Empty TAG

__\<br> <hr> <img>__

Sono tag pensati per non avere un corpo\.

In base al fatto che siano usati come HTML5 o XHTML5 potrebbero essere scritti in formato diverso

__\<br/> <hr/> <img/>__

---

# HTML – attributi

Attributi

__<a href="https://www.baccan.it">Visitate Baccan.it</a>__

I tag HTML possono avere degli attributi\.

Gli attributi aggiungono delle informazioni ai tag

La loro struttura è per

__chiave=valore__

---

# HTML – definizione

__\<\!DOCTYPE html>__

Identifica il fatto che il documento sia in formato HTML5

---

<span style="color:#C9211E"> __\<html lang="it">__ </span>

<span style="color:#C9211E"> __\.\.\.__ </span>

<span style="color:#C9211E"> __\</html>__ </span>

<span style="color:#000000">É il primo elemento di una pagina html\, all’interno di questo  elemento è contenuta la struttura della pagina</span>

<span style="color:#C9211E"> __\<head>__ </span>

<span style="color:#C9211E"> __\.\.__ </span>

<span style="color:#C9211E"> __\</head>__ </span>

È il tag che contiene le informazioni inerenti alla pagina

\- Titolo

\- Descrizione

\- Tag per motori di ricerca

\- Tag per Social Network

\<head>

<span style="color:#C9211E">\<title>Titolo della pagina\</title></span>

\</head>

È il titolo della pagina: viene visualizzato all’interno del browser per dare un nome al tab che state visualizzando o dai motori di ricerca per rappresentare la vostra pagina

<span style="color:#C9211E">\<body></span>

<span style="color:#C9211E">…</span>

<span style="color:#C9211E">\</body></span>

Definisce il corpo della pagina html: testi\, paragrafi\, immagini\, link\, tabelle etc

\<body>

<span style="color:#C9211E">\<h1>Intestazione\</h1></span>

\</body>

È il primo degli heading disponibili in HTML5

\<body>

<span style="color:#C9211E">	</span>  <span style="color:#C9211E">\<p>Lorem ipsum dolor sit amet\, consectetur adipiscing elit\. Praesent laoreet hendrerit neque sed sagittis\. Donec sodales pharetra convallis\. Morbi sagittis orci vel erat cursus\, et pretium risus porttitor\.\</p></span>

\</body>

Definisce un paragrafo

Heading

<span style="color:#C9211E">\<h1>Intestazione 1\</h1></span>

<span style="color:#C9211E">\<h2>Intestazione 2\</h2></span>

<span style="color:#C9211E">\<h3>Intestazione 3\</h3> </span>

Questo tipo di tag sono intestazioni

Hanno 6 livelli di profondità e servono per intestare nel modo corretto delle parti di pagina\. Il loro utilizzo è utilizzato dai motori di ricerca per determinare delle parti importanti di pagina

L’attributo  __style__  viene utilizzato per assegnare un stile ad un determinato tag

<span style="color:#C9211E">\<h1 style="color:red;">Intestazione\</h1></span>

<span style="color:#C9211E">\<h2 style="color:blue;">Intestazione\</h2></span>

<span style="color:#C9211E">\<h3 style="color:yellow;">Intestazione\</h3></span>

Ad esempio per cambiare il colore del carattere di un testo

HTML – formattazione

\<b> \- Grassetto

\<strong> \- Importante

\<i> \- Italico

\<em> \- Enfatizzato

\<mark> \- Marked

\<small> \- Smaller

\<del> \- Cancellato

\<ins> \- Inserted

\<sub> \- Subscript

\<sup> \- Superscript

HTML – citazioni

Esistono alcuni elementi utilizzati per poter fare delle citazioni

\<abbr>	Defines an abbreviation or acronym

\<address>	Defines contact information for the author/owner of a document

\<bdo>	Defines the text direction

\<blockquote>	Defines a section that is quoted from another source

\<cite>	Defines the title of a work

\<q>	Defines a short inline quotation

Esiste la possibilità di inserire del testo che verrà scartato in automatico del browser\. Lo scopo del commento è puramente documentativo\.

<span style="color:#C9211E">\<\!\-\- Questo è un commento \-\-></span>

<span style="color:#C9211E">\<p>Questo è un paragrafo\</p></span>

In HTML esistono 140 colori standard che possono essere chiamati per nome

<span style="color:#C9211E">https://www\.w3schools\.com/colors/colors\_names\.asp</span>

Ad ognuno è associata una sequenza RGB

I colori possono essere usati in vari contesti\, come colore di fondo\, colore di testo o di bordo

<span style="color:#C9211E">\<h1 style="background\-color:DodgerBlue;">Intestazione\</h1></span>

<span style="color:#C9211E">\<p style="background\-color:Tomato;">Paragrafo\</p></span>

<span style="color:#C9211E">\<h1 style="color:Tomato;">Intestazione \</h1></span>

<span style="color:#C9211E">\<p style="color:DodgerBlue;">Paragrafo\</p></span>

<span style="color:#C9211E">\<p style="color:MediumSeaGreen;">Paragrafo\</p></span>

<span style="color:#C9211E">\<h1 style="border:2px solid Tomato;">Intestazione\</h1></span>

<span style="color:#C9211E">\<h1 style="border:2px solid DodgerBlue;">Intestazione\</h1></span>

<span style="color:#C9211E">\<h1 style="border:2px solid Violet;">Intestazione\</h1></span>

I colori possono essere indicati in vari formati RGB\, HEX\, HSL\, RGBA e HSLA

<span style="color:#C9211E">\<h1 style="background\-color:rgb\(255\, 99\, 71\);">\.\.\.\</h1></span>

<span style="color:#C9211E">\<h1 style="background\-color:\#ff6347;">\.\.\.\</h1></span>

<span style="color:#C9211E">\<h1 style="background\-color:hsl\(9\, 100%\, 64%\);">\.\.\.\</h1></span>

<span style="color:#C9211E">\<h1 style="background\-color:rgba\(255\, 99\, 71\, 0\.5\);">\.\.\.\</h1></span>

<span style="color:#C9211E">\<h1 style="background\-color:hsla\(9\, 100%\, 64%\, 0\.5\);">\.\.\.\</h1></span>

Un colore RGB rappresenta le tre componenti di luce RED\, GREEN e BLUE

I colori RGBA sono una estensione di RGB con l’aggiunta del canale Alpha per l’effetto di opacità

In HTML possiamo indicare un RGB con questa formula

rgb\(red\, green\, blue\)

Ogni parametro identifica l’intensità del colore in una scala da 0 a 255

I colori possibili sono 16\.777\.216

Il nero è rappresentato da  rgb\(0\, 0\, 0\)

Il bianco è rappresentato da rgb\(255\, 255\, 255\)

![](img%5CChapter_html1.png)

<span style="color:#C9211E">https://www\.w3schools\.com/colors/colors\_rgb\.asp</span>

Un colore HEX è la rappresentazione esadecimale di un colore RGB\, usando la seguente griglia

\#RRGGBB dove RR è il red\, GG è il green e BB è il blue

Si tratta del valore esadecimale precedentemente rappresentato da 0 a 255

![](img%5CChapter_html2.png)

<span style="color:#C9211E">https://www\.w3schools\.com/colors/colors\_hexadecimal\.asp</span>

HSL è acronimo di hue\, saturation e lightness \(tinta\, saturazione e luminosità\)

HSLA è la variante con Alpha channel

Hue è il grado di colore in una ruota da 0 a 360: 0 è il rosso\,120 il verde e 240 il blue\.

Saturation è una percentuale da 0% che identifica un’ombra grigia e  100% che rappresenta il colore pieno\.

Lightness è a sua volta una percentuale che va dal 0% che è il nero a 100% che è il bianco\.

![](img%5CChapter_html3.png)

<span style="color:#C9211E">https://www\.w3schools\.com/colors/colors\_hsl\.asp</span>

Cos'è il CSS?

CSS è acronimo di  __Cascading Style Sheets__ \, sono fogli che vengono utilizzati per formattare le pagine web\.

Con i CSS è possibile controllare il colore\, il carattere\, la dimensione del testo\, la spaziatura tra gli elementi\, il modo in cui gli elementi sono posizionati e disposti\, quali immagini di sfondo o colori di sfondo devono essere utilizzati\, o le diverse visualizzazioni in base alle dimensioni dello schermo

Da notare che  __cascading __ identifica il fatto che uno stile applicato a un elemento padre si applicherà anche a tutti gli elementi figli all'interno dell'elemento padre

I CSS possono essere aggiunti ai documenti HTML in 3 modi:

Inline \- utilizzando l'attributo style all'interno degli elementi HTML

Interno \- utilizzando un elemento \<style> nella sezione \<head>

Esterno: utilizzando un elemento \<link> per collegarsi a un file CSS esterno

HTML – CSS Inline

<h1  __style="color:blue;"__ >Una intestazione blue\</h1>

<p  __style="color:red;"__ >Un paragrafo rosso\</p>

HTML – CSS Interno

\<\!DOCTYPE html>

\<html>

\<head>

__  __  __\<style>__

__body \{background\-color: powderblue;\}__

__h1   \{color: blue;\}__

__p    \{color: red;\}__

__  __  __\</style>__

\</head>

\<body>

\<h1>This is a heading\</h1>

\<p>This is a paragraph\.\</p>

\</body>

\</html>

HTML – CSS Esterno

\<\!DOCTYPE html>

\<html>

\<head>

__\<link rel="stylesheet" href="styles\.css">__

\</head>

\<body>

\<h1>Intestazione\</h1>

\<p>Paragrafo\</p>

\</body>

\</html>

HTML – CSS styles\.css

body \{

background\-color: powderblue;

\}

h1 \{

color: blue;

\}

p \{

color: red;

\}

I link HTML sono collegamenti ipertestuali\.

Lo scopo è quello di passare da una pagina all’altra

Essendo elementi cliccabili\, quando viene spostato il mouse su un link il puntatore viene trasformato in una piccola mano\.

![](img%5CChapter_html4.png)

Sintassi

Il tag  __\<a>__  ha la seguente sintassi:

__\<a href="url">__ testo del collegamento __\</a>__

L'attributo più importante di  __\<a>__  è l'attributo  __href__ \, che indica la destinazione del collegamento\.

Il testo del collegamento è la parte visibile all’interno della pagina HTML

Facendo clic sul testo del collegamento\, il browser verrà indirizzato all'indirizzo  __URL__

Esiste una convenzione fra browser per visualizzare i collegamenti con un colre diverso\, in base ad alcune caratteristiche

Un collegamento  __non visitato__  è sottolineato e  __blu__

Un collegamento  __visitato__  è sottolineato e  __viola__

Un collegamento  __attivo__  è sottolineato e  __rosso __

Per ottenere l’attivo basta tenere cliccato il mouse sul link

L'attributo di  __target__

Se non indichiamo un  __target__  il browser visualizzerà il link nella pagina corrente\.

Per modificare questo comportamento è necessario specificare un altro  __target__

L'attributo  __target__  può avere uno dei seguenti valori:

__\_self__  \- DEFAULT\. Apre il documento nella stessa finestra/scheda in cui è stato cliccato

__\_blank__  \- Apre il documento in una nuova finestra o scheda

__\_parent__  \- Apre il documento nel frame genitore

__\_top__  \- Apre il documento in tutto il corpo della finestra

__“__  __nomeframe” – __ Apre il documento in un determinato frame

\<iframe src="http://www\.acmenovara\.it" name="A">

\<p>ACME Novara\</p>

\</iframe>

<iframe src="[https://www\.google\.com](https://www.google.com/)" name="B">

\<p>Google\.com\</p>

\</iframe>

\<iframe src="https://www\.google\.it" name="C">

\<p>Google\.it\</p>

\</iframe>

\<a href="http://www\.acmenovara\.it" target="B">CAMBIO B\</a>

Crea un bookmark in HTML

I bookmark possono essere utili se una pagina web è molto lunga\.

Per creare un bookmark: prima occorre creare il bookmark\, poi aggiungere un collegamento ad esso\.

Quando si fa clic sul bookmark\, la pagina scorrerà verso il basso o verso l'alto fino alla posizione del bookmark\.

Il tag HTML  __\<img>__  viene utilizzato per incorporare un'immagine in una pagina web\.

Le immagini non sono tecnicamente inserite in una pagina web; le immagini sono collegate a pagine web\. Il tag  __\<img>__  crea uno spazio per inserire l'immagine\.

Il tag \<img> è vuoto\, contiene solo attributi e non ha un tag di chiusura\.

Il tag \<img> ha due attributi obbligatori:

__src__  \- Specifica il percorso dell'immagine

__alt__  \- Specifica un testo alternativo per l'immagine

HTML – Immagini di sfondo

Tramite l’attributo  __style__  è possibile inserire un’immagine di sfondo ad un elemento grafico

__<div __  <span style="color:#C9211E"> __style__ </span>  __="__  <span style="color:#C9211E"> __background\-image__ </span>  __: url\('__  __[https://i\.ytimg\.com/vi/\-cQk6kK7JVs/maxresdefault\.jpg](https://i.ytimg.com/vi/-cQk6kK7JVs/maxresdefault.jpg)__  __'\);">__

_Lorem ipsum dolor sit amet\, consectetur adipiscing elit\. Donec ante eros\, egestas vitae ullamcorper id\, dignissim nec ipsum\._

__\</div>__

Testo  __Lorem ipsum__  _ _ generato da [https://www\.lipsum\.com/](https://www.lipsum.com/)

HTML – Immagini di sfondo \- cover

Se volete che l'immagine di sfondo copra l'intero elemento\, si può impostare la proprietà

<span style="color:#C9211E">background\-size: cover</span>

Inoltre\, per assicurasi che l'intero elemento sia sempre coperto\, basta impostare la proprietà

<span style="color:#C9211E">background\-attachment: fixed</span>

In questo modo\, l'immagine di sfondo coprirà l'intero elemento\, senza cambiarne le proporzioni

L'elemento HTML  __\<picture>__  offre una maggiore flessibilità nello specificare le risorse dell'immagine\. Contiene uno o più elementi  __\<source>__ \, ognuno dei quali si riferisce a diverse immagini tramite l'attributo  __srcset__ \. In questo modo il browser sceglie l'immagine che meglio si adatta alla visualizzazione e/o al dispositivo corrente\.

Ogni elemento  __\<source>__  ha un attributo multimediale che definisce quando l'immagine è la più adatta\.

Infine un elemento  __\<img>__  indicherà il default da usare nel caso non ci siano match corretti

<span style="color:#C9211E">\<picture></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<source media="\(min\-width: 650px\)" srcset="computer\.jpg"></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<source media="\(min\-width: 465px\)" srcset="tablet\.jpg"></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<img src="cellulare\.jpg"></span>

<span style="color:#C9211E">\</picture> </span>

Quando usare il tag  __\<picture>__ ?

\- Risparmiare banda

\- Usare immagini ottimizzate

\- Adattare facilmente il contesto alla dimensione del device

Il tag  __\<map>__  viene usato per definire una mappa di immagini\.

Una mappa è un'immagine con delle aree selezionabili

L'attributo  __name__  dell'elemento  __\<map>__  è associato all'attributo  __usemap__  di  __\<img>__  e crea una relazione tra immagine e mappa

L'elemento  __\<map>__  contiene un numero di elementi  __\<area>__ \, che definisce le aree cliccabili nella mappa dell'immagine

<span style="color:#C9211E">\<img src="https://www\.affde\.com/uploads/article/33391/hMAObf6pOlc2GHIM\.jpg" usemap="\#workmap" width="500px" height="300px"></span>

<span style="color:#C9211E">\<map name="workmap"></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<area shape="rect" title="google" coords="0\,0\,250\,300" href="https://www\.google\.com"></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<area shape="rect" title="bing" coords="250\,0\,500\,300" href="https://www\.bing\.com"></span>

<span style="color:#C9211E">\</map></span>

Una favicon è una piccola immagine visualizzata accanto al titolo della pagina nella scheda del browser e nel bookmark del browser

Per aggiungere una favicon ad un sito web\, occorre salvarla nella directory principale del server web e chiamarla  __favicon\.ico__

Nel caso sia posizionata o nominata in modo diverso è necessario indicarne il percorso a livello di  __head__

<span style="color:#C9211E">\<head></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<link rel="icon" type="image/x\-icon" href="/images/favicon\.ico"></span>

<span style="color:#C9211E">\</head></span>

![](img%5CChapter_html5.png)

Un sito utilizzabile per disegnare delle favicon è [https://www\.favicon\.cc/](https://www.favicon.cc/)

Non volendo usare il formato  __ico__  è comunque possibile scegliere fra una serie di altri formati orizzontalmente accettati dai maggiori browser

![](img%5CChapter_html6.png)

Il tag  __table __ serve a racchiudere delle informazioni per righe e colonne\.

Questo tag\, molto utilizzato in passato\, è stato progressivamente superato da altri costrutti responsive\, pur essendo fortemente utilizzato da molti siti web\.

Il tag  __table__  è composto da più tag

__table : __ tabella

__thead : __ area di intestazione tabella

__tbody :__  corpo della tabella

__tfoot :__  piede della tabella

__tr :__  riga

__th : __ header

__td : __ data

__caption: __ titolo

__colgroup: __ definizione di colonne

__col: __ singolo elemento di definizione di colonna

HTML – Table border

Ci sono una serie di proprietà che possono essere utilizzate per personalizzare i tag  __table__ \, ad esempio

border: 1px solid black;

border\-collapse: collapse;

border\-radius: 10px;

border\-color: \#96D4D4;

background\-color: \#96D4D4;

HTML – Table width

Con lo  __style__   __width__  è possibile indicare l’occupazione di una singola colonna

<table  __style="width:100%"__ >

\<thead>

\<tr>

<th  __style="width:10%"__ >Colonna 1\</th>

\<th>Colonna 2\</th>

\</tr>

\</thead>

\<tbody>

\<tr>

\<td>Dato 1\</td>

\<td>Dato 2\</td>

\</tr>

\</tbody>

\</table>

HTML – Table colspan e rowspan

Con lo  __colspan __ e  __rowspan__  è possibile indicare che una

cella occupa più di una riga o di una colonna

\<table>

\<thead>

\<tr>

<th  <span style="color:#C9211E">colspan="2"</span> >Colonna 1\</th>

\<th>Colonna 2\</th>

\</tr>

\</thead>

\<tbody>

\<tr>

<td  <span style="color:#C9211E">rowspan="2"</span> >Dato 1\</td>

\<td>Dato 2\</td>

\<td>Dato 3\</td>

\</tr>

\<tr>

\<td>Dato 2\</td>

\<td>Dato 3\</td>

\</tr>

\</tbody>

\</table>

![](img%5CChapter_html7.png)

HTML – Table caption

Con  __caption__  è possibile dare un titolo a una tabella

Il tab  __caption __ deve essere inserito subito dopo il tag  __table__

\<table>

<span style="color:#C9211E">\<caption></span> Caption <span style="color:#C9211E">\</caption></span>

\.\.\.

HTML – Table colgroup col

Con  __colgroup __ e  __col__  è possibile indicare una serie di caratteristiche che la singola colonna deve avere: come un colore o un bordo

Il tab  __col__  può anche avere un attributo che indica quante colonne subiscono il nuovo stile

\<table>

<span style="color:#C9211E">\<colgroup></span>

<span style="color:#C9211E">\<col span="2" style="background\-color:green;"></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<col style="background\-color:blue; border: 5px solid black;"></span>

<span style="color:#C9211E">\</colgroup></span>

\.\.\.

HTML – Liste non ordinate

L’utilizzo dei tag  __ul __ e  __li __ permette di definire delle liste non ordinate

Le liste sono rappresentate da una serie di righe contigue evidenziate da un piccolo cerchio nero iniziale

<span style="color:#C9211E">\<ul></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<li>Primo elemento\</li></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<li>Secondo elemento\</li></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<li>Terzo elemento\</li></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\</ul></span>

HTML – Liste ordinate

L’utilizzo dei tag  __ol __ e  __li __ permette di definire delle liste ordinate

Le liste sono rappresentate da una serie di righe contigue numerate

<span style="color:#C9211E">\<ol></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<li>Primo elemento\</li></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<li>Secondo elemento\</li></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<li>Terzo elemento\</li></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\</ol></span>

HTML – Liste descrittive

L’utilizzo dei tag  __dl\,__   __dt__  e  __dd __ permettono di creare delle liste descrittive

Con  __dl __ si definisce la lista\, con  __dt __ si descrive il nome \(term\)\, con  __dd __ si descrive il termine

<span style="color:#C9211E">\<dl></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<dt>Cornetto\</dt></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<dd>\- alla crema\</dd></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<dd>\- al cioccolato\</dd></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<dd>\- alla marmellata\</dd></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<dt>Latte\</dt></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<dd>\- di soia\</dd></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">\<dd>\- di capra\</dd></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\</dl></span>

HTML – Blocchi e inline

Esistono due tag generici e abbastanza simili utilizzati per definire delle aree\.

I tag sono  __div __ e  __span__ \.

<span style="color:#C9211E">DIV</span>

L’elemento inizia sempre su una nuova riga

Occupa l’intera larghezza disponibile

Ha un margine inferiore e superiore

<span style="color:#C9211E">SPAN</span>

Non inizia su una nuova riga

Occupa solo la larghezza necessaria

Non ha un margine superiore e inferiore

HTML – Blocchi e inline

Lorem ipsum dolor sit amet\, consectetur adipiscing elit\. \<div style="background\-color:yellow; border: 1px solid red;">Ciao DIV\</div> Praesent laoreet hendrerit neque sed sagittis\.

Lorem ipsum dolor sit amet\, consectetur adipiscing elit\. \<span style="background\-color:yellow; border: 1px solid red;">Ciao SPAN\</span> Praesent laoreet hendrerit neque sed sagittis\.

![](img%5CChapter_html8.png)

![](img%5CChapter_html9.png)

L’attributo  __class __ serve ad indicare una classe associata ad un qualsiasi tag\.

<div  <span style="color:#C9211E">class</span> ="town">

\<h2>Roma\</h2>

\<p>Forza Roma forza Lupi\</p>

\</div>

La classe specificata può poi essere descritta a livello di CSS\.

Da notare che il nome della classe è case sensitive

L’attributo  __id __ permette di referenziare un singolo tag in modo univoco\.

Il browser non effettua nessun controllo di univocità sull’ __id__  è quindi a carico di chi crea la pagina assicurarsi che  __id__  sia effettivamente univoco

Avere un  __id__  ci permette di applicare delle caratteristiche ad un singolo tag e di usarlo in modo più efficiente da parte di codice javascript

Il tag  __iframe __ permette l’inclusione di una pagina all’interno di una pagina HTML

<span style="color:#C9211E">\<iframe src="url" title="descriptione">\</iframe> </span>

L’attributo necessario per il funzionamento di un  __Iframe__  è  __url__ \.

Questo attributo indica l’indirizzo della pagina da includere

__iframe __ ha una serie di attributi che ne condizionano la visualizzazione come:

<iframe src="https://www\.baccan\.it/" title="Matteo Baccan"  <span style="color:#C9211E">height</span> ="200"  <span style="color:#C9211E">width</span> ="300">\</iframe>

<iframe src="https://www\.baccan\.it/" title="Matteo Baccan"  <span style="color:#C9211E">style</span> ="height:200px;width:300px;">\</iframe>

__Iframe __ può poi essere utilizzato come target di un tag  __a__

<iframe src="about:blank" title="Matteo Baccan"  <span style="color:#C9211E">name="baccan"</span> >\</iframe>

<a href="https://www\.baccan\.it/"  <span style="color:#C9211E">target="baccan"</span> >Baccan\.it\</a>

__script __ è il tag col quale è possibile inserire del codice JavaScript per rendere dinamiche delle pagine HTML

__script__  può contenere direttamente del codice\, o referenziare una pagina esterna contenente a sua volta del codice

<span style="color:#C9211E">\<a href="https://www\.baccan\.it/" id="baccan">Baccan\.it\</a></span>

<span style="color:#C9211E">\<script></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">document\.getElementById\("baccan"\)\.innerHTML = "CIAO\!\!";</span>

<span style="color:#C9211E">\</script></span>

E’ importante capire come sono gestiti i file in una struttura a cartelle\. La corretta comprensione permette di indirizzare nel modo giusto le varie risorse

Rispetto alla pagina corrente

\<img src="foto\.jpg"> 				 __foto\.jpg __ è nella stessa cartella

\<img src="immagini/foto\.jpg"> 		 __foto\.jgp __ è nella cartella  __immagini__

\<img src="/immagini/foto\.jpg"> 		 __foto\.jpg __ è nella cartella  __immagini __ del root folder

\<img src="\.\./foto\.jpg"> 				 __foto\.jpg __ è nella cartella padre della cartella corrente

\<img src="http://www\.foo\.bar/foto\.jpg"> 	 __foto\.jpg __ è sul sito  __foo\.bar__

__head__  è il tag dove sono contenute una serie di informazioni propedeutiche alla visualizzazione corretta di una pagina e alla sua indicizzazione all’interno di motori di ricerca e social network\.

Nel tag  __head __ sono presenti anche i riferimenti a file esterni\, tipicamente  __css__

Altri elementi che entrano a far parte di questo tag sono i tag  __meta__

Il set di caratteri usato per la corretta visualizzazione del sito

\<meta charset="UTF\-8">

Aggiornamento automatico

\<meta http\-equiv="refresh" content="10">

Impostazioni per la visualizzazione responsive

\<meta name="viewport" content="width=device\-width\, initial\-scale=1\.0">

Elementi utilizzati dai motori di ricerca

Descrizione

\<meta name="description" content="La mia bellissima pagina">

Keywords

\<meta name="keywords" content="HTML\, CSS\, JavaScript">

L’autore

\<meta name="author" content="Matteo Baccan">

HTML – Open Graph

Altri elementi che si trovano in  __head__  sono quelli del protocollo Open Graph

https://ogp\.me/

Il protocollo Open Graph consente a qualsiasi pagina Web di essere arricchita di dati utili ad un “social graph”\. Ad esempio\, questo protocollo viene utilizzato su Facebook per consentire a qualsiasi pagina Web di avere le stesse funzionalità di qualsiasi altro oggetto su Facebook\.

HTML – Open Graph

Le quattro proprietà minime per Open Graph sono

__og:title__  : il titolo del vostro oggetto

__og:type__  : il tipo\, ad esempio "video\.movie"

__og:image__  : l’immagine che rappresenta l’oggetto

__og:url__  : l’indirizzo canonico dell’oggetto

HTML – Open Graph

Un esempio di utilizzo delle proprietà Open Graph

<meta property="og:url"		   content="https://www\.baccan\.it" />

<meta property="og:title"		   content="Il sito personale di Matteo Baccan" />

\<meta property="og:description"  content="Scrivo software e aiuto le aziende a scriverne di migliore" />

<meta property="og:image"	   content="https://www\.baccan\.it/logo/29\.png" />

<meta property="og:type"		   content="blog" />

<meta property="og:site\_name"	   content="Il sito personale di Matteo Baccan" />

HTML – Open Graph

Altri elementi di Open Graph sono

og:audio : l’audio che accompagna questo oggetto

og:description : la descrizione di questo oggetto

og:determiner : la parola che appare prima del titolo all’interno di una frase\. E’ possibile scegliere fra  __a__ \,  __an__ \,  __the__ \,  __""__ \,  __auto__ \)\. Se è scelto  __auto __ il valore sarà scelto fra  __a__  o  __an__ \. Il default è vuoto  __""__  \(blank\)\.

og:locale : è la lingua dell’oggetto\. Se non indicato il default è  __en\_US__ \.

og:locale:alternate : l’elenco di altre lingue nelle quali la pagina è disponibile

og:site\_name : se l’oggetto è parte di un grande sito web\, sarà il nome con il quale verrà referenziato il sito

og:video : l’indirizzo del video in accompagnamento della pagina

HTML – Open Graph

Un esempio di uso avanzato di Open Graph preso dalla pagina di  __Gal Gadot __  __[https://www\.imdb\.com/name/nm2933757/](https://www.imdb.com/name/nm2933757/)__  protagonista di “Wonder Woman 1984”

<meta  __property="og:url"__  content="http://www\.imdb\.com/name/nm2933757/" />

<meta  __property='og:image'__  content="https://m\.media\-amazon\.com/images/M/MV5BYThjM2NlOTItYTUzMC00ODE3LTk1MTItM2I3MDViY2U3MThlXkEyXkFqcGdeQXVyMTg4NDI0NDM@\.\_V1\_UY1200\_CR165\,0\,630\,1200\_AL\_\.jpg" />

<meta  __property='og:type'__  content="actor" />

<meta  __property="og:description"__  content="Gal Gadot\, Actress: Wonder Woman 1984\. Gal Gadot is an Israeli actress\, singer\, martial artist\, and model\. She was born in Rosh Ha'ayin\, Israel\. Her parents are Irit\, a teacher\, and Michael\, an engineer\. She served in the IDF for two years\, and won the Miss Israel title in 2004\. Gal made her film debut in the fourth film of the Fast and Furious franchise\, Fast &amp; Furious \- Solo parti\.\.\." />

<meta  __property='og:title'__  content="Gal Gadot \- IMDb" />

<meta  __property='og:site\_name' __ content='IMDb' />

HTML – Open Graph

Alcune proprietà Open Graph possono avere delle proprietà aggiuntive\.

Ad esempio  __og:image__  può indicare alcuni dati in riferimento alla propria dimensione

og:image:width – Larghezza in pixel

og:image:height – Altezza in pixel

HTML – Responsive

Il responsive web design consiste nel creare pagine web che si adattino a qualsiasi dispositivo

Un responsive web design si adatterà in automatico alle diverse dimensioni dello schermo e viewport

Per poter definire che una pagina è responsive occorre aggiungere una riga nel tag  __head__

<span style="color:#C9211E"> __\<meta name="viewport" content="width=device\-width\, initial\-scale=1\.0"> __ </span>

Questa riga dirà al browser come controllare le dimensioni di pagina

HTML – Responsive image

Per rendere una immagine responsive è possibile utilizzare  __max\-width__  che ci permette di indica la dimensione massima che avrà in larghezza ed impostare l’altezza ad  __auto__

<span style="color:#C9211E"><img src="gattino\.jpg" style="</span>  <span style="color:#C9211E"> __max\-width:100%; height:auto;__ </span>  <span style="color:#C9211E">"> </span>

HTML – Responsive image

Un altro elemento responsive che abbiamo visto è il tag  __picture__

<span style="color:#C9211E">\<picture></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<source media="\(min\-width: 650px\)" srcset="computer\.jpg"></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<source media="\(min\-width: 465px\)" srcset="tablet\.jpg"></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<img src="cellulare\.jpg"></span>

<span style="color:#C9211E">\</picture> </span>

HTML – Responsive text

Anche gli elementi testuali possono avere delle caratteristiche responsive\.

Per farlo occorre impostare le dimensioni del carattere in  __vw__  che rappresenta il  __viewport width__

Ad esempio proviamo ad impostare la grandezza di  __ciao__  a 10vw

<span style="color:#C9211E"> </span>  <span style="color:#C9211E">\<div style="font\-size:10vw">Ciao\</div> </span>

Ingrandendo a diminuendo la dimensione dello schermo il testo si adeguerà di conseguenza

Il  __viewport width__  è la larghezza della finestra del browser e l’unità  __vw__  è il suo percentile

[https://whatismyviewport\.com/](https://whatismyviewport.com/)

HTML – Media Query

Un altro modo per adattare le pagine ad una particolare dimensione è l’utilizzo delle media query

In questo modo è possibile cambiare completamente layout\, in base alle dimensioni dello schermo

HTML – Media Query

All’interno di una media query è possibile indicare il momento in cui un particolare frammento di CSS deve entrare in gioco

In questo caso\, il CSS viene considerato fino alla larghezza di 800px

<span style="color:#C9211E">@media screen and \(max\-width: 800px\) \{</span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">/\* CSS \*/</span>

<span style="color:#C9211E">\}</span>

Il tag  __code __ permette di evidenziare del testo in modo possa essere usato per la rappresentazione di codice\, ad esempio usando un font non proporzionale

<span style="color:#C9211E">\<code></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">x = 1;</span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">y = 2;</span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">z = x \+ y;</span>

<span style="color:#C9211E">\</code></span>

Il comportamento è simile all’uso di un tag  __span __ con font  __courier__

Il tag  __kbd __ permette di evidenziare una sequenza di tasti da premere: l’aspetto è simile a quello di  __code__

<span style="color:#C9211E">\<p>Visualizza il sorgente premendo \<kbd>Ctrl \+ U\</kbd>\</p></span>

Il comportamento è simile all’uso di un tag  __span __ con font  __courier__

Il tag  __samp __ permette di simulare l’output di un programma

<span style="color:#C9211E">\<p>Esempio di output:\</p></span>

<span style="color:#C9211E">\<p>\<samp>Hello world\.\<br>Premi F1 per continuare\</samp>\</p></span>

Il tag  __pre __ permette di mantenere la formattazione presente all’interno di un testo

<span style="color:#C9211E">\<pre></span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\<code></span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">x = 1;</span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">y = 2;</span>

<span style="color:#C9211E">    </span>  <span style="color:#C9211E">z = x \+ y;</span>

<span style="color:#C9211E">  </span>  <span style="color:#C9211E">\</code></span>

<span style="color:#C9211E">\</pre></span>

Il tag  __var __ evidenzia una variabile o una espressione

<span style="color:#C9211E">L’area del rettangolo è \<var>b\</var> per \<var>a\</var>\, dove \<var>b\</var> è la base e \<var>a\</var> è l’altezza</span>

HTML ha diversi tag semantici che definiscono le diverse parti di una pagina\.

Questi elementi permettono una standardizzazione del codice verso una serie di elementi comuni

\<header> \- Intestazione o sezione di un documento

\<nav> \- Link di navigazione

\<section> \- Sezioni

\<article> \- Un contenuto

\<aside> \- Una sidebar

\<footer> \- Il piede del documento o di una sezione

\<details> \- Dettagli aggiuntivi rispetto al documento

\<summary> \- Un header dell’elemento \<details>

![](img%5CChapter_html10.png)

Esistono tecniche diverse per posizionare questi tag

L’uso di framework CSS come Bootstrap

L’uso delle proprietà  __float __ e  __clear__

L’uso di Flexbox \(1\)

L’uso di Grid Layout \(2\)

https://caniuse\.com/flexbox

https://caniuse\.com/css\-grid

![](img%5CChapter_html11.png)

HTML – validazione

Per verificare che il proprio codice HTML/CSS sia valido è possibile usare dei siti di validazione codice

Il più conosciuto è il validatore di w3\.org\, che è in grado di darci segnalazione di tutte le anomalie presenti nel nostro codice\. Esistono però delle valide alternative

[https://validator\.w3\.org](https://validator.w3.org/)

[https://html5\.validator\.nu](https://html5.validator.nu/)

In alternativa esistono dei plugin utilizzabili direttamente da browser\, come  __html\-validator__  per Chrome

https://chrome\.google\.com/webstore/detail/html\-validator/mpbelhhnfhfjnaehkcnnaknldmnocglk

HTML – validazione cross device

Esistono una serie di siti web che permettono di verificare che il proprio sito venga visualizzato correttamente su una serie di device\.

Alcuni di più famosi sono

[https://www\.browserstack\.com](https://www.browserstack.com/)

[https://www\.browserling\.com](https://www.browserling.com/)

HTML – validazione cross device

Browserstack richiede una registrazione per poter usare la versione gratuita e mette a disposizione una simulazione su device reali per sistemi operativi Windows\, Mac\, IOS e Android

![](img%5CChapter_html12.png)

HTML – validazione cross device

Browserling permette 1 minuto di navigazione su una serie di sistemi operativi e versioni di browser

![](img%5CChapter_html13.png)

Esistono una serie ci caratteri riservati che non possono essere inseriti all’interno di una pagina HTML\.

Ad esempio i caratteri \< e > che rappresentano l’inizio e la fine di un  __tag\.__

Per superare questa limitazione è possibile ricorrere alle entity\, che rappresentano una sintassi con la quale indicare la rappresentazione di un carattere riservato\.

Una entity è rappresentabile in 2 modi differenti\, tramite

__&nome\_entity;__

Oppure

__&\#numero\_entity;__

Di seguito una serie di entity largamente diffuse

non\-breaking space 			&nbsp; 	&\#160;

< 	less than 						&lt; 		&\#60;

> 	greater than 					&gt; 		&\#62;

& 	ampersand 					&amp; 	&\#38;

" 	double quotation mark 			&quot; 	&\#34;

' 	single quotation mark \(apostrophe\) 	&apos; 	&\#39;

¢ 	cent 							&cent;	&\#162;

£ 	pound 						&pound; 	&\#163;

¥ 	yen 							&yen; 	&\#165;

€ 	euro 							&euro; 	&\#8364;

© 	copyright 						&copy; 	&\#169;

® 	registered trademark 			&reg; 	&\#174;

HTML – entity \- simboli

Oltre ai caratteri riservati\, esistono una serie di caratteri non riproducibili da tastiera\, anche loro sono rappresentabili con delle entity

Un esempio sono i simboli matematici

∀ 	&\#8704; 	&forall; 		FOR ALL

∂ 	&\#8706; 	&part; 		PARTIAL DIFFERENTIAL

∃ 	&\#8707; 	&exist; 		THERE EXISTS

∅ 	&\#8709; 	&empty; 	EMPTY SETS

∇ 	&\#8711; 	&nabla; 	NABLA

∈ 	&\#8712; 	&isin; 		ELEMENT OF

∉ 	&\#8713; 	&notin; 		NOT AN ELEMENT OF

∋ 	&\#8715; 	&ni; 		CONTAINS AS MEMBER

∏ 	&\#8719; 	&prod; 		N\-ARY PRODUCT

∑ 	&\#8721; 	&sum; 		N\-ARY SUMMATION

HTML – entity \- simboli

Oltre ai caratteri riservati\, esistono una serie di caratteri non riproducibili da tastiera\, anche loro sono rappresentabili con delle entity

Un esempio sono i simboli matematici

∅ 	&\#8709; 	&empty; 	Vuoto

∈ 	&\#8712; 	&isin; 		Contenuto

∉ 	&\#8713; 	&notin; 		Non contenuto

Per un elenco completo è possibile utilizzare questo indirizzo

https://www\.w3schools\.com/charsets/ref\_utf\_math\.asp

HTML – entity \- emoji

Le entity possono rappresentare\, non solo caratteri\, ma anche emoji\, che vengono visualizzate come piccole immagini\, pur non essendolo\.

Le emoji sono caratteri provenienti dal charset Unicode UTF\-8 e sono sottoposte ad uno standard che si aggiorna in modo periodico

L’accortezza da avere per poter visualizzare i caratteri nel modo corretto è che la pagina inizi col metatag

__\<meta charset="UTF\-8">__

HTML – entity \- emoji

Di seguito alcuni esempi di emoji

✔	10004	2714

✖	10006	2716

✝	10013	271D

✡	10017	2721

✨	10024	2728

✳	10035	2733

✴	10036	2734

❄	10052	2744

Per un elenco completo è possibile utilizzare questo indirizzo

https://www\.w3schools\.com/charsets/ref\_emoji\.asp

HTML – entity \- emoji

Essendo immagini\, specificate tramite caratteri\, le emoji vengono rappresentate diversamente in base al sistema operativo\, sito web o applicazione che le rappresenta\.

https://www\.researchgate\.net/figure/Seven\-dierent\-implementations\-of\-three\-dierent\-Emoji\-The\-face\-with\-tears\-of\_fig16\_316168050

![](img%5CChapter_html14.png)

HTML – entity \- emoji – tonalità della pelle

Alcune emoji permettono di cambiare il colore della pelle\, per farlo si pone\, dopo l’entity della emoji\, un entity di colorazione

&\#127999; 🏿 Carnagione scura

&\#127998; 🏾 Carnagione abbastanza scura

&\#127997; 🏽 Carnagione media

&\#127996; 🏼 Carnagione abbastanza chiara

&\#127995; 🏻 Carnagione chiara

Di conseguenza\, se vogliamo colorare diversamente l’emoji della mano faremo

&\#9757; Nessun tono della pelle

&\#9757;&\#127999; Scuro

&\#9757;&\#127998; Medio Scuro

&\#9757;&\#127997; Medio

&\#9757;&\#127996; Luce media

&\#9757;&\#127995; Luce

Un form HTML serve a raccogliere l'input dell'utente\.

__Form __ è tag che inizia e finisce una maschera di acquisizione dati

< __form__  action="/action\.php">

\<label for="fname">Nome:\</label>\<br>

\<input type="text" id="fname" name="fname" value="Matteo">\<br>

\<label for="lname">Cognome:\</label>\<br>

\<input type="text" id="lname" name="lname" value="Baccan">\<br>\<br>

\<input type="submit" value="conferma">

</ __form__ >

HTML – form attributi

Il tag  __form __ ha una serie di attributi che ne modificano il comportamento

__target __ si comporta analogamente al target inserito all’interno di un tag  __a__

__method __ è il metodo col quale i parametri devono essere passati alla chiamata http di conferma\. Normalmente i metodi sono  __get__  o  __post__ \.

Se non indicato il default è  __get__

Ci sono delle implicazioni a livello di sicurezza e di gestione di cui tener conto quando viene scelto il metodo per inviare i dati

__autocomplete __ è una indicazione che viene data al browser\, che indica se automatizzare il completamento dei campi con dati che sono stati precedentemente digitati

__novalidate __ indica che i dati inseriti non devono essere validati al loro salvataggio

HTML – form elementi

Esistono più tag che rappresentano il modo col quale inserire dati in una form\.

Ognuno di essi ha delle proprie caratteristiche di utilizzo

\<input>

\<label>

\<select>

\<textarea>

\<button>

\<fieldset>

\<legend>

\<datalist>

\<output>

\<option>

\<optgroup>

HTML – form input

Il tag  __input __ è il primo tag utilizzato e serve ad inserire dei campi testuali monoriga\. Normalmente si lega ad un tag  __label__  che rappresenta la sua descrizione

\<label for="fname">Nome:\</label>

\<input type="text" id="fname" name="fname">

HTML – form input type

Uno degli attributi più interessanti di  __input __ è type\, che identifica il tipo di dati che verranno inseriti nel campo

button

checkboxcolor

date

datetime

datetime\-local

email

file

hidden

image

month

number

password

radio

range

reset

search

submit

tel

text

time

url

week

HTML – CSS Framework

Per facilitare la scrittura di pagine HTML sono nati col tempo una serie di framework CSS utili a velocizzare il lavoro

Fra i framework più noti ci sono

Boostrap

Foundation

Bulma

Tailwind

Uikit

Milligram

Pure CSS

Tachyons

Materialize CSS

HTML – Bootstrap

Cos'è Bootstrap?

Bootstrap è un framework front\-end gratuito\, progettato per essere mobile first

Bootstrap include modelli di progettazione basati su HTML e CSS per tipografia\, moduli\, pulsanti\, tabelle\, navigazione\, modali\, caroselli di immagini e molti altri\, oltre a plug\-in JavaScript opzionali

Bootstrap ti dà anche la possibilità di creare facilmente design reattivi

HTML – Bootstrap \- container

Boostrap fornisce 2 classi per definire un container

__\.container __

che fornisce un contenitore reattivo a larghezza fissa

__\.container\-fluid __

che fornisce un contenitore a larghezza intera\, che copre l'intera larghezza della finestra

HTML – Bootstrap \- grid

Il sistema a griglia di Bootstrap è costruito con flexbox e consente fino a 12 colonne nella pagina\.

Se non desideri utilizzare tutte e 12 le colonne singolarmente\, puoi raggruppare le colonne insieme per creare colonne più larghe

HTML – Bootstrap \- grid

il sistema a griglia Bootstrap 5 ha sei classi:

\.col\- \(dispositivi extra piccoli \- larghezza dello schermo inferiore a 576px\)

\.col\-sm\- \(piccoli dispositivi \- larghezza dello schermo uguale o superiore a 576px\)

\.col\-md\- \(dispositivi medi \- larghezza dello schermo uguale o superiore a 768px\)

\.col\-lg\- \(dispositivi di grandi dimensioni \- larghezza dello schermo uguale o superiore a 992px\)

\.col\-xl\- \(dispositivi xlarge \- larghezza dello schermo uguale o superiore a 1200px\)

\.col\-xxl\- \(dispositivi xxlarge \- larghezza dello schermo uguale o superiore a 1400px\)

Le classi di cui sopra possono essere combinate per creare layout più dinamici e flessibili\.

HTML – Bootstrap \- table

Boostrap dispone di classi predisposte per la visualizzazione dei tag  __table__

Per utilizzarle è sufficiente indicarle a livello di attributo  __class__

__\<table class="table">__

__…__

__\</table>__

__\<table class="table table\-striped">__

__…__

__\</table>__

__\<table class="table table\-hover">__

__…__

__\</table>__

__\<table class="table table\-bordered">__

__…__

__\</table>__

https://getbootstrap\.com/docs/5\.0/content/tables/

HTML – Bootstrap \- testi

Boostrap modifica lo stile standard dei tag tipografici\, come  __h1\, h2\, h3 \.\. h6__ \, ma soprattutto aggiunge una serie di classi per la formattazione dei testi:

\.text\-start 			Allinea il testo a sinistra

\.text\-center 		Allinea al centro

\.text\-decoration\-none 	Rimuove la sottolineatura da un collegamento

\.text\-end 			Allinea a destra

\.text\-nowrap 		Evita il ritorno a capo

\.text\-lowercase 		Minuscolo

\.text\-uppercase 		Maiuscolo

\.text\-capitalize 		Iniziale in maiuscolo

HTML – Bootstrap – colori testo

Boostrap aggiunge una serie di classi utili per raggruppare dei contesti in base ai colori\. Queste classi possono essere sovrascritte da template CSS integrativi

\.text\-muted

\.text\-primary

\.text\-success

\.text\-info

\.text\-warning

\.text\-danger

\.text\-secondary

\.text\-white

\.text\-dark

\.text\-body

\.text\-light

HTML – Bootstrap – colori sfondo

Boostrap anche gli sfondi hanno delle colorazioni contestuali

\.bg\-primary

\.bg\-success

\.bg\-info

\.bg\-warning

\.bg\-danger

\.bg\-secondary

\.bg\-dark

\.bg\-light

HTML – Bootstrap – immagini

Per quanto riguarda le immagini\, sono state introdotte una serie di classi che aiutano la loro visualizzazione e allineamento

\.rounded 		Arrotonda gli angoli dell’immagine

\.rounded\-circle 	Mette l’immagine in un cerchio

\.img\-thumbnail 	Mette un bordo all’immagine

\.float\-start		Allinea a sinistra

\.float\-end		Allinea a destra

\.mx\-auto \(margin:auto\) ed \.d\-block \(display:block\)	Permettono la centratura

\.img\-fluid		Crea un’immagine responsive applicando 				max\-width: 100%; e height: auto;

HTML – Bootstrap – Jumbotron

jumbotron è un grande box con lo scopo di richiamare l'attenzione su alcuni contenuti

__\<div class="jumbotron">__

__  __  __\<h1>Titolo\</h1>__

__  __  __\<p>testo testo testo testo testo testo testo testo testo testo \</p>__

__\</div>__

HTML – Bootstrap – Alert

Le classi di alert servono ad evidenziare un testo utilizzando un contesto\, come nel caso dei testi

__\<div class="alert alert\-success">__

__  __  __\<strong>SUCCESSO\</strong> hai fatto qualcosa di perfetto__

__\</div>__

Le tipogie di classi di alert si sovrappongono a quelle già viste per i testi

\.alert\-success \.alert\-info \.alert\-warning \.alert\-danger \.alert\-primary \.alert\-secondary \.alert\-light \.alert\-dark

Come classi di supporto agli alert è possibile anche usare

\.alert\-dismissible	Alert chiudibile

\.fade \.show		Alert con un fade in chiusura

HTML – Bootstrap – Button

Come per testi e alert\, anche i button hanno delle classi relative al contesto

__\<button type="button" class="btn">Basic\</button>__

__\<button type="button" class="btn btn\-primary">Primary\</button>__

__\<button type="button" class="btn btn\-secondary">Secondary\</button>__

__\<button type="button" class="btn btn\-success">Success\</button>__

__\<button type="button" class="btn btn\-info">Info\</button>__

Le tipogie di classi di btn si sovrappongono a quelle già viste per i testi

\.btn\-success \.btn\-info \.btn\-warning \.btn\-danger \.btn\-primary \.btn\-secondary \.btn\-light \.btn\-dark

Come classi di supporto ai button è possibile usare le stesse classi con aggiunta di  __outline__

\.btn\-outline\-primary \.btn\-outline\-secondary \.\.\.

HTML – Bootstrap – Badge

I badge sono delle etichette di testo che subiscono il contesto come button e text

__\<h1>Esempio di intestazione \<span class="badge bg\-secondary">badge\</span>\</h1>__

In questo caso il suffisso da usare è __ bg__

La classe di supporto dei badge è

__rounded\-pill__ 	Arrotonda i bordi del badge

