pseudo-elementi
    ::before
    ::after
    ::placeholder



position:
- static (il valore di default)
- relative
- absolute
- fixed
- sticky è una via di mezzo tra relative e fixed


In combinazione con la proprietà position è necessario utilizzare (sempre) le proprietà:
- top oppure bottom
- left oppure right


Un elemento con position relative si posiziona rispetto alla posizione che lui stesso occupa normalmente

Un elemento con position absolute si posiziona rispetto:
- al primo antenato che ha (a sua volta) proprietà position diversa dal valore di default
- altrimenti rispetto al body


su un elemento avente position diversa da static posso utilizzare la proprietà z-index



# Esercizio FAB
Creare un bottoncino rotondo chiamato Floating Action Button da posizionare in basso a destra rispetto alla viewport

# Esercizio - Modal
Creare un modal posizionato al centro della viewport su sfondo nero in trasparenza.

Prevedere la presenza di una classe in grado di nascondere il modal.

# Esercizio - Pagina Responsive
Ricreare una pagina simile alla seguente https://www.w3schools.com/w3css/tryw3css_templates_band.htm
Prestare particolare attenzione al layout (che deve essere responsive)





Trasformazioni:
- traslazioni
- rotazioni
- cambi di scala


Per utilizzare una animazione sono necessari 2 passaggi:
1) definizione degli stati dell'animazione tramite keyframes (cioè definizione dell'animazione)
2) applicare l'animazione sugli elementi HTML selezionati




@keyframes nomeAnimazione {
    from {

    }

    to {
        
    }
}





animation-fill-mode al valore:
- backwards applica immediatamente il CSS definito nello stato iniziale anche prima che l'animazione inizii
- forwards mantiene il CSS definito nello stato finale
