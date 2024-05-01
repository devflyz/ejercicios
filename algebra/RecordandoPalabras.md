## Recordando Palabras
Volem programar una màquina que sigui capaç de recordar paraules. Donada una quantitat n de paraules, cal mostrar per pantalla si aquesta paraula ja ha aparegut (`repetida`) o no (`nova`) just després de llegir-la.
#### Input Format
Primera línia:
*   n: Quantitat de paraules que cal llegir.
Segona línia:
*   La resta de paraules a llegir (separades amb un espai).
#### Constraints
*   n\>0
#### Output Format
*   Cada cop que es llegeix una paraula, cal mostrar per pantalla `repetida` (si la paraula ja s'havia llegit) o `nova` (si és nova).
*   Cada missatge apareixerà a una nova línia.
**Sample Input 0**
1
hola
**Sample Output 0**
nova
**Sample Input 1**
3
hola amics meus
**Sample Output 1**
nova
nova
nova
**Sample Input 2**
3
hola amics hola
**Sample Output 2**
nova
nova
antiga
