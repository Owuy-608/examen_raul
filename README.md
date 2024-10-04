# Sistemas de Numeración.

## Lo más faćil.

### Binario -> Octal (tabla de tres bits).

| A | B | C | Z |
|---|---|---|----|
| 0 | 0 | 0 | =0 |
| 0 | 0 | 1 | =1 |
| 0 | 1 | 0 | =2 |
| 0 | 1 | 1 | =3 |
| 1 | 0 | 0 | =4 |
| 1 | 0 | 1 | =5 | 
| 1 | 1 | 0 | =6 |
| 1 | 1 | 1 | =7 |

### Binario -> Hexadecimal (tabla de cuatro bits).

| A | B | C | D | Z |
|---|---|---|---|----|
| 0 | 0 | 0 | 0 | =0 |
| 0 | 0 | 0 | 1 | =1 |
| 0 | 0 | 1 | 0 | =2 |
| 0 | 0 | 1 | 1 | =3 |
| 0 | 1 | 0 | 0 | =4 |
| 0 | 1 | 0 | 1 | =5 | 
| 0 | 1 | 1 | 0 | =6 |
| 0 | 1 | 1 | 1 | =7 |
| 1 | 0 | 0 | 0 | =8 |
| 1 | 0 | 0 | 1 | =9 |
| 1 | 0 | 1 | 0 | =A |
| 1 | 0 | 1 | 1 | =B |
| 1 | 1 | 0 | 0 | =C |
| 1 | 1 | 0 | 1 | =D |
| 1 | 1 | 1 | 0 | =E |
| 1 | 1 | 1 | 1 | =F |

### Octal -> Hexadecimal.

Debes primero pasarlo a binario.

## Lo más difícil.

### Cualquiera de los tres -> Decimal (T.F.N)

__Dígito__ * Base^nª de la fila.

#### Binario -> Decimal.

1101.101

1 x 2<sup>3</sup> + 1 x 2<sup>2</sup> + 0 x 2<sup>1</sup> + 1 x 2<sup>0</sup> + 1 x 2<sup>-1</sup> + 0 x 2<sup>-2</sup> + 1 x 2<sup>-3</sup>

#### Octal -> Decimal.

132.5

1 x 8<sup>2</sup> + 3 x 8<sup>1</sup> + 2 x 8<sup>0</sup> + 5 x 8<sup>-1</sup>

#### Hexadecimal -> Decimal.

1A3.4

1 x 16<sup>2</sup> + A x 16<sup>1</sup> + 3 x 16<sup>0</sup> + 4 x 16<sup>-1</sup>

### Decimal -> Cualquiera de los tres (división).

Tienes que dividir el número que te dan por __2__ en caso del Binario, __8__ en caso del Octal y __16__ en caso del Hexadecimal. __Después tienes que coger lo números desde abajo hacia arriba (en sentido contrario al que haces la operación)__

## Conversión de Unidades de Datos.

### Bits a Bytes.
1 byte = 8 bits

### Kilobytes a Bytes.
1 KB = 1024 B

### Megabytes a Bytes.
1 MB = 1024 KB = 1024 × 1024 B = 1,048,576 B

### Gigabytes a Bytes.
1 GB = 1024 MB = 1,048,576 KB = 1,073,741,824 B

### Terabytes a Bytes.
1 TB = 1024 GB = 1,073,741,824 KB = 1,099,511,627,776 B

### Petabytes a Bytes.
1 PB = 1024 TB = 1,099,511,627,776 KB = 1,125,899,906,842,624 B

## Como se hace una regla de tres.
| 3 | 5 |
|---|---|
| 6 | x |

3x = 6 x 5
3x = 30
x = 30 / 3 = 10

# Operaciones Artiméticas y Lógicas.

## Suma.

- 0 + 0 = 0
- 1 + 0 = 1
- 0 + 1 = 1
- 1 + 1 = 0 (Se acarrea 1).

## Resta.

- 1 - 1 = 0
- 0 - 0 = 0
- 1 - 0 = 1
- 0 - 1 = 1 (Se acarrea 1).

## Divsion.

Se divide normal, y se resta.

# Puertas lógicas.

Las puertas lógicas son los bloques fundamentales de la electrónica digital, utilizadas para realizar operaciones lógicas básicas. Cada puerta lógica realiza una función específica basada en la combinación de sus entradas para producir una salida. A continuación se describen las puertas lógicas más comunes junto con su símbolo, definición, tabla de verdad, función y representación en circuitos.

## Puerta Lógica OR (Suma Lógica)

- **Símbolo:** ≥1
- **Definición:** Produce una salida alta si al menos una de las entradas es alta.
- **Tabla de Verdad:**
  | A | B | Salida |
  |---|---|--------|
  | 0 | 0 |   0    |
  | 0 | 1 |   1    |
  | 1 | 0 |   1    |
  | 1 | 1 |   1    |
- **Función:** S = A + B
- **Circuito:** Representación con dos entradas donde la salida es alta si alguna de las entradas es alta.

## Puerta Lógica AND (Multiplicación Lógica)

- **Símbolo:** &
- **Definición:** Produce una salida alta solo si todas las entradas son altas.
- **Tabla de Verdad:**
  | A | B | Salida |
  |---|---|--------|
  | 0 | 0 |   0    |
  | 0 | 1 |   0    |
  | 1 | 0 |   0    |
  | 1 | 1 |   1    |
- **Función:** S = A·B
- **Circuito:** Representación con dos entradas donde la salida es alta solo si ambas entradas son altas.

## Puerta Lógica NOT (Negación o Inversora)

- **Símbolo:** 1
- **Definición:** Invierte el estado de la entrada; si la entrada es alta, la salida es baja, y viceversa.
- **Tabla de Verdad:**
  | A | Salida |
  |---|--------|
  | 0 |   1    |
  | 1 |   0    |
- **Función:** S = ¬A
- **Circuito:** Representación con una entrada y una salida invertida.

## Puerta Lógica NAND (Negativa AND)

- **Símbolo:** &
- **Definición:** Produce una salida baja solo cuando todas las entradas son altas.
- **Tabla de Verdad:**
  | A | B | Salida |
  |---|---|--------|
  | 0 | 0 |   1    |
  | 0 | 1 |   1    |
  | 1 | 0 |   1    |
  | 1 | 1 |   0    |
- **Función:** S = ¬(A·B)
- **Circuito:** Representación con dos entradas donde la salida es baja solo si ambas entradas son altas.

## Puerta Lógica NOR (Negativa OR)

- **Símbolo:** ≥1
- **Definición:** Produce una salida baja si al menos una de las entradas es alta.
- **Tabla de Verdad:**
  | A | B | Salida |
  |---|---|--------|
  | 0 | 0 |   1    |
  | 0 | 1 |   0    |
  | 1 | 0 |   0    |
  | 1 | 1 |   0    |
- **Función:** S = ¬(A + B)
- **Circuito:** Representación con dos entradas donde la salida es baja si alguna de las entradas es alta.

## Puerta Lógica XOR (Exclusiva OR)

- **Símbolo:** =1
- **Definición:** Produce una salida alta si el número de entradas altas es impar.
- **Tabla de Verdad:**
  | A | B | Salida |
  |---|---|--------|
  | 0 | 0 |   0    |
  | 0 | 1 |   1    |
  | 1 | 0 |   1    |
  | 1 | 1 |   0    |
- **Función:** S = A ⊕ B
- **Circuito:** Representación con dos entradas donde la salida es alta si las entradas son diferentes.

Estas puertas lógicas son esenciales para la construcción de circuitos más complejos y para la realización de cálculos y operaciones lógicas en sistemas digitales.
