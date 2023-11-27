# Vue Slider

Partendo dal markup della versione svolta in js plain, rifare lo slider ma questa volta usando Vue.

## Bonus:

1- al click su una thumb, visualizzare in grande l'immagine corrispondente
2- applicare l'autoplay allo slider: ogni 3 secondi, cambia immagine automaticamente
3- quando il mouse va in hover sullo slider, bloccare l'autoplay e farlo riprendere quando esce

### Bonus 1

- aggiungo all'oggetto ritornato da data() la proprietà currentImg inizializzata a 0
- aggiungo a ogni thumb l'evento al click che richiama la funzione changeThumb che aggiorna il valore di currentImg con l'indice della thumbnail su cui ho cliccato
