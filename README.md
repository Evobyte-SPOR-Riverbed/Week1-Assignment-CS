# Week1-Assignment-CS

Sa se scrie un program care gestioneaza vanzarile unei cofetarii.

Vor exista urmatoarele functionalitati:

1.  Adaugare **prajitura**: `id`, `nume`, `descriere`, `pret`.
    
    `+delete`, `+update`, `+show all` => `CRUD` (Create Read Update Delete) 
    
Ex.:

| id | nume  | descriere      | pret |
| -- | ----- | -------------- | ---- |
| 1 | ecler | ciocolata vanilie si frisca | 20 |
| 2 | brownie | ciocolata | 14 |

2. Adaugare **vanzare**: `id`, `id_prajitura`, `bucati (1-100)`.

Ex.:
| id | id_prajitura  | bucati | _explicatie_ |
| -- | ------------- | --- | --------------- |
| 1  | 1             | 13  | Am vandut 13 ecleruri |
| 2  | 1             | 7  | Am vandut 7 ecleruri |
| 3  | 2             | 8  | Am vandut 8 brownies |
| 4  | 1             | 3 | Am vandut 3 ecleruri |
| 5  | 2             | 5 | Am vandut 5 brownies |


4. Afisarea vanzarilor ordonate descrescator dupa bucati.

Ex.:
| id | id_prajitura  | bucati |
| -- | ------------- | --- | 
| 1  | 1             | 13  | 
| 3  | 2             | 8  | 
| 2  | 1             | 7  |
| 5  | 2             | 5 |
| 4  | 1             | 3 | 

5. Afisarea prajiturilor ordonate crescator dupa media vanzarilor.

Ex.:
| id | nume  | descriere      | pret | media vanzarilor | _explicatie_ |
| -- | ----- | -------------- | ---- | ---------------- | ------------ |
| 2 | brownie | ciocolata | 14 | 6.5 | Am vandut brownies de 2 ori, cu cantitatile 8+5 => (8+5) / 2 |
| 1 | ecler | ciocolata vanilie si frisca | 20 | 7.67 | Am vandut ecleruri de 3 ori, cu cantitatile 13+7+3 => (13+7+3) / 3 |
