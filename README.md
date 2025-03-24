# T1. PR1. Seguretat i vulnerabilitat - Alvaro Cobo

## Exercici 1.
**L’organització OWASP Foundation va actualitzar en 2021 el seu Top 10 de vulnerabilitats més trobades en aplicacions web.**
- Escull 3 vulnerabilitats d’aquesta llista i descriu-les. Escriu l’impacte que tenen a la seguretat i quins danys pot 
arribar a fer un atac en aquesta vulnerabilitat. Enumera diferents mesures i tècniques per poder evitar-les.

***

## Excercici 2.
**Obre el següent enllaç ([sql inseckten](https://www.sql-insekten.de/)) i realitza un mínim de 7 nivells fent servir tècniques d’injecció SQL.**
- Copia cada una de les sentències SQL resultant que has realitzat a cada nivell i comenta que has aconseguit.
- Enumera i raona diferents formes que pot evitar un atac per SQL injection en projectes fets amb Razor Pages i Entity Framework. 

***

## Exercici 3
**L’empresa a la qual treballes desenvoluparà una aplicació web de venda d’obres d’art. Els artistes registren les seves obres amb fotografies, 
títol, descripció i preu.  Els clients poden comprar les obres i poden escriure ressenyes públiques dels artistes a qui han comprat. Tant 
clients com artistes han d’estar registrats. L’aplicació guarda nom, cognoms, adreça completa, dni i telèfon. En el cas dels artistes guarda 
les dades bancàries per fer els pagaments. Hi ha un tipus d’usuari Account Manager que s’encarrega de verificar als nous artistes. Un cop aprovats 
poden pública i vendre les seves obres.**

**Ara es vol aplicar aplicant els principis  de seguretat per tal de garantir el servei i la integritat de les dades. T’han encarregat l'elaboració 
de part de les polítiques de seguretat. Elabora els següents apartats:**
- a) Definició del control d’accés: enumera els rols  i quin accés a dades tenen cada rol.
- b) Definició de la política de contrasenyes: normes de creació, d’ús i canvi de contrasenyes. Raona si són necessàries diferents polítiques segons el perfil d’usuari.
- c) Avaluació de la informació: determina quin valor tenen les dades que treballa l'aplicació. Determina com tractar les dades més sensibles. Quines dades encriptaries?
***

## Exercici 4
**En el control d’accessos, existeixen mètodes d’autenticació basats en tokens. Defineix l’autenticació basada en tokens. Quins tipus hi ha? Com 
funciona mitjançant la web? Cerca llibreries .NET que ens poden ajudar a implementar autenticació amb tokens.**

***

## Exercici 5
**Crea un projecte de consola amb un menú amb tres opcions:** 
- a) Registre: l’usuari ha d’introduir username i una password. De la combinació dels dos camps guarda en memòria directament l'encriptació. Utilitza 
l’encriptació de hash HA256. Mostra per pantalla el resultat.
- b) Verificació de dades: usuari ha de tornar a introduir les dades el programa mostra per pantalla si les dades són correctes.
- c) Encriptació i desencriptació amb RSA. L’usuari entrarà un text per consola. A continuació mostra el text encriptat i en la següent línia el text 
desencriptat. L’algoritme de RSA necessita una clau pública per encriptar i una clau privada per desencriptar. No cal guardar-les en memòria persistent.

***

## Exercici 6 (Bibliografia)