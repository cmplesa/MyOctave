# MyOctave

TEMA 2:


Încărcarea în memorie a unei noi matrice:

 Am realizat o colectie de matrice ***lm si o matrice de dimensiuni **msize.
In functia readmatrix se citesc dimensiunile matricei si se aloca memorie
pentru o matrice de acele dimensiuni care este bagata in lista de matrice la
indicele mn (reprezinta nr matricelor), iar dimensiunile sunt bagate si ele in
matricea de dimensiuni. Dupa aceste operatii, se citeste matricea si se mareste
contorul mn.

Determinarea dimensiunilor unei matrice:

 Citesc in main indicele matricei ale carei dimensiuni vreau sa le aflu si dupa
caut in matricea de dimensiuni numarul de linii si coloane ale matricei alese

Afisarea unei matrice:

 Am citit indicele matricei pe care vr sa o afisez, daca acesta nu exista,se va
afisa mesajul "No matrix with the given index", dar daca exista se va apela
functia printmatrix si se va cauta in lm matricea cu indexul respectiv si va
fi afisata.

Redimensionarea unei matrice:

 Se citeste indicele matricei care se doreste a fi redimensionata si in functie
se citesc variabilele l si r care reprezinta numarul de linii/coloane dupa care
se face redimensionarea si se initializeaza 2 vectori ldx si cdx care pastreaza 
l/r indici (indicii de redimensionare). Se initializeaza o matrice rdmatr cu
l=nr linii si r =nr coloane si se egaleaza fiecare element cu elementrul din
matricea originala corespunzatoare cu linia si coloana indicata. Se elibereaza
acea zona de memorie din colectia de matrice si se egaleaza cu noua matrice
redimensionata.

Înmultirea a două matrice:

 Se citesc indicii celor 2 matrice, se verifica existenta matricelor si daca
poate fi realizata inmulitrea. Se aloca o noua matrice cu dimensiunile
potrivite si se realizeaza inmultirea si adaugarea in colectia de matrice.
 
Sortarea matricelor:

 Se ia fiecare matrice cu urmatoarea, se realizeaza suma elementelor din
fiecare matrice si cu ajutorul varabilelor aux si temp se face schimbul intre
matrice si dimensiunile acestora.

Transpunerea unei matrice:

 Se aloca memorie unei matrice cu dimensiunile inverse fata de cea initiala si
se interschimba indicele liniei cu cel al coloanei si se salveaza in locul
matricei initiale.
 
Ridicarea unei matrice la o putere în timp logaritmic:

 Se verifica daca puterea este 0 si daca este 0 se intoarce matricea
identitate. Daca puterea este para se calculeaza matricea la puterea n/2 si
inmulteste rezultatul cu el insusi la final. Daca puterea este impara, se cal
culeaza matricea la puterea (n-1)/2  si se inmulteste rezultatul cu el insusi
la final.

Eliberarea memoriei unei matrice:

 Se elibereaza memoria pentru matricea pe care vrem sa o stergem prin indicele
ales si dupa se muta la stanga cu o matrice toate matricele de la urmatoarea
pana la final.

Înmult, irea matricelor folosind algoritmul lui Strassen:

 In funcitia multiplier strassen se verifica dimensiunile si se aloca o matrice
rezultat dupa care se apeleaza algoritmul strassen cu impartirea in submatrice
si realizarea celor 7 produse si dupa calcularea celor 4 submatrice rezultat cu
ajutorul celor 7 produse si se pun in matricea rezultat.
 
