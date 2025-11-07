attributi globali:
- id utile per identificare in maniera univoca un elemento HTML
- class sinonimo di insieme utile per raggruppare più elementi HTML
- style


tag semantici: elementi html con un ruolo ben specifico in relazione alla SEO (al pari dei div)
- nav è un contenitore di link di navigazione
- main


- article è un contenitore per del contenuto informativo (agli occhi dell'utente - ogni article deve avere un titolo):
    * indipendente dal contenuto informativo presente in altri article
    * self-contained cioè l'informazione è tutta contenuta al suo interno
- section è un contenitore utilizzatore per raggruppare ("una categoria") di contenuti legati tra loro a livello tematico (ogni section deve avere un titolo).
  L'elemento section deve essere utilizzato SOLO SE non sono presenti altri tag semantici più specifici.



- header è un contenitore utile per introdurre il contenuto presente nell'elemento parent
- footer è un contenitore utile per informazioni secondarie (di secondaria importanza) relative all'elemento parent

- aside è un contenitore per del contenuto informativo indirettamente collegato all'elemento parent



Elementi block:
form

Elementi inline:
input (self closing tag)
label
select
textarea

Gli elementi input possono essere di tipo differente:
- text
- number
- email
- password


Attributi form
- action destinazione dei dati
- method della richiesta http
- enctype encoding type cioè la formattazione dei dati

Formato application/x-www-form-urlencoded   and
name1=value1&name2=value2&name3=value3
firstname=Eric&lastname=Cartman






# Esercizio - Blog di Ricette
Prendendo ispirazione da un blog di ricette già esistente (ad esempio Giallo Zafferano), 
strutturare la pagina index.html utilizzando tutto ciò che abbiamo visto in HTML ed in particolare:
    tag semantici
    headings tag (sia article sia section devono presentare un heading tag)
    
Per le immagini utilizzare picsum.photos modificando opportunamente l'URL dell'immagine:
    https://picsum.photos/id/1/400/300

Creare una navbar che contiene un link interno per registrarsi come chef (pagina di iscrizione per gli chef).
Questa pagina deve presentare una form che richieda le seguenti informazioni:
    nome e cognome
    età
    email
    password
    chef stellato?
    accetti termini e condizioni?


# References
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/article
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/section
https://www.youtube.com/@NetNinja/playlists

