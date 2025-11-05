HTML hypertext markup language un linguaggio di formattazione per ipertesti utile per definire una struttura logica della pagina


# Sintassi
La sintassi di un elemento HTML è:
<tag attribute1="value1" attribute2="value2">content</tag>


Headings tag
h1
h2
h3
...
h6


p Paragraph tag
a anchor tag Link - attributo href hypertext reference




# Commenti:
- Mac ctrl + shift + 7      ctrl + /
- Windows alt + shift + a     ctrl + /



URL in rete                                     ->      Path del file system
http://127.0.0.1:5500/index.html                ->      02_HTML/index.html
http://127.0.0.1:5500/chefs.html                ->      02_HTML/chefs.html 
http://127.0.0.1:5500/ricette/involtini.html    ->      02_HTML/ricette/involtini.html





# Esercizio - AboutMe
Creare una fantastica pagina web di presentazione personale, stile anni '90,
che punta al vostro account Instagram o TikTok o entrambi usando gli heading, paragraph e links

# Esercizio
Creare un sito formato da più pagine html oltre alla pagina index.html

# Esercizio - Link Esterni e Link Interni
Creare più link esterni.
Creare, ancora, più link interni (al sito stesso).
Creare una sotto-directory contenente pagine html (ad esempio users contenente le pagine degli utenti) e aggiungere i link alle pagine presenti nella directory





# Box Model descrive quanto spazio occupa un elemento HTML

Block Level Elements (nascono per definire un layout)
- si allargano il più possibile (da migliorare in CSS width: 100% )
- sono impilati in verticale (uno sotto l'altro)

body
div generica divisione della pagina (una parte della pagina) - il contenitore per eccellenza di tipo block
h1, ..., h6
p
ul li   unordered list  list item
ol li   ordered list    list item



Inline Level Elements (nascono per contenere testo)
- sono larghi tanto quanto il contenuto testuale
- sono impilati in orizzontale (uno di fianco all'altro)

span il contenitore per eccellenza di tipo Inline
a
img




Elementi HTML innestati (nested):
Un elemento block può contenere al suo interno:
- elementi block
- elementi inline
- puro testo


Un elemento inline può contenere al suo interno:
- elementi inline
- puro testo


Eccezione alla regola:
gli elementi h1, ..., h6 e p sono elementi block strani poichè possono contenere solo:
- testo
- altri elementi inline
In sostanza, negli elementi h1, ..., h6 e p NON posso innestare altri elementi block



Self-closing tags: Elementi HTML che non possono avere del contenuto
img



# References
https://developer.mozilla.org/en-US/docs/Web/HTML/Guides


siblings