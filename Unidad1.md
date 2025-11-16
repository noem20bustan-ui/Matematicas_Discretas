# 🧩 Unidad 1 — Lógica Matemática

---

# 1. DEFINICIONES BÁSICAS DE LÓGICA

La **lógica** es la rama de las matemáticas y la filosofía que estudia los **métodos y principios del razonamiento válido**. Su objetivo es determinar cuándo una conclusión se deduce correctamente de un conjunto de premisas.

### 📌 Conceptos Fundamentales

### ✔️ **Enunciado o proposición**
Un **enunciado** o **proposición** es una oración que puede ser **verdadera (V)** o **falsa (F)**, pero no ambas al mismo tiempo.

Ejemplos:  
- "2 es un número par." → **V**  
- "Quito es la capital de Perú." → **F**

No son proposiciones:  
- Preguntas: "¿Qué hora es?"  
- Órdenes: "Cierra la puerta."  
- Expresiones ambiguas: "Hace frío."  

---

# 2. PROPOSICIONES Y OPERADORES LÓGICOS

Los operadores lógicos permiten formar **proposiciones compuestas**.

### ✔️ **1. Negación (¬p)**
Invierte el valor de verdad.  
- Si p es verdadera → ¬p es falsa  
- Si p es falsa → ¬p es verdadera

---

### ✔️ **2. Conjunción (p ∧ q)**
Es verdadera **solo si ambas** proposiciones son verdaderas.

| p | q | p ∧ q |
|---|---|-------|
| V | V | **V** |
| V | F | F |
| F | V | F |
| F | F | F |

---

### ✔️ **3. Disyunción (p ∨ q)**
Es verdadera cuando **al menos una** proposición es verdadera.

| p | q | p ∨ q |
|---|---|-------|
| V | V | **V** |
| V | F | **V** |
| F | V | **V** |
| F | F | F |

---

### ✔️ **4. Implicación (p → q)**
Solo es falsa cuando **p es verdadera** y **q es falsa**.

| p | q | p → q |
|---|---|--------|
| V | V | **V** |
| V | F | **F** |
| F | V | **V** |
| F | F | **V** |

---

### ✔️ **5. Doble implicación (p ↔ q)**
Es verdadera cuando **p y q tienen el mismo valor de verdad**.

| p | q | p ↔ q |
|---|---|--------|
| V | V | **V** |
| V | F | F |
| F | V | F |
| F | F | **V** |

---

# 3. TABLAS DE VERDAD

Las **tablas de verdad** muestran los valores posibles de una proposición compuesta evaluando todas las combinaciones de sus proposiciones simples.

---

## ✔️ Ejemplo 1:  
### Tabla de verdad de (p ∧ q) → ¬r

| p | q | r | p ∧ q | ¬r | (p ∧ q) → ¬r |
|---|---|---|-------|-----|----------------|
| V | V | V | V     | F   | F |
| V | V | F | V     | V   | **V** |
| V | F | V | F     | F   | **V** |
| V | F | F | F     | V   | **V** |
| F | V | V | F     | F   | **V** |
| F | V | F | F     | V   | **V** |
| F | F | V | F     | F   | **V** |
| F | F | F | F     | V   | **V** |

---

## ✔️ Ejemplo 2:
### Tabla de verdad de ¬p ∨ (q → p)

| p | q | ¬p | q → p | ¬p ∨ (q → p) |
|---|---|----|--------|----------------|
| V | V | F  | V      | **V** |
| V | F | F  | V      | **V** |
| F | V | V  | F      | **V** |
| F | F | V  | V      | **V** |

---

# 📝 Conclusión de la Unidad 1

En esta unidad se estudiaron los fundamentos del razonamiento lógico:  
- Qué es una proposición  
- Cómo operan los conectores lógicos  
- Cómo se construyen y leen las tablas de verdad  

Estos conceptos son esenciales para temas más avanzados como **reglas de inferencia, equivalencias lógicas, álgebra booleana, grafos y algoritmos**.

---

> 📌 *Este documento forma parte del Portafolio de Matemáticas Discretas — Universidad Nacional de Loja*

