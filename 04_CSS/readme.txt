Separation of Concerns è un design principle cioè separazione delle responsabilità


HTML hypertext markup language un linguaggio di formattazione per ipertesti
- ipertesti testi con link
- struttura logica della pagina


CSS         Cascade      style sheet    un insieme di regole (dichiarazioni) applicate a cascata
si occupa di fornire uno style agli elementi HTML (rendere belli graficamente gli elementi HTML)

Come si può applicare il CSS agli elementi HTML?
- inline attraverso l'attributo style 
- embedded  attraverso l'elemento style dentro head
- file esterno attraverso l'elemento link dentro head


L'elemento HTML link è utile per collegare la pagina html entro cui è stato utilizzato con la risorsa avete url specificato nell'attributo href


Sintassi CSS:
selector {
    property1: value1;
    property2: value2;
    property3: value3;
}


Per le parentesi graffe:
su windows: alt gr + shift + è
sul mac: option + shift + è


Commento multilinea
/*

*/



Selettori utili per selezionare gli elementi HTML su cui applicare lo style (ordinati per specificità dei selettori crescente cioè per importanza):
5) universal selector * utile per selezionare TUTTI gli elementi HTML della pagina
4) tag selector utile per selezionare TUTTI gli elementi HTML aventi quel tag 
3) class selector .nomeDellaClasse utile per selezionare TUTTI gli elementi HTML che appartengo ad una certa classe
2) id selector #nomeId
1) attributo style HTML




Color values:
- named color
- rgb(r, g, b)  0 <= r,g,b <= 255 (è una funzione CSS)   oppure rgba(r, g, b, a)   0 <= r,g,b <= 255  mentre  0.0 <= a <= 1.0
- 

base 10     base 16
0           0
1           1
2           2
3           3

9           9
10          A
11          B
12          C
13          D
14          E
15          F
16          10





Serif
Sans-Serif
Monospace
Cursive


font-weight (alias) spessore del carattere:
100 lighter
200
300 light
400 normal
500
600
700 bold
800
900 bolder

I valori più importanti sono:
100 lighter
300 light
400 normal
700 bold



# Esercizio
Prendendo ispirazione da un blog di ricette già esistente (ad esempio Giallo Zafferano):
    utilizzare due font (presi da Google Fonts - uno per tutti gli elementi ed uno per gli headings tag)
    applicare dei colori (sia sul il testo sia sul background dell'elemento)
prestando particolare attenzione alla specificità dei selettori!



# References
https://blog.marketing-espresso.com/colori-marketing/
https://m3.material.io/
https://materializecss.com/color.html










