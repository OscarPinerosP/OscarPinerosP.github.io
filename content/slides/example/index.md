---
title: Slides
summary: 
authors: []
tags: []
categories: []
date: '2019-02-05T00:00:00Z'
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

## Conceptos Básico de Programación con Python

Aprende a programar en Python desde cero. En este curso te ayudaré a comprender los fundamentos y características esenciales del lenguaje de programación Python de una manera sencilla, fácil de comprender y sobre todo práctica. Comenzando con una pequeña introducción, conceptos como variables, tipos de datos y operadores. Veremos estructuras de control como condicionales y bucles, así como funciones y manejo de excepciones. Abordaremos temas como el manejo de diversos tipos de datos, como listas, tuplas, diccionarios y conjuntos, junto con sus operaciones y métodos asociados. El curso cubre el uso del módulo datetime para trabajar con fechas y horas, así como la gestión de zonas horarias con pytz. Además, se exploran temas clave como entrada/salida de datos, manejo de archivos y expresiones regulares entre otros. Para cada uno de los temas verás en todo momento ejemplos prácticos que te permitirán reforzar tus conocimientos, también te dejaré un notebook para que puedas practicar todos los conceptos vistos durante el curso. En resumen, este curso te proporcionará una base sólida para programar en Python, abordando desde los conceptos básicos hasta temas más avanzados, preparándote para desarrollar tus proyectos con confianza.

---

## Introducción

Python es un lenguaje de programación de alto nivel, interpretado y de propósito general. Fue creado por Guido van Rossum y su primera versión fue lanzada en 1991. Python se destaca por su sintaxis clara y legible, lo que lo hace muy accesible para programadores principiantes y facilita el mantenimiento del código.

---

## Que es Python?

Python es un lenguaje de programación de alto nivel, interpretado y de propósito general. Fue creado por Guido van Rossum y su primera versión fue lanzada en 1991. Python se destaca por su sintaxis clara y legible, lo que lo hace muy accesible para programadores principiantes y facilita el mantenimiento del código.

---

## Algunas características clave de Python incluyen

1. **Legibilidad del código:** Python hace hincapié en la legibilidad y la claridad del código, utilizando una sintaxis que permite a los programadores expresar conceptos en menos líneas de código que en otros lenguajes.
2. **Interpretado:** Python es un lenguaje interpretado, lo que significa que el código se ejecuta línea por línea por un intérprete en lugar de ser compilado antes de la ejecución. Esto facilita la experimentación y el desarrollo interactivo.
3. **Orientado a objetos:** Python es un lenguaje de programación orientado a objetos, lo que significa que permite la creación y manipulación de objetos que encapsulan datos y funciones.
4. **Amplia biblioteca estándar:** Python cuenta con una extensa biblioteca estándar que abarca desde manipulación de archivos y redes hasta interfaces gráficas de usuario (GUI), lo que facilita el desarrollo de una amplia variedad de aplicaciones.
5. **Multiplataforma:** Python es compatible con varias plataformas, lo que significa que el código escrito en Python puede ejecutarse en diferentes sistemas operativos sin modificaciones significativas.
6. **Comunidad activa:** Python cuenta con una gran y activa comunidad de desarrolladores que contribuyen a la mejora continua del lenguaje y proporcionan una amplia gama de bibliotecas y recursos.

---

Python se utiliza en una variedad de aplicaciones, como desarrollo web, análisis de datos, inteligencia artificial, aprendizaje automático, automatización de tareas, scripting, y más. Es considerado uno de los lenguajes de programación más populares y versátiles en la actualidad.

---

## Conceptos Básicos de Programación en Python

La programación en Python se basa en la creación y ejecución de instrucciones que guían a una computadora para realizar tareas específicas. Utiliza una sintaxis clara y legible, lo que facilita la escritura y comprensión del código, incluso para aquellos que están comenzando en la programación. Python es un lenguaje de alto nivel que aborda conceptos fundamentales como variables, tipos de datos, estructuras de control (como bucles y condicionales), funciones y manejo de errores. Su importancia radica en su versatilidad y accesibilidad, permitiendo a los programadores abordar una amplia gama de problemas, desde tareas sencillas hasta proyectos complejos de desarrollo de software. Además, Python es ampliamente utilizado en diversas áreas, como ciencia de datos, inteligencia artificial, desarrollo web y automatización, lo que lo convierte en una herramienta valiosa para profesionales y principiantes por igual.

---

### **Variables**

En programación Python, las variables son nombres simbólicos que se utilizan para almacenar y manipular datos en la memoria de un computador. Estos nombres están asociados a ubicaciones específicas en la memoria que contienen valores, como números, cadenas de texto, listas, objetos, entre otros. Las variables permiten a los programadores referirse a estos valores mediante un nombre significativo en lugar de tener que recordar la ubicación exacta en la memoria.

---

Para declarar una variable en Python, simplemente se asigna un valor a un nombre utilizando el operador de asignación (`=`). Aquí hay un ejemplo simple:

```python
# Declaración de una variable llamada 'edad' con el valor 25
edad = 25

# Declaración de una variable llamada 'nombre' con el valor "Juan"
nombre = "Juan"

# Declaración de una variable llamada 'lista_numeros' con una lista de números
lista_numeros = [1, 2, 3, 4, 5]

```

En el código anterior, `edad`, `nombre` y `lista_numeros` son nombres de variables, y cada uno tiene asignado un valor específico.

---

Es importante destacar que en Python no es necesario declarar explícitamente el tipo de variable, ya que el intérprete de Python infiere automáticamente el tipo de datos basándose en el valor asignado. Por ejemplo, en el código anterior, Python entenderá que `edad` es un entero (`int`), `nombre` es una cadena de texto (`str`), y `lista_numeros` es una lista (`list`).

---

### **Tipos de Datos Básicos**

Python ofrece varios tipos de datos básicos para trabajar con diferentes tipos de información. Aquí hay algunos de los tipos de datos más comunes en Python, junto con ejemplos:

- **Enteros (int):**
Representan números enteros sin decimales.

```python
edad = 25
numero_negativo = -10
```

- **Flotantes (float):**
Representan números con decimales.

```python
altura = 1.75
precio = 19.99
```

---

- **Cadenas de texto (str):**
Representan secuencias de caracteres.

    ```python
    nombre = "Juan"
    mensaje = 'Hola, ¿cómo estás?'
    ```

- **Booleanos (bool):**
Representan valores de verdad: Verdadero (`True`) o Falso (`False`).

    ```python
    es_mayor_de_edad = True
    esta_lloviendo = False
    ```

---

- **Listas:**
Almacenan secuencias ordenadas de elementos.

```python
numeros = [1, 2, 3, 4, 5]
colores = ['rojo', 'verde', 'azul']
```

- **Tuplas:**
Son similares a las listas, pero son inmutables (no pueden ser modificadas después de la creación).

```python
coordenadas = (10, 20)
dias_semana = ('lunes', 'martes', 'miércoles')
```

---

- **Diccionarios:**
Almacenan pares clave-valor para representar información estructurada.

```python
estudiante = {'nombre': 'Ana', 'edad': 21, 'curso': 'Python'}
```

- **Conjuntos:**
Colecciones no ordenadas de elementos únicos.

    ```python
    numeros_primos = {2, 3, 5, 7, 11}
    ```

---

Estos son solo algunos ejemplos de los tipos de datos básicos en Python. La flexibilidad en el manejo de tipos de datos es una de las características clave de Python.

---

### **La función type()**

La función `type()` en Python se utiliza para obtener el tipo de un objeto o valor. Puedes pasar un valor como argumento a la función `type()` y te devolverá el tipo de ese valor. Aquí tienes un ejemplo:

```python
edad = 25
tipo_edad = type(edad)

print(tipo_edad)  # Esto imprimirá <class 'int'>
```

En este ejemplo, `type(edad)` devuelve el tipo de la variable `edad`, que es un entero (`int`). La función `type()` es útil cuando necesitas verificar el tipo de un objeto en tiempo de ejecución o cuando deseas realizar ciertas operaciones según el tipo de dato de una variable.

---

Puedes utilizar `type()` con otros tipos de datos y objetos, como cadenas, listas, diccionarios, funciones, etc. Por ejemplo:

```python
nombre = "Juan"
tipo_nombre = type(nombre)

print(tipo_nombre)  # Esto imprimirá <class 'str'>

lista_numeros = [1, 2, 3, 4, 5]
tipo_lista = type(lista_numeros)

print(tipo_lista)  # Esto imprimirá <class 'list'>
```

Esta función es especialmente útil en situaciones donde necesitas realizar comprobaciones de tipo dinámicamente en tu código.

---

### **Operadores Básicos**

Python incluye una variedad de operadores básicos que permiten realizar diferentes operaciones en variables y valores. Aquí algunos de los operadores básicos en Python, junto con ejemplos:

- **Operadores Aritméticos:**
- `+` : Suma
- `-` : Resta
- `*` : Multiplicación
- `/` : División
- `%` : Módulo (devuelve el resto de la división)
- `*` : Exponenciación

---

```python
a = 10
b = 3
suma = a + b # 13
resta = a - b # 7
multiplicacion = a * b # 30
division = a / b # 3.3333 (en Python 3)
modulo = a % b # 1
exponente = a ** b # 1000
```

---

- **Operadores de Comparación:**
- `==` : Igual a
- `!=` : No igual a
- `<` : Menor que
- `>` : Mayor que
- `<=` : Menor o igual que
- `>=` : Mayor o igual que

---

```python
x = 5
y = 10
igual = x == y # False
no_igual = x != y # True
menor_que = x < y # True
mayor_que = x > y # False
menor_o_igual = x <= y # True
mayor_o_igual = x >= y # False
```

---

- **Operadores Lógicos:**
- `and` : Operador lógico AND
- `or` : Operador lógico OR
- `not` : Operador lógico NOT

    ```python
    a = True
    b = False
    resultado_and = a and b # False
    resultado_or = a or b # True
    resultado_not = not a # False
    ```

---

- **Operadores de Asignación:**
- `=` : Asignación simple
- `+=`, `=`, `=`, `/=` : Asignación con operación aritmética

    ```python
    x = 5
    x += 3 # Equivalente a x = x + 3 (x ahora es 8)
    ```

---

Estos son solo algunos ejemplos de los operadores básicos en Python. Puedes combinar estos operadores para realizar operaciones más complejas y expresiones en tu código.