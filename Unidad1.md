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

## Tabla Resumen de Documentos – Portafolio Matemáticas Discretas

| **Documento** | **Tema Principal** | **Contenido Resumido** | **Enfoque / Aportes** |
|---------------|--------------------|--------------------------|-------------------------|
| **ACD1: Lógica proposicional, conectores y tablas de verdad** | Fundamentos de lógica proposicional | • Definición de lógica y análisis de validez de razonamientos. <br>• Proposiciones vs. no proposiciones y su representación simbólica (p, q, r). <br>• Conectores lógicos: negación, conjunción, disyunción, condicional, bicondicional. <br>• Construcción de tablas de verdad. <br>• Clasificación: tautologías, contradicciones, contingencias. <br>• Relación entre lógica y programación. | Documento introductorio, ordenado y didáctico. Presenta conceptos base con ejemplos y tablas de verdad. Útil para comprender la estructura de razonamientos y su aplicación en computación. |
| **ACD2: Implicaciones, equivalencias y razonamiento deductivo** | Leyes lógicas y reglas de inferencia | • Leyes proposicionales: doble negación, idempotencia, conmutativa, asociativa, distributiva, De Morgan, condicional y bicondicional. <br>• Reglas de inferencia: Modus Ponens, Modus Tollens, Silogismo Hipotético, Adición, Simplificación, Ley de la Unión. <br>• Ejemplos simbólicos y prácticos. | Guía académica sintética y clara. Permite comprender cómo se transforman expresiones lógicas y cómo se obtienen conclusiones válidas mediante reglas formales. |
| **AA: Lectura y ejercicios** | Aplicación de leyes lógicas e inferencia | **Ejercicio 1:** <br>• Demostración lógica paso a paso usando premisas y reglas (De Morgan, Modus Tollendo Ponens, doble negación, etc.). <br>• Conclusión final: S. <br><br> **Ejercicio 2:** <br>• Traducción de argumentos del lenguaje natural a proposiciones. <br>• Deducción de la conclusión “los ingenieros han cometido un error”. | Fortalece la capacidad de aplicar reglas de inferencia en situaciones formales y cotidianas. Enfatiza el razonamiento estructurado y la justificación de cada paso. |
| **APE: Resolución de ejercicios** | Práctica general de lógica proposicional | • Definiciones básicas: proposición, conectores y tablas de verdad. <br>• Clasificación de oraciones como proposiciones o no proposiciones. <br>• Elaboración de negaciones. <br>• Tablas de verdad y clasificación en tautologías, contradicciones o contingencias. <br>• Evaluación de proposiciones con valores dados. <br>• Traducción entre lenguaje natural y simbólico. | Material práctico completo que refuerza teoría y desarrolla habilidades de análisis, interpretación y simbolización lógica. |



## 💭 Reflexión de la Unidad 1

Durante esta unidad comprendí que el estudio de la **lógica proposicional** es, ante todo, aprender a **razonar de manera estructurada y coherente**. Las **proposiciones** y los **conectores lógicos** permiten expresar ideas de forma precisa, evitando ambigüedades y facilitando el análisis formal de cualquier argumento.  

Además, **elaborar tablas de verdad** se convirtió en una herramienta fundamental para verificar el comportamiento de las proposiciones compuestas y determinar si una expresión es **válida**, **contradictoria** o **contingente**.

Siento que trabajé bien al identificar los valores de verdad de cada proposición y entender cómo se combinan mediante los diferentes conectores.  
Sin embargo, aún debo mejorar mi **rapidez** y **seguridad** al construir tablas de verdad más extensas, especialmente cuando involucran varios operadores.


---

> 📘 *Portafolio Académico — Matemáticas Discretas — Universidad Nacional de Loja*




