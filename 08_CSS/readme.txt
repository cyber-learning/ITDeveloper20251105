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

