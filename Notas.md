# Introduccion
* Las funciones son la base para las redes neuronales
* Permiten modelar nuestra realidad
* Se aprendera como crearlas, modelarlas y programarlas

# ¿Qué es una función?
* Un valor se determina por otros factores
* En este curso se vera como un valor puede variar en base a un solo factor o tmabién conocido como variable
* Funciones de una variable. Son aquellas operaciones que permiten obtener un valor en base a uno sola variable o factor
* Una función es como una máquina, donde entra un elemento ```x``` y sale un elemento ```y```

Su fórmula algebráica es: $y = f(x) $

Entonces, una **función** es una *regla* donde cada elemento de un *conjunto X*, se le *asigna* un elemento de *conjunto de Y*

## Formas de representar una función

* Verbalmente
* Numéricamente
* Visualmente
* Algebráicamente

### Verbal
```
El precio aumenta 2 dólares por cada kilómetro recorrido.
Uber
```
### Numérica
Teniendo una tabla de valores. Variable independiente, columna 1. Variable dependiente, columna 2

| x | f(x) |
|---|------|
|-14|  4   |
|-6 |  2   |
|-25|  0   |

### Visual

Por medio de una gráfica. Parábola

### Algebráica
$y = f(x) = x^2 $

# Las funciones sirven para modelar nuestra realidad

# Variables
![Variables](/img/variables.png)

Las **variables cuantitativas** se usan en las funciones para modelar 

|Tipo | Variable | descripción |
|-----|----------|-------------|
|Cuantitativa| Discreta | Números enteros. Son finitas. Por ejemplo una persona puede tener 0, 1, 2 o 3 amigos, pero nunca 4.5|
|Cuantitativa| Continua | Números decimales. Pueden ser infinitos al tomar cualquier valor dentro de los números reales en un rango establecido. Por ejemplo, medir la estatura de una persona, 1.80m, 1.56m, etc|
|Cualitativa | Nominal | Se les asigna una cualidad. Por ejemplo, el carro es **azul** |
|Cualitativa | Ordinaria | La que está ordenada, por ejemplo, la altura de un objeto se puede clasificar como alto, medio o bajo|
|Cualitativa | Binaria | Son aquellas que toman dos valores y son usadas para representar estados o condiciones. Falso, verdadero, esl objeto está frío o caliente, uno o cero, etc|

# Dominio y Rango de una función

- [ ] El **dominio** son los valores que toma ```x```
- [ ] El **rango** son *todos* los resultados que nos puede dar una función
![Dominio-Rango-Funcion](/img/cafe_dominio_rango_funcion.png)

# Leer símbolos matemáticos

| simbolo | Tipo | Significa | Lectura | Ejemplo |
|---------|------|-----------|---------|---------|
| $=$ | igualdad | *igual que* |2 es *igual que* uno mas uno | $2 = 1+1$ |
| $>$ | relacion | *mayo que* | 5 es *mayor que* 3 | $5 > 3$ |
| $<$ | relacion | *menor que* | 4 es *menor que* 7 | $4 < 7$ |
| $≥$ | igualdad y relacion | *mayor o igual* | Usado para establecer rangos. ```x``` es *mayor o igual* que ```y``` | $x ≥ y$ ( $7 ≥ 2$ , $7 ≥ 7$ )|
| $≤$ | igualdad y relacion | *menor o igual que* | ```x``` es *menor o igual* que ```y``` | $x ≥ y$ ( $15 ≤ 31$ , $15 ≤ 15$ )|
| $≠$ | igualdad | *diferente de* |4 es *diferente de* 3 | $4 ≠ 3$ |
| $≈$ | relacion | *aproximado de* | 5 es *aproximado de* 4.999 | $5 ≈ 4.999$|
| $>>$ | relacion | *mayor mayor que* 😜 | 100000 es *mayor mayor que* 1 | $100000 >> 1$ |
| $<<$ | relacion | *menor menor que* 😜 | 1/10000 es *menor menor que* 1000 | $1/10000 << 10000$ |
| $∞$ | relacion | numero muy grande | puede ser positivo $∞+$ | o puder ser negativo $∞-$ |
| $∑$ | acumulativo | *sumatoria de* | Conocido como *sigma* y tiene un límite inferior $n=0$ , y tiene un límite superior $3$ | $$  \sum_{n=0}^3   $$ |
| $∏$ | acumulativo | *producto de* | Tiene un límite inferior y un límite superior | $$ \prod_{n=1}^{n=4} $$ |