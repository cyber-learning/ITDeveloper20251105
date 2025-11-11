pseudo-classi utili per selezionare degli elementi HTML che si trovano in un certo stato (situazione)
    :root
    :hover
    :focus
    :first-child
    :last-child


La pseudo-classe :root è utile per:
- dichiarare le variabili (globali) del CSS
- dichiarare il font-size di base




unità di misura assolute:
- px

unità di misura relative (layout):
- %
- vw vh

unità di misura relative (font):
- em un coefficiente moltiplicato per il font-size dell'elemento stesso
- rem root em un coefficiente moltiplicato per il font-size di base (dichiarato nella pseudoclasse root)





Viewport virtuale avente width 980px


Responsive Design sviluppare pagine web che ben siano visualizzate (mostrate) per larghezze di schermo differenti
Responsive Design con approccio:
- mobile first      media query con min-width
- desktop first     media query con max-width

Responsive Design con approccio mobile first:
1) sviluppiamo la pagina affinchè sia ben visualizzata su mobile
2) effettueremo il numero MINIMO di modifiche al layout affinchè la nosta pagina sia ben visualizzata per larghezze di schermo via via crescenti


@media condizione {
    CSS
}


@media screen and (min-width: 400px) {
    p {
        background-color: green;
    }
}

if(screenWidth >= 400px) {
    p {
        background-color: green;
    }
}


# References
https://getbootstrap.com/docs/5.3/layout/breakpoints/






