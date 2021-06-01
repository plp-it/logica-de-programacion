# Variables, constantes y operadores
<br/>


## **Variables**
<br/>
Son  elementos  de  almacenamiento  de  datos.  Representan  una  dirección  de  memoria  en  donde  se almacena un dato, que puede variar en el desarrollo del programa.

Existen distintos tipos de datos de variables dependiendo del lenguaje que se use, aqui una tabla con algunos tipos de datos:

![Imagen ilustrativa](https://2.bp.blogspot.com/-dHKVEs7IQwI/U-WG2Eq1jQI/AAAAAAAAAKw/4FBA6CN89wQ/s1600/28Wp8WXd.png)

Estos son algunos tipos de datos que se le pueden asignar a variables, como ya mencionado. A esta tabla se le puede agregar el tipo "string" que es de tipo cadena de texto alfanumerica.

<br/>

Al declarar variables estas deben seguir unas serie de reglas, no deben tener espacios en los nombres, no deben empezar con numero ni simbolos y deben comenzar en minuscula. Para los espacios hay dos formas en las que se puede hacer, una representar esos espacios con guion bajo o camelCase que consta de capitalizar la segunda palabra como en el ejemplo que se muestra debajo. Vale destacar que la idea es capitalizar las palabras siguientes a la primera, en caso de tener tres palabras quedaria lo siguiente, numeroDeDocumento.

Por ejemplo, algunas variables declaradas en PSeInt con pseudocodigo:

```
Algoritmo primerAlgoritmo
	Definir varEntera Como Entero
	Definir varFloat Como Real
	Definir varBool Como Logico
	Definir varString Como Caracter
	varEntera <- 10
	varFloat <- 5.5
	varBool <- true
	varString <- "PLP IT"
FinAlgoritmo
```

Donde "<-" representa a la asignacion tipicamente usada en los lenguajes con un igual "="

<br/>


## **Constantes**
<br/>
Elementos de almacenamiento de datos. Representan una dirección de memoria en donde se almacena un dato pero que no varía durante la ejecución del programa. Se podría pensar en un ejemplo de necesitar utilizar  en  el  programa  el  número  pi,  como  el  mismo  no  varía,  se  puede  definir  una  constante  pi  y asignarle el valor 3.14. 

Generalmente en los lenguajes de programacion una forma de distinguir las constantes de las variables pueden ser por palabras claves como "const" para algunos lenguajes o simplemente al nombre ponerlo todo en mayuscula y si es mas de una palabra se usa el guion bajo para representar el espacio. Ejemplo: int NUMERO_PI = 3.14

<br/>

## **Operadores**
<br/>
Los programas de computadoras se apoyan esencialmente en la realización de numerosas operaciones aritméticas y matemáticas. Los operadores son símbolos especiales que sirven para ejecutar una determinada operación, devolviendo el resultado de la misma.

* Operador de asignacion: como ya hemos visto el operador de asignacion sirve para asignar un valor a una variable o constante, normalmente se representa con el signo "=",  (<- en PSeInt).
<br/>
<br/>

* Operadores aritmeticos: sirven para realizar operaciones aritmeticas.

Tabla Resumen Operadores Aritméticos:

| Operador | Significado |
|----------|-------------|
|    +     | suma        |
|    -     | resta       |
|    *     | producto    |
|    /     | division    |
|    %     | resto de division entera      |

<br/>
<br/>

* Operadores unitarios: Los operadores unitarios requieren sólo un operando; que llevan a cabo diversas operaciones, tales como incrementar/decrementar un valor de a uno, negar una expresión, o invertir el valor de un booleano. 


| Operador | Significado |
|----------|-------------|
|    ++     | operador  de  incremento;  incrementa  un valor de a 1        |
|    --    | operador   de   decremento;   Reduce   un valor de a 1       |
|    !    | operador     de     complemento     lógico; invierte el valor de un valor booleano    |

<br/>
<br/>

* Operadores condicionales: Son  aquellos  operadores  que  sirven  para  comparar  valores.  Siempre  devuelven  valores  booleanos: TRUE O FALSE. Pueden ser Relacionales o Lógicos.

<br/>
<br/>

* Operadores relacionales: Los operadores relacionales sirven para realizar comparaciones de igualdad, desigualdad y relación de menor o mayor. 

| Operador | Significado |
|----------|-------------|
|    ==     | igual a        |
|    !-    | diferente a      |
|    >   | mayor a    |
|    >=   | mayor o igual a    |
|    <   | menor a    |
|    <=   | menos o igual a    |

<br/>
Ejemplos: 

1. 3 > 5 = false

2. 5 == 5 = true

3. 8 != 7 = true

4. 10 <= 10 = true

<br/>
<br/>

* Operadores logicos: Los operadores lógicos (AND, OR), sirven para evaluar condiciones complejas. Se utilizan para construir  expresiones  lógicas,  combinando  valores  lógicos  (true  y/o  false)  o  los  resultados  de  los operadores relacionales.

| Operador | Significado |
|----------|-------------|
|    &&     | AND        |
|    ||    | OR      |

<br/>
Ejemplos:

1. 5 == 5 && 5 > 2 = true

2. 9 != 3 || 4 <= 10 = true

3. 5 > 8 && 10 == 10 = false

4. 1 >= 10 || 4 == 7 = false

<br/>

En el operador AND las dos condiciones deben ser verdaderas para que sea verdadero el conjunto de condiciones, en cambio con la el operador OR con solo una que se cumple ya el resultado sera verdadero.