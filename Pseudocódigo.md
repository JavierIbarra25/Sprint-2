S﻿etmana 2 → Sprint 2.

Crea un algoritme i el programa que l'implementa



Cal que defineixis l'algoritme del programa que, partint dels valors inicials d'amples i llargs, realitzi els càlculs i mostri els resultats d'aquests:



Piscina rectangular 1

llarg: 300 // ample: 150 // profunditat: 20

Piscina rectangular 2

llarg: 300 // ample: 80 // profunditat: 35



El programa ha de calcular i mostrar el resultat de calcular:

1. L'àrea que ocupa cadascuna de les dues piscines

1. El volum d'aigua que pot allotjar cadascuna de les dues piscines

1. Els valors d'ample i llarg de l'espai que ocuparien les dues piscines si les posem les dues una al costat de l'altre. Aquest espai tindrà un llarg igual al de qualsevol d'elles (totes dues tenen el mateix llarg), i un ample resultant de sumar els dos amples.

1. L'àrea que ocuparien les dues piscines quan estan una al costat de l'altre.

1. El volum d'aigua que allotjarien entre les dues.

1. El programa ha d'intercanviar1 els valors de profunditat de les dues piscines i tornar a calcular i mostrar el valor del volum d'aigua que pot encabir cada piscina amb aquestes noves mides.



Algoritme de càlcul d’àrees i volums de le piscines:



VAR {

// Piscina1

llarg = 300;

ample1 = 150;

profunditat1 = 20;



// Piscina2

llarg= 300;

ample2 = 80;

profunditat2= 35;



// Piscina3

llarg = 300;

ample3 = ample1 + ample2;

Profunditat3 = profunditat1 + profunditat2;



//Cálculs

AreaPiscina1, VolumPiscina2;

AreaPiscina2, VolumPiscina2;

AreaPiscina3, VolumPiscina3;

}

FVAR



\-------------------------------------------------------------------------------------------------------

// 1, 2

Var AreaPiscina1 = ample1 x llarg

print

Var VolumPiscina1 = AreaPiscina1 x profunditat1

print

Var AreaPiscina2 = ample2 x llarg

print

Var VolumPiscina2= AreaPiscina2 x profunditat2

print

// 3

llarg3 = 300;

ample3 = ample1 + ample2;

// 4, 5

Var AreaPiscina3 = ample3 x llarg (o AreaPiscina1 + AreaPiscina2)

print

VolumPiscina3 = VolumPiscina1 + VolumPiscina2

print

//6

Var profunditat= profunditat1

profunditat1 = profunditat2

profunditat2 = profunditat



VolumPiscina1 = AreaPiscina1 x profunditat1

print

VolumPiscina2 = AreaPiscina2 x profunditat2

print
