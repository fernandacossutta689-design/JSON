# JSON

1- ¿Que es JSON?
2- Estructura basica, tipo de datos soportados

## Actividad 
Crear un ejemplo basico de persona. Contendra nombre, edad, mail y el id. Se debera cargar al menos 10 personas. 

### Respuestas
1- Json (JavaScript Object Notation) es un formato ligero de intercambio de datos, es un estándar universal para enviar información entre un servidor y una aplicación web o móvil. 

### Estructura basica:

Objetos { }: Es una colección de pares {llave: valor}. 
Las llaves siempre deben ser cadenas de texto entre comillas dobles, seguidas de dos puntos y luego el valor.

Arreglos [ ]: Es una lista ordenada de valores separados por comas. 
Los valores pueden ser de cualquier tipo, incluso otros objetos o arreglos.

### tipo de datos:
Cadena (String): Secuencia de cero o más caracteres Unicode encerrados entre comillas dobles ("texto").
Número (Number): Números enteros o de punto flotante (positivos, negativos o con exponente) sin comillas.
Booleano (Boolean): Valores lógicos true (verdadero) o false (falso), escritos sin comillas.
Nulo (Null): Representa la ausencia de valor o un valor vacío, escrito como null.
Objeto (Object): Conjunto desordenado de pares clave-valor (ej. {"nombre": "Ana"}), envuelto en llaves {}.
Matriz (Array): Lista ordenada de valores (pueden ser de distintos tipos), envuelta en corchetes []. 

## Actividad 
[
  {
    "id": 1,
    "nombre": "Elena García",
    "edad": 28,
    "mail": "elena.garcia@gmail.com"
  },
  {
    "id": 2,
    "nombre": "Marcos López",
    "edad": 34,
    "mail": "marcos.lopez@gmail.com"
  },
  {
    "id": 3,
    "nombre": "Sofía Martínez",
    "edad": 22,
    "mail": "sofia.mtz@gmail.com"
  },
  {
    "id": 4,
    "nombre": "Javier Solís",
    "edad": 45,
    "mail": "javier.solis@gmail.com"
  },
  {
    "id": 5,
    "nombre": "Lucía Torres",
    "edad": 31,
    "mail": "lucia.torres@gmail.com"
  },
  {
    "id": 6,
    "nombre": "Andrés Castro",
    "edad": 29,
    "mail": "andres.castro@gmail.com"
  },
  {
    "id": 7,
    "nombre": "Valeria Ríos",
    "edad": 26,
    "mail": "valeria.rios@gmail.com"
  },
  {
    "id": 8,
    "nombre": "Diego Navarro",
    "edad": 40,
    "mail": "diego.nav@gmail.com"
  },
  {
    "id": 9,
    "nombre": "Camila Peña",
    "edad": 24,
    "mail": "camila.pena@gmail.com"
  },
  {
    "id": 10,
    "nombre": "Ricardo Vega",
    "edad": 37,
    "mail": "ricardo.vega@gmail.com"
  }
  
]
