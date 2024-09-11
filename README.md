# minecraft turtle

Repo to program Advanced Turtle. 
3 programs:
- scava dritto quadrato o cilindro
- scende fino al primo blocco solido e scava a spirale sul piano
- scava "a miniera": scende fino a livello desiderato con scala 2x2 e fa tunnel

Ogni programma deve avere:
- auto fueling se trova carbone o lava (servono secchi in inventario)
- auto dropping di ceste
- ritorna al punto di partenza se current fuel == distance from home
- comando per non raccogliere cobblestone (e derivati) per non riempirsi: MA: rischio di over performare il server con troppe entità (i blocchi non raccolti sono entità)
