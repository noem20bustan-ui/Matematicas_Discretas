# 🧩 Unidad 1 — Lógica Matemática  

---

<details>
<summary><h2>📘 1. Definiciones Básicas de Lógica</h2></summary>

La **lógica** es la rama de las matemáticas y la filosofía que estudia los **métodos y principios del razonamiento válido**. Su propósito es determinar cuándo una conclusión se deduce correctamente de un conjunto de premisas.

---

### 📌 Conceptos Fundamentales

#### ✔️ Enunciado o Proposición  
Una **proposición** es una afirmación que puede ser **verdadera (V)** o **falsa (F)**, pero nunca ambas.

**Ejemplos:**
- "2 es un número par." → **V**
- "Quito es la capital de Perú." → **F**

**NO son proposiciones:**
- Preguntas: *¿Qué hora es?*  
- Órdenes: *Cierra la puerta.*  
- Expresiones ambiguas: *Hace frío.*  

</details>

---

<details>
<summary><h2>🔗 2. Proposiciones y Operadores Lógicos</h2></summary>

Los operadores lógicos permiten formar **proposiciones compuestas**.

---

### ✔️ 2.1 Negación (¬p)

Invierte el valor de verdad:  
- p verdadera → ¬p falsa  
- p falsa → ¬p verdadera  

---

### ✔️ 2.2 Conjunción (p ∧ q)

| p | q | p ∧ q |
|---|---|-------|
| V | V | **V** |
| V | F | F |
| F | V | F |
| F | F | F |

---

### ✔️ 2.3 Disyunción (p ∨ q)

| p | q | p ∨ q |
|---|---|-------|
| V | V | **V** |
| V | F | **V** |
| F | V | **V** |
| F | F | F |

---

### ✔️ 2.4 Implicación (p → q)

| p | q | p → q |
|---|---|--------|
| V | V | **V** |
| V | F | **F** |
| F | V | **V** |
| F | F | **V** |

---

### ✔️ 2.5 Doble Implicación (p ↔ q)

| p | q | p ↔ q |
|---|---|--------|
| V | V | **V** |
| V | F | F |
| F | V | F |
| F | F | **V** |

</details>

---

<details>
<summary><h2>📊 3. Tablas de Verdad</h2></summary>

Las **tablas de verdad** permiten analizar todas las combinaciones posibles de una proposición compuesta.

---

### ✔️ Ejemplo 1  
#### (p ∧ q) → ¬r

| p | q | r | p ∧ q | ¬r | (p ∧ q) → ¬r |
|---|---|---|-------|-----|----------------|
| V | V | V | V | F | F |
| V | V | F | V | V | **V** |
| V | F | V | F | F | **V** |
| V | F | F | F | V | **V** |
| F | V | V | F | F | **V** |
| F | V | F | F | V | **V** |
| F | F | V | F | F | **V** |
| F | F | F | F | V | **V** |

---

### ✔️ Ejemplo 2  
#### ¬p ∨ (q → p)

| p | q | ¬p | q → p | ¬p ∨ (q → p) |
|---|---|----|--------|----------------|
| V | V | F | V | **V** |
| V | F | F | V | **V** |
| F | V | V | F | **V** |
| F | F | V | V | **V** |

</details>

---

# 📂 📝 **Espacio para Tareas de la Unidad**

A continuación tienes una **tabla editable**, organizada, estética y perfecta para ir registrando tus deberes.

### 📋 **Registro de Tareas**

| Nº | Descripción del deber | Enlace al archivo | Estado |
|----|------------------------|-------------------|--------|
| 1 | Identificación de proposiciones | [Abrir archivo](link_aquí) | ✔️ Completado |
| 2 | Tabla de verdad de 3 proposiciones | [Abrir archivo](link_aquí) | ✔️ Completado |
| 3 | Operadores lógicos aplicados | *(Sin enlace)* | ⏳ Pendiente |
| 4 | Problemas de implicaciones | *(Sin enlace)* | ⏳ Pendiente |
| 5 | Ejercicios extra de práctica | *(Sin enlace)* | ⏳ Pendiente |


---

# 📝 **Conclusión de la Unidad**

En esta unidad se estudiaron los fundamentos del razonamiento lógico:

- Qué es una proposición  
- Cómo funcionan los conectores lógicos  
- Cómo se construyen y analizan tablas de verdad  

Estos conocimientos son esenciales para avanzar a temas como:  
**reglas de inferencia**, **equivalencias lógicas**, **álgebra booleana**, **grafos** y **algoritmos**.

---

> 📘 *Portafolio Académico — Matemáticas Discretas — Universidad Nacional de Loja*



