# IT Academy - Data Science amb Python
## Tasca 2-A: Estructura de una Matriu
### Descripció
Anem a practicar i a familiaritzar-nos amb l'estructure de Matrius, dimensio, forma, vectorització i Broadcasting .


### Nivell 1

Treballem els conceptes de l'estructura d'una matriu, dimensió, eixos i la vectorització que ens permet reduir l'ús de for loops en operacions aritmètiques o matemàtiques..

- Exercici 1: 
  - Crea un np.array de una dimension, que inclogui l'almenys 8 nombres sencers, data type int64. Mostra la dimensió i la forma de la matriu. .

- Exercici 2: 
  - De la matriu de l'exercici 1, calcula el valor mitjà dels valors introduïts i resta la mitjana resultant de cada un dels valors de la matriu.
  
- Exercici 3:
  - Crea una matriu bidimensional amb una forma de 5 x 5. Extreu el valor màxim de la matriu, i els valors màxims de cadascun dels seus eixos.
  
### Nivell 2 

- Exercici 4:
  - Mostreu-me amb exemples de diferents matrius, la regla fonamental de Broadcasting que diu : "les matrius es poden transmetre / broadcast entre si les seves dimensions coincideixen o si una de les matrius té una mida d'1".
  
- Exercici 5:
  - Utilitza la Indexació per extreure els valors d'una columna i una fila de la matriu. I suma els seus valors.
  
- Exercici 6:
  - Mask la matriu anterior, realitzeu un càlcul booleà vectoritzat, agafant cada element i comprovant si es divideix uniformement per quatre.

  - Això retorna una matriu de mask de la mateixa forma amb els resultats elementals del càlcul.
   
- Exercici 7:
  - A continuació, utilitzeu aquesta màscara per indexar a la matriu de números original. Això fa que la matriu perdi la seva forma original, reduint-la a una dimensió, però encara obteniu les dades que esteu cercant.
  
### Nivell 3 

Manipulació d’imatges amb Matplotlib.

Carregareu qualsevol imatge (jpg, png ..) amb Matplotlib. adoneu-vos que les imatges RGB (Red, Green, Blue) són realment només amplades × alçades × 3 matrius (tres canals Vermell, Verd i Blau), una per cada color de nombres enters int8, manipuleu aquests bytes i torneu a utilitzar Matplotlib per desar la imatge modificada un cop hàgiu acabat.

Ajuda:Importeu, import matplotlib.image as mpimg. estudieu el metode mpimg.imread(()

- Exercici 8:
  - Mostreu-me a veure que passa quan eliminem el canal G Verd o B Blau. Hauries de utizar la indexacion per selecciones el canal que voleu anul·lar.

  - Utilitzar el mètode, mpimg.imsave () de la llibreria importada, per guardar les imatges modificades i que haureu de pujar al vostre repositori a github.