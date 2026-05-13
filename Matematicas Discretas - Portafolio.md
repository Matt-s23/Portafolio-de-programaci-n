<div align="center">

# 📚 PORTAFOLIO DE MATEMÁTICAS DISCRETAS

### Universidad Nacional de Loja

![Banner](https://univercimas.com/wp-content/uploads/2021/04/Universidad-Nacional-de-Loja-UNL.png)

<br>

<img src="https://img.shields.io/badge/MATEMÁTICAS-DISCRETAS-0d6efd?style=for-the-badge&labelColor=0b1120" />
<img src="https://img.shields.io/badge/GITHUB-PORTAFOLIO-181717?style=for-the-badge&logo=github" />
<img src="https://img.shields.io/badge/UNIDAD-1_ACTIVA-success?style=for-the-badge" />

---

## 👨‍🎓 Información Académica

| Campo | Información |
|:---|:---|
| 👤 Estudiante | **Matias Santiago Calva Gonzalez** |
| 👨‍🏫 Docente | **Ing. Mario Enrique Cueva** |
| 💻 Carrera | **Computación** |
| 📘 Asignatura | **Matemáticas Discretas** |
| 🎓 Ciclo | **Primer Ciclo** |
| 📅 Año Lectivo | **2026** |

---

> ✨ *"La lógica es la base del razonamiento computacional."*

</div>

---

# 📑 ÍNDICE GENERAL

<details open>
<summary><b>📘 Navegación del Portafolio</b></summary>

<br>

## 🟢 Unidad 1 — Lógica Proposicional

### 📖 Contenido Teórico
- [1.1 ¿Qué es una proposición?](#11--qué-es-una-proposición)
- [1.2 Tipos de proposiciones](#12--tipos-de-proposiciones)
- [1.3 Conectores lógicos](#13--conectores-lógicos)
- [1.4 Tablas de verdad](#14--tablas-de-verdad)
- [1.5 Leyes proposicionales](#15--leyes-proposicionales)
- [1.6 Reglas de inferencia](#16--reglas-de-inferencia)

### 📊 Ejercicios Resueltos
- [Ejercicio 1 — Traducción simbólica](#ejercicio-1--traducción-de-lenguaje-natural-a-simbólico)
- [Ejercicio 2 — Tabla de verdad](#ejercicio-2--construcción-de-tabla-de-verdad)
- [Ejercicio 3 — Tautología](#ejercicio-3--identificación-de-tautología)
- [Ejercicio 4 — Contradicción](#ejercicio-4--identificación-de-contradicción)
- [Ejercicio 5 — Leyes proposicionales](#ejercicio-5--aplicación-de-leyes-proposicionales)
- [Ejercicio 6 — Validación de argumento](#ejercicio-6--validación-de-argumento)

### 🧠 Ejercicio Aplicado
- [Caso real o cotidiano](#-ejercicio-aplicado)

### 🔍 Reflexión Personal
- [¿Qué fue lo más difícil de entender?](#qué-fue-lo-más-difícil-de-entender)
- [¿Qué tema comprendí mejor?](#qué-tema-comprendí-mejor)
- [¿Cómo puedo aplicar la lógica en mi carrera?](#cómo-puedo-aplicar-la-lógica-en-mi-carrera)

### 🔒 Otras Unidades
- [Unidad 2 — No habilitado](#-unidad-2--no-habilitado)
- [Unidad 3 — No habilitado](#-unidad-3--no-habilitado)

</details>

---

# 🟢 UNIDAD 1 — LÓGICA PROPOSICIONAL

## 📌 Introducción

La lógica proposicional es una de las bases fundamentales de las matemáticas discretas y del razonamiento computacional. Permite representar información mediante símbolos y analizar si un razonamiento es válido o incorrecto.

Actualmente se aplica en áreas como:

- 💻 Desarrollo de software
- 🤖 Inteligencia artificial
- 🔐 Seguridad informática
- 🌐 Redes computacionales
- 🗄️ Bases de datos
- ⚙️ Electrónica digital

---

## 📖 1.1 — ¿Qué es una proposición?

Una **proposición** es un enunciado declarativo que puede clasificarse como **verdadero** o **falso**, nunca ambos a la vez.

### ✅ Ejemplos de proposiciones

| Enunciado | Valor |
|---|---|
| 7 es un número primo | Verdadero |
| 2 + 2 = 5 | Falso |
| Python es un sistema operativo | Falso |

### ❌ Expresiones que NO son proposiciones

| Expresión | Motivo |
|---|---|
| ¿Cómo estás? | Pregunta |
| Guarda el archivo | Orden |
| Ojalá funcione | Deseo |

### 📌 Idea clave

> Toda proposición debe poseer un valor de verdad definido.

Las proposiciones son la base de algoritmos, programación lógica, estructuras condicionales y sistemas computacionales.

---

## 📖 1.2 — Tipos de proposiciones

Las proposiciones pueden clasificarse en **simples** y **compuestas**.

### 🔹 Proposiciones simples

No contienen conectores lógicos. Son la unidad mínima de análisis.

Ejemplos:
- `p` : El servidor está activo
- `q` : El usuario inició sesión

### 🔹 Proposiciones compuestas

Se forman combinando proposiciones simples mediante conectores lógicos.

Ejemplos:
- `p ∧ q`
- `p → q`
- `¬p`

### 📊 Comparación

| Tipo | Característica |
|---|---|
| Simples | No pueden dividirse en partes más pequeñas |
| Compuestas | Contienen uno o más conectores lógicos |

### 💻 Relación con informática

Las condiciones en programación funcionan mediante lógica proposicional:

```cpp
if (usuario && contraseña) {
    // acceso permitido
}
```

---

## 📖 1.3 — Conectores lógicos

Los **conectores lógicos** permiten relacionar proposiciones para formar expresiones compuestas.

### 📊 Tabla de conectores

| Símbolo | Nombre | Lectura | Descripción |
|---|---|---|---|
| `¬` | Negación | "No" | Invierte el valor de verdad |
| `∧` | Conjunción | "Y" | Verdadero solo si ambas son verdaderas |
| `∨` | Disyunción | "O" | Falso solo si ambas son falsas |
| `→` | Condicional | "Si... entonces" | Falso solo cuando el antecedente es V y el consecuente F |
| `↔` | Bicondicional | "Si y solo si" | Verdadero cuando ambas tienen el mismo valor |

### 💻 Equivalencia en programación

| Lógica | Programación |
|---|---|
| `¬p` | `!p` |
| `p ∧ q` | `p && q` |
| `p ∨ q` | `p \|\| q` |

Los conectores lógicos son fundamentales en validaciones, algoritmos, circuitos digitales e inteligencia artificial.

---

## 📖 1.4 — Tablas de verdad

Las **tablas de verdad** permiten analizar todas las combinaciones posibles de valores de una expresión lógica. Con `n` variables, se generan `2ⁿ` filas.

### ⚙️ Procedimiento general

| Paso | Descripción |
|---|---|
| 1 | Identificar las variables |
| 2 | Calcular el número de filas con `2ⁿ` |
| 3 | Construir las columnas de izquierda a derecha |
| 4 | Resolver operadores de menor a mayor precedencia |
| 5 | Obtener el resultado final |

### 📊 Tabla básica para p y q

| p | q | ¬p | p ∧ q | p ∨ q | p → q | p ↔ q |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| V | V | F | V | V | V | V |
| V | F | F | F | V | F | F |
| F | V | V | F | V | V | F |
| F | F | V | F | F | V | V |

### 🎯 Clasificación de expresiones

| Tipo | Resultado | Ejemplo |
|---|---|---|
| 🟢 **Tautología** | Siempre verdadero | `p ∨ ¬p` |
| 🔴 **Contradicción** | Siempre falso | `p ∧ ¬p` |
| 🟡 **Contingencia** | Valores mixtos | `p → q` |

---

## 📖 1.5 — Leyes proposicionales

Las **leyes proposicionales** permiten simplificar o transformar expresiones lógicas sin alterar su significado (equivalencia lógica `≡`).

### 📊 Leyes principales

| Ley | Equivalencia |
|---|---|
| Doble negación | `¬(¬p) ≡ p` |
| De Morgan (conjunción) | `¬(p ∧ q) ≡ ¬p ∨ ¬q` |
| De Morgan (disyunción) | `¬(p ∨ q) ≡ ¬p ∧ ¬q` |
| Implicación material | `p → q ≡ ¬p ∨ q` |
| Conmutativa (∧) | `p ∧ q ≡ q ∧ p` |
| Conmutativa (∨) | `p ∨ q ≡ q ∨ p` |
| Absorción | `p ∧ (p ∨ q) ≡ p` |
| Identidad | `p ∧ V ≡ p` |

### 💻 Aplicación informática

La ley de De Morgan es muy usada en programación para simplificar condiciones:

```txt
!(A && B)   equivale a   !A || !B
!(A || B)   equivale a   !A && !B
```

Estas leyes permiten simplificar condiciones, optimizar código y mejorar algoritmos.

---

## 📖 1.6 — Reglas de inferencia

Las **reglas de inferencia** permiten obtener conclusiones válidas a partir de premisas conocidas.

### 🔹 Modus Ponens

```
Premisa 1:  p → q
Premisa 2:  p
            ─────
Conclusión: ∴ q
```

### 🔹 Modus Tollens

```
Premisa 1:  p → q
Premisa 2:  ¬q
            ─────
Conclusión: ∴ ¬p
```

### 🔹 Silogismo Hipotético

```
Premisa 1:  p → q
Premisa 2:  q → r
            ─────
Conclusión: ∴ p → r
```

### 🔹 Adición

```
Premisa:    p
            ─────
Conclusión: ∴ p ∨ q
```

### 🔹 Simplificación

```
Premisa:    p ∧ q
            ─────
Conclusión: ∴ p
```

Estas reglas se utilizan en sistemas expertos, razonamiento computacional, inteligencia artificial y validaciones lógicas.

---

# 📊 EJERCICIOS RESUELTOS

---

## 📌 Ejercicio 1 — Traducción de lenguaje natural a simbólico

<details open>
<summary><b>Ver ejercicio</b></summary>

<br>

### 📷 Evidencia

> ⬇️ *Pegar aquí la imagen del ejercicio resuelto*

```
[Ejercicio 1 — pendiente de imagen]
```

<!-- Cuando tengas la imagen, reemplaza el bloque anterior con:
<img src="ejercicio1.png" width="850">
-->

---

### Enunciado

> Si el sistema detecta un error **y** el usuario está conectado, **entonces** se envía una alerta.

### Variables

| Variable | Significado |
|---|---|
| `p` | El sistema detecta un error |
| `q` | El usuario está conectado |
| `r` | Se envía una alerta |

### Expresión lógica

```
(p ∧ q) → r
```

</details>

---

## 📌 Ejercicio 2 — Construcción de tabla de verdad

<details>
<summary><b>Ver ejercicio</b></summary>

<br>

### 📷 Evidencia

> ⬇️ *Pegar aquí la imagen del ejercicio resuelto*

```
[Ejercicio 2 — pendiente de imagen]
```

<!-- Cuando tengas la imagen, reemplaza el bloque anterior con:
<img src="ejercicio2.png" width="850">
-->

---

### Expresión

```
(p → q) ∧ (¬p ∨ r)
```

### Tabla de verdad

| p | q | r | p → q | ¬p | ¬p ∨ r | (p → q) ∧ (¬p ∨ r) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| V | V | V | V | F | V | V |
| V | V | F | V | F | F | F |
| V | F | V | F | F | V | F |
| V | F | F | F | F | F | F |
| F | V | V | V | V | V | V |
| F | V | F | V | V | V | V |
| F | F | V | V | V | V | V |
| F | F | F | V | V | V | V |

### Clasificación

🟡 **Contingencia** — la expresión no es siempre verdadera ni siempre falsa.

</details>

---

## 📌 Ejercicio 3 — Identificación de tautología

<details>
<summary><b>Ver ejercicio</b></summary>

<br>

### 📷 Evidencia

> ⬇️ *Pegar aquí la imagen del ejercicio resuelto*

```
[Ejercicio 3 — pendiente de imagen]
```

<!-- Cuando tengas la imagen, reemplaza el bloque anterior con:
<img src="ejercicio3.png" width="850">
-->

---

### Expresión

```
p ∨ ¬p
```

### Tabla de verdad

| p | ¬p | p ∨ ¬p |
|:---:|:---:|:---:|
| V | F | **V** |
| F | V | **V** |

### Clasificación

🟢 **Tautología** — la expresión es **siempre verdadera** independientemente del valor de `p`.

</details>

---

## 📌 Ejercicio 4 — Identificación de contradicción

<details>
<summary><b>Ver ejercicio</b></summary>

<br>

### 📷 Evidencia

> ⬇️ *Pegar aquí la imagen del ejercicio resuelto*

```
[Ejercicio 4 — pendiente de imagen]
```

<!-- Cuando tengas la imagen, reemplaza el bloque anterior con:
<img src="ejercicio4.png" width="850">
-->

---

### Expresión

```
p ∧ ¬p
```

### Tabla de verdad

| p | ¬p | p ∧ ¬p |
|:---:|:---:|:---:|
| V | F | **F** |
| F | V | **F** |

### Clasificación

🔴 **Contradicción** — la expresión es **siempre falsa** independientemente del valor de `p`.

</details>

---

## 📌 Ejercicio 5 — Aplicación de leyes proposicionales

<details>
<summary><b>Ver ejercicio</b></summary>

<br>

### 📷 Evidencia

> ⬇️ *Pegar aquí la imagen del ejercicio resuelto*

```
[Ejercicio 5 — pendiente de imagen]
```

<!-- Cuando tengas la imagen, reemplaza el bloque anterior con:
<img src="ejercicio5.png" width="850">
-->

---

### Simplificar la expresión

```
¬(p ∧ q)
```

### Procedimiento paso a paso

| Paso | Expresión | Ley aplicada |
|---|---|---|
| 1 | `¬(p ∧ q)` | Expresión original |
| 2 | `¬p ∨ ¬q` | **Ley de De Morgan** |

### Resultado

```
¬(p ∧ q)  ≡  ¬p ∨ ¬q
```

### Verificación en programación

```txt
!(A && B)   equivale a   !A || !B
```

</details>

---

## 📌 Ejercicio 6 — Validación de argumento

<details>
<summary><b>Ver ejercicio</b></summary>

<br>

### 📷 Evidencia

> ⬇️ *Pegar aquí la imagen del ejercicio resuelto*

```
[Ejercicio 6 — pendiente de imagen]
```

<!-- Cuando tengas la imagen, reemplaza el bloque anterior con:
<img src="ejercicio6.png" width="850">
-->

---

### Premisas

```
Premisa 1:  p → q
Premisa 2:  q → r
Premisa 3:  p
```

### Procedimiento

| Paso | Operación | Regla aplicada |
|---|---|---|
| 1 | De `p → q` y `q → r` se obtiene `p → r` | Silogismo Hipotético |
| 2 | De `p → r` y `p` se obtiene `r` | Modus Ponens |

### Conclusión

```
∴ r
```

### Resultado

✅ **El argumento es válido** — la conclusión se deriva correctamente de las premisas.

</details>

---

# 🧠 EJERCICIO APLICADO

<details open>
<summary><b>📌 Caso real: Sistema de acceso universitario</b></summary>

<br>

## 📖 Problema planteado

Una plataforma virtual universitaria permite el acceso a un examen **únicamente si**:

- el estudiante ha **iniciado sesión**, **y**
- el estudiante posee **matrícula activa**.

Si alguna condición no se cumple, el sistema bloqueará el acceso automáticamente.

---

## 🔹 Definición de proposiciones

| Variable | Significado |
|---|---|
| `p` | El estudiante inició sesión |
| `q` | El estudiante tiene matrícula activa |
| `r` | El estudiante puede acceder al examen |

---

## 🔹 Expresión simbólica

```
(p ∧ q) → r
```

---

## 🔹 Análisis lógico

La proposición establece que el acceso al examen solo será posible cuando **ambas condiciones sean verdaderas simultáneamente**.

### 📊 Tabla de casos posibles

| p | q | p ∧ q | Resultado (r) |
|:---:|:---:|:---:|:---|
| V | V | V | ✅ Puede acceder al examen |
| V | F | F | ❌ No puede acceder (sin matrícula) |
| F | V | F | ❌ No puede acceder (sin sesión) |
| F | F | F | ❌ No puede acceder |

---

## 🔹 Código equivalente

```python
if usuario_con_sesion and matricula_activa:
    permitir_acceso_examen()
else:
    bloquear_acceso()
```

---

## 🔹 Conclusión

La lógica proposicional permite representar situaciones reales de manera precisa. En este caso, modelamos exactamente cómo un sistema informático toma decisiones mediante condiciones lógicas combinadas, lo que es la base de cualquier sistema de autenticación y autorización en software.

</details>

---

# 🔍 REFLEXIÓN PERSONAL

---

<details open>
<summary><b>📌 ¿Qué fue lo más difícil de entender?</b></summary>

<br>

Lo más difícil fue comprender correctamente el desarrollo de **tablas de verdad** con múltiples conectores lógicos simultáneos. Al principio era fácil confundirse con el orden de precedencia de los operadores y equivocarse en los valores de verdad de expresiones complejas como `(p → q) ∧ (¬p ∨ r)`.

</details>

---

<details>
<summary><b>📌 ¿Qué tema comprendí mejor?</b></summary>

<br>

El tema que comprendí mejor fueron las **leyes proposicionales** y las **reglas de inferencia**, debido a su relación directa con la programación. Al ver que `¬(p ∧ q) ≡ ¬p ∨ ¬q` corresponde exactamente a `!(A && B) == !A || !B` en código, el concepto se volvió muy intuitivo.

</details>

---

<details>
<summary><b>📌 ¿Cómo puedo aplicar la lógica en mi carrera?</b></summary>

<br>

La lógica proposicional tiene aplicaciones directas en mi carrera de Computación:

- **Desarrollo de software**: estructuras condicionales y validaciones
- **Algoritmos**: análisis de condiciones y toma de decisiones
- **Bases de datos**: consultas con condiciones lógicas (`AND`, `OR`, `NOT`)
- **Inteligencia artificial**: sistemas expertos y razonamiento automático
- **Ciberseguridad**: sistemas de control de acceso y autenticación

</details>

---

# 🔒 UNIDAD 2 — NO HABILITADO

<div align="center">

## ⚠️ Contenido aún no disponible

</div>

---

# 🔒 UNIDAD 3 — NO HABILITADO

<div align="center">

## ⚠️ Contenido aún no disponible

</div>

---

# 🎯 CONCLUSIÓN GENERAL

La lógica proposicional constituye una herramienta fundamental para el razonamiento formal y el desarrollo computacional. Gracias a ella es posible analizar situaciones complejas, validar argumentos y desarrollar sistemas eficientes y seguros. Su estudio es indispensable para cualquier profesional del área de la computación.

---

<div align="center">

# 🎓 Universidad Nacional de Loja

### Matemáticas Discretas · Portafolio Académico · 2026

<img src="https://img.shields.io/badge/PORTAFOLIO-COMPLETADO-success?style=for-the-badge" />

<br>

⭐ Elaborado en GitHub Markdown &nbsp;·&nbsp; 💻 Diseño académico interactivo

</div>

