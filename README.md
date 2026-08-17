# TP0-PARADIGMAS-EXEQUIEL-ALANIZ
# Trabajo Práctico 0

### Análisis sobre lenguajes de programación en base a la lógica paradigmática

### Exequiel Alaniz - Ingeniería en Sistemas

## Ejercicio 1 - C

### 1. Generalización simbólica: ¿Cuáles son las reglas escritas del lenguaje?

**Respuesta:** El uso del `;` al final de las instrucciones, el uso de estructuras de control, la declaración de variables y funciones, el manejo de punteros para acceder directamente a posiciones de memoria y la gestión manual de la memoria mediante funciones como `malloc()` y `free()`. También permite trabajar con estructuras y distintos tipos de datos.

### 2. Creencias de los profesionales: ¿Qué características particulares del lenguaje se cree que sean "mejores" que en otros lenguajes?

**Respuesta:** C está pensado para permitir una manipulación bastante directa de la memoria, a diferencia de otros lenguajes donde esta gestión es automática. Esto permite tener un mayor control sobre los recursos y puede generar programas muy eficientes. Además, es un lenguaje muy utilizado y disponible en una gran cantidad de plataformas, y cuenta con una gran cantidad de bibliotecas.

### 3. Valores: ¿Qué pensamiento o estilo de programación consideraron mejor los creadores?

**Respuesta:** Es un lenguaje de bajo nivel relativamente simple, pensado para ser eficiente y portable. Fue creado como una alternativa más práctica al lenguaje ensamblador para desarrollar sistemas operativos y software de sistemas. En pocas palabras, C fue pensado buscando principalmente eficiencia, portabilidad y simplicidad.

### 4. Ejemplares: ¿Qué clase de problemas pueden resolverse más fácilmente en el lenguaje?

**Respuesta:** C permite resolver muchos tipos de problemas, pero resulta especialmente útil para problemas relacionados con sistemas operativos, sistemas embebidos, control de hardware, desarrollo de software de sistemas y programas donde sea importante tener un control preciso sobre los recursos de la computadora.

---

## Ejercicio 1 - JAVA

### 1. Generalización simbólica: ¿Cuáles son las reglas escritas del lenguaje?

**Respuesta:** Java está basado en conceptos de C y C++, pero utiliza principalmente el paradigma orientado a objetos y posee una gestión automática de memoria mediante el recolector de basura (Garbage Collector), por lo que el programador no necesita utilizar funciones como `malloc()` y `free()`. Java utiliza clases y objetos como elementos principales de su estructura, aunque también posee tipos primitivos como `int`, `double` y `char`.

### 2. Creencias de los profesionales: ¿Qué características particulares del lenguaje se cree que sean "mejores" que en otros lenguajes?

**Respuesta:** Una de sus principales características es la portabilidad gracias a la JVM (Java Virtual Machine), ya que un programa compilado puede ejecutarse en diferentes sistemas operativos siempre que exista una JVM compatible. También se considera una ventaja la gestión automática de memoria, porque reduce la posibilidad de cometer ciertos errores relacionados con la memoria. Además, Java posee mecanismos de seguridad y un sistema de tipos bastante estricto.

### 3. Valores: ¿Qué pensamiento o estilo de programación consideraron mejor los creadores?

**Respuesta:** Java fue pensado principalmente para trabajar con programación orientada a objetos, buscando que fuera relativamente fácil de utilizar y portable entre diferentes plataformas. Sus creadores tomaron ideas de otros lenguajes, especialmente C y C++, intentando conservar algunas de sus características útiles y reducir problemas asociados a ellos, como la gestión manual de memoria.

### 4. Ejemplares: ¿Qué clase de problemas pueden resolverse más fácilmente en el lenguaje?

**Respuesta:** Java puede utilizarse para desarrollar aplicaciones web, aplicaciones empresariales, aplicaciones de escritorio, aplicaciones para dispositivos y sistemas que necesiten ejecutarse en diferentes plataformas. También es utilizado en sistemas de gran escala debido a su portabilidad y a la cantidad de bibliotecas disponibles.

---

# Ejercicio 2 - Analizando Java

### 1. ¿Tiene una sintaxis y una semántica bien definida? ¿Existe documentación oficial?

**Respuesta:** Sí, Java tiene una sintaxis y una semántica bien definidas. Su sintaxis es estricta pero relativamente simple, utilizando elementos como `;`, `{}` y la declaración de clases mediante estructuras como `public class Nombre {}`. Además, existe documentación oficial de Java donde se especifican sus características, clases, métodos y funcionamiento.

### 2. ¿Es posible comprobar el código producido en ese lenguaje?

**Respuesta:** Sí, es posible comprobar el código producido. El compilador de Java verifica diferentes aspectos del programa durante la compilación, como errores de sintaxis y determinados errores relacionados con los tipos. Sin embargo, no todos los errores pueden detectarse durante la compilación, ya que algunos ocurren durante la ejecución del programa.

### 3. ¿Es confiable?

**Respuesta:** Java puede considerarse un lenguaje confiable debido a varias de sus características. La gestión automática de memoria mediante el Garbage Collector reduce la posibilidad de errores relacionados con la liberación manual de memoria. Además, cuenta con mecanismos para manejar errores y excepciones mediante estructuras como `try-catch`, y posee un sistema de tipos que permite detectar determinados errores antes de ejecutar el programa.

### 4. ¿Es ortogonal?

**Respuesta:** Java no es completamente ortogonal, ya que existen algunas excepciones a las reglas generales del lenguaje. Por ejemplo, Java utiliza principalmente objetos, pero existen tipos primitivos como `int`, `double`, `char` y `boolean` que no son objetos. Para trabajar con estos valores como objetos existen sus correspondientes clases envolventes, como `Integer`, `Double`, `Character` y `Boolean`.

### 5. ¿Cuáles son sus características de consistencia y uniformidad?

**Respuesta:** Java presenta un alto nivel de consistencia porque la mayor parte de su estructura se organiza mediante clases, objetos, métodos y tipos bien definidos. Sin embargo, no es completamente uniforme debido a la existencia de tipos primitivos, que funcionan de manera diferente a los objetos. Esto genera algunas excepciones respecto de la idea general de que el lenguaje está orientado a objetos.

### 6. ¿Es extensible? ¿Hay subconjuntos de ese lenguaje?

**Respuesta:** Sí, Java es extensible mediante la creación de nuevas clases, métodos, bibliotecas y frameworks, permitiendo ampliar las funcionalidades del lenguaje sin modificar directamente su sintaxis o semántica. También existen diferentes plataformas y perfiles de Java orientados a distintos tipos de dispositivos y aplicaciones, como Java ME, que fue diseñado para dispositivos con recursos más limitados.

### 7. El código producido, ¿es transportable?

**Respuesta:** Sí, una de las principales características de Java es su portabilidad. El código fuente se compila normalmente a bytecode, que puede ejecutarse sobre una JVM compatible. Por esto, un programa compilado para Java puede ejecutarse en diferentes sistemas operativos, como Windows, Linux o macOS, sin necesidad de modificar el código fuente para cada uno de ellos.
