# 🧩 Unidad 1 — Lógica Matemática

---

<details>
<summary><h2>📘 1. Definiciones Básicas de Lógica</h2></summary>

La **lógica** es la rama de las matemáticas y la filosofía que estudia los **métodos y principios del razonamiento válido**. Su propósito es determinar cuándo una conclusión se deduce correctamente de un conjunto de premisas.

Además, desde una perspectiva formal: la lógica es *“la ciencia que se encarga del estudio de los componentes, las formas y métodos del razonamiento válido… usada para diferenciar los razonamientos correctos de los incorrectos”*. Esta definición resalta que la lógica analiza la **estructura del pensamiento**, sin depender del significado de las proposiciones.

La **Lógica Matemática** se entiende como *“el estudio de la lógica con métodos matemáticos”*, lo cual permite representar razonamientos mediante símbolos, leyes y tablas que garantizan conclusiones válidas.

---

### 📌 Conceptos Fundamentales

#### ✔️ Enunciado o Proposición

Una **proposición** es una afirmación que puede ser **verdadera (V)** o **falsa (F)**, pero nunca ambas. También es descrita como *“una expresión lingüística, con un sentido aseverativo determinado, que es o verdadera o falsa”*. Para reconocer una proposición, debe cumplir:

* Ser una estructura lingüística.
* Tener sentido aseverativo.
* Tener valor de verdad definido.

**Ejemplos:**

* "2 es un número par." → **V**
* "Quito es la capital de Perú." → **F**

**NO son proposiciones:**

* Preguntas: *¿Qué hora es?*
* Órdenes: *Cierra la puerta.*
* Expresiones ambiguas: *Hace frío.*

</details>

---

<details>
<summary><h2>🔗 2. Proposiciones y Operadores Lógicos</h2></summary>

Las proposiciones se representan con letras como p, q, r y sirven de base para crear expresiones lógicas más complejas usando operadores lógicos. Cada operador define cómo se combinan los valores de verdad.

---

### ✔️ 2.1 Negación (¬p)

La negación es una operación unaria que invierte el valor de verdad:

* p verdadera → ¬p falsa
* p falsa → ¬p verdadera

Esta operación cumple: *(V) = F y (F) = V*.

---

### ✔️ 2.2 Conjunción (p ∧ q)

La conjunción expresa **“y”**. Es verdadera solo si ambas proposiciones lo son.

| p | q | p ∧ q |
| - | - | ----- |
| V | V | **V** |
| V | F | F     |
| F | V | F     |
| F | F | F     |

---

### ✔️ 2.3 Disyunción (p ∨ q)

La disyunción es un **or inclusivo**: es verdadera si al menos una de las proposiciones lo es.

| p | q | p ∨ q |
| - | - | ----- |
| V | V | **V** |
| V | F | **V** |
| F | V | **V** |
| F | F | F     |

---

### ✔️ 2.4 Implicación (p → q)

La implicación funciona como una **promesa lógica**: solo es falsa cuando p es verdadera y q es falsa.

| p | q | p → q |
| - | - | ----- |
| V | V | **V** |
| V | F | **F** |
| F | V | **V** |
| F | F | **V** |

---

### ✔️ 2.5 Doble Implicación (p ↔ q)

El bicondicional expresa equivalencia lógica: es verdadero si ambos tienen el mismo valor de verdad.

| p | q | p ↔ q |
| - | - | ----- |
| V | V | **V** |
| V | F | F     |
| F | V | F     |
| F | F | **V** |

</details>

---

<details>
<summary><h2>📊 3. Tablas de Verdad</h2></summary>

Las **tablas de verdad** permiten analizar sistemáticamente todas las combinaciones posibles del valor de verdad de una proposición compuesta.

Se definen como *“una aplicación veritativa que representa todas las posibles combinaciones del dominio y su correspondiente valor en {V, F}”*. Estas tablas permiten determinar si una proposición es tautología, contradicción o contingencia.

---

### ✔️ Ejemplo 1

#### (p ∧ q) → ¬r

| p | q | r | p ∧ q | ¬r | (p ∧ q) → ¬r |
| - | - | - | ----- | -- | ------------ |
| V | V | V | V     | F  | F            |
| V | V | F | V     | V  | **V**        |
| V | F | V | F     | F  | **V**        |
| V | F | F | F     | V  | **V**        |
| F | V | V | F     | F  | **V**        |
| F | V | F | F     | V  | **V**        |
| F | F | V | F     | F  | **V**        |
| F | F | F | F     | V  | **V**        |

---

### ✔️ Ejemplo 2

#### ¬p ∨ (q → p)

| p | q | ¬p | q → p | ¬p ∨ (q → p) |
| - | - | -- | ----- | ------------ |
| V | V | F  | V     | **V**        |
| V | F | F  | V     | **V**        |
| F | V | V  | F     | **V**        |
| F | F | V  | V     | **V**        |

</details>

---

# 📂 Tareas de la Unidad
| Apartado | Descripción (sin cambios) | Enlace al deber |
|----------|----------------------------|------------------|
| **📘 ACD1: LÓGICA PROPOSICIONAL, CONECTORES Y TABLAS DE VERDAD** | <details><summary>Mostrar descripción</summary><br>ACD1: LOGICA PROPOCICIONAL, CONECTORES Y TABLAS DE VERDAD: El documento corresponde a una presentación elaborada por el grupo PseInt con el propósito de introducir los conceptos fundamentales de la lógica proposicional. El contenido se organiza en diapositivas que explican de manera clara y progresiva los temas principales. En las primeras secciones se expone la definición general de lógica, destacando que su objetivo es analizar la validez de los razonamientos a partir de su estructura. Posteriormente, se presenta la distinción entre proposiciones y no proposiciones, junto con la manera en que se representan simbólicamente mediante letras como p, q y r. El documento continúa con una explicación detallada de los conectores lógicos, entre ellos la negación, la conjunción, la disyunción, el condicional y el bicondicional. Cada conector incluye su significado, su regla de verdad y un ejemplo aplicado, lo cual facilita la comprensión del lector. Asimismo, se aborda la construcción de tablas de verdad y la clasificación de las proposiciones compuestas en tautologías, contradicciones y contingencias. Finalmente, la presentación establece una relación entre la lógica y su aplicación en lenguajes de programación, mostrando los equivalentes de los conectores lógicos en distintos entornos computacionales. En conjunto, el documento ofrece una exposición ordenada y didáctica que permite comprender los principios esenciales de la lógica proposicional.</details> | XDD |
| **📙 ACD2: implicaciones, equivalencias y razonamiento deductivo (leyes proposicionales y reglas de inferencia)** | <details><summary>Mostrar descripción</summary><br>ACD2: implicaciones, equivalencias y razonamiento deductivo (leyes proposicionales y reglas de inferencia)) Descripción de la sección Este documento presenta una síntesis de las principales leyes de las proposiciones y de las reglas de inferencia utilizadas en lógica proposicional. Su estructura es clara y está acompañada de ejemplos y representaciones simbólicas que facilitan el aprendizaje. En la primera parte se explican diversas leyes lógicas, entre ellas la doble negación, la idempotencia, las leyes conmutativa y asociativa, la distributiva, las leyes de De Morgan, la ley condicional y la ley bicondicional. Cada una se acompaña de una breve descripción y un ejemplo que ilustra cómo se aplica en la simplificación de expresiones lógicas. En la segunda sección se desarrollan las reglas de inferencia, como Modus Ponens, Modus Tollens, Silogismo Hipotético, Adición, Simplificación y la Ley de la Unión. Cada regla se presenta con un ejemplo que muestra cómo se utiliza para obtener conclusiones válidas a partir de premisas verdaderas. El documento cumple una función de guía académica, ofreciendo un resumen estructurado y accesible para el estudio de las transformaciones lógicas y de los métodos formales de inferencia.</details> | [Ver PDF](trabajosUnidad1/Leyes-Logicas-y-Reglas-de-Inferencia%20%281%29-comprimido%20%282%29%20%283%29.pdf) |
| **📗 AA: LECTURA Y EJERCICIOS** | <details><summary>Mostrar descripción</summary><br>AA. LECTURA Y EJERCICIOS Este documento corresponde a una tarea de la asignatura Matemáticas Discretas, elaborada por los integrantes del grupo PseInt. El trabajo está compuesto por dos ejercicios orientados a la aplicación de leyes lógicas y reglas de inferencia. Ejercicio 1 El primer ejercicio presenta una demostración lógica manuscrita. En la parte superior se encuentran varias premisas expresadas mediante conectores proposicionales como la negación, la disyunción, la conjunción y el condicional. A partir de estas, se desarrolla una secuencia de pasos numerados, cada uno de los cuales aplica una ley o regla de inferencia específica, como las leyes de De Morgan, el Modus Tollendo Ponens o la doble negación. El procedimiento está organizado de forma ordenada, indicando en cada línea la referencia a pasos o premisas previos. Al final del ejercicio, se llega a la conclusión S, marcando así la validez del razonamiento construido. Ejercicio 2 El segundo ejercicio consiste en analizar un argumento expresado en lenguaje natural y traducirlo a proposiciones lógicas. A partir de las premisas descritas en el enunciado, se debe deducir la conclusión final: “los ingenieros han cometido un error”. El desarrollo del ejercicio requiere identificar correctamente las premisas y aplicar reglas de inferencia para justificar la conclusión.</details> | [Ver PDF](trabajosUnidad1/matematicasTarea%20%281%29.pdf)|
| **📕 APE: RESOLUCIÓN DE EJERCICIOS** | <details><summary>Mostrar descripción</summary><br>APE: RESOLUCION DE EJERCICIOS Este documento es un material académico elaborado como práctica de la asignatura de Matemáticas Discretas por el grupo PSeInt de la Universidad Nacional de Loja. Su contenido reúne varios ejercicios destinados a reforzar los conceptos fundamentales de la lógica proposicional, organizados de manera progresiva. En la primera sección se presentan definiciones básicas, como proposición, tabla de verdad y los principales conectores lógicos. Estas nociones se acompañan de ejemplos breves que facilitan su comprensión. Luego, el documento incluye ejercicios para identificar si determinadas oraciones pueden considerarse proposiciones y, en caso afirmativo, elaborar su negación. Se analizan enunciados matemáticos, informativos y cotidianos, así como preguntas y órdenes que se clasifican correctamente como no proposiciones. Posteriormente, se desarrollan tablas de verdad de varias expresiones compuestas. A partir de los resultados, se clasifican las fórmulas como tautologías, contradicciones o contingencias. También se resuelven ejercicios en los que se evalúan proposiciones suponiendo valores determinados para p, q y r. Finalmente, el documento contiene actividades de traducción entre lenguaje natural y simbólico. Estas tareas consisten en expresar oraciones comunes mediante conectores lógicos o interpretar proposiciones simbólicas en lenguaje cotidiano. En conjunto, el documento ofrece una práctica completa que combina teoría y aplicación, permitiendo fortalecer el manejo de la lógica proposicional.</details> | [Ver PDF](trabajosUnidad1/APE1%20Resolucion%20de%20ejercicios%20relacionados%20a%20tablas%20de%20verdad%20y%20logica.pdf) |



## 💭 Reflexión de la Unidad 1

Durante esta unidad comprendí que el estudio de la **lógica proposicional** es, ante todo, aprender a **razonar de manera estructurada y coherente**. Las **proposiciones** y los **conectores lógicos** permiten expresar ideas de forma precisa, evitando ambigüedades y facilitando el análisis formal de cualquier argumento.  

Además, **elaborar tablas de verdad** se convirtió en una herramienta fundamental para verificar el comportamiento de las proposiciones compuestas y determinar si una expresión es **válida**, **contradictoria** o **contingente**.

Siento que trabajé bien al identificar los valores de verdad de cada proposición y entender cómo se combinan mediante los diferentes conectores.  
Sin embargo, aún debo mejorar mi **rapidez** y **seguridad** al construir tablas de verdad más extensas, especialmente cuando involucran varios operadores.


---

> 📘 *Portafolio Académico — Matemáticas Discretas — Universidad Nacional de Loja*




