## Tarjeta de crédito válida

*Crea una web que pida, por medio de un prompt(), el número de una tarjeta de crédito y confirme su validez según el algoritmo de Luhn.*

#### Consideraciones Específicas

+ Tu código debe estar compuesto por 1 función: isValidCard.
+ El usuario no debe poder ingresar un campo vacío.

Se pedirá al usuario por medio de un prompt que *"Ingrese el número de la tarjeta de crédito"*.

Se debe pasar los números del array inversos. por medio de un "for" el cuál nos permitirá recorrer los números ingresados.

Se aplica la operación multiplicación por dos a los números que se encuentrene en la posición par. Si el doble de ese resultado es mayor o igual a 10 se procede a sumar los digitos del número.

Sumar digitos y nuevos digitos.
Comprobar si es una tarjeta válida. Despúes de las anteriores operaciones se necesitará el residuo de la división entre 10 y el resultado de la suma.