# README

Nume: Gogete Ioan-Robert, Balan Alexandra-Andreea

Grupa: 344C2

## Privire de ansamblu
Proiectul este format din doua aplicatii:
    
1. DispunereOptima - care calculeaza dispunerea optima pe stagii a doua baterii fiind data o greutate totala
2. calculatorEficienta - care primeste un fisier de input cu detalii despre drona:
    
    * un array de baterii care contine informatii despre capacitatea si greutatea bateriilor
    * greutatea dronei fara baterii
    * un profil energetic al motoarelor care reprezinta o functie a consumului de energie in functie de putere. Este necesar sa fie pasate doar cateva date, restul sunt interpolate.

## Dispunere optima

In cadrul acestei aplicatii am calculat dispunerea pentru doua baterii fiind data greutatea scheletului dronei si greutatea totala a bateriilor.

Ideal am fi dorit sa aplicat formula comentata pentru un numar N de baterii.

## Calculator de eficienta

Aplicatia primeste ca parametru numele fisierului de input. 

La initializare, profilul de eficienta interpoleaza datele pentru a aproxima consumul de curent la diferite greutati ale dronei. 

Mai departe, se calculeaza timpul de zbor al dronei neoptimizat ca sa poata fi comparat cu timpul optimizat. 


Timpul optimizat este dedus calculand timpul de zbor pentru fiecare stagiu al bateriilor si actualizata greutatea totala a dronei.

La final, aplicatia afiseaza gradul de optimizare.