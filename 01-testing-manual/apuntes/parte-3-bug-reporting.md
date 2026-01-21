# Parte 3 — Bug Reporting Profesional

## ¿Qué es un bug?

Un **bug** es un comportamiento del sistema que **no coincide con el resultado esperado**.

Aparece cuando:
- Se ejecuta un caso de prueba
- El resultado real es distinto al esperado

---

## 🧠 Mentalidad QA al reportar bugs

Todo bug se documenta:

- Aunque sea pequeño
- Aunque ya lo hayan visto
- Aunque parezca obvio

👉 QA **no arregla errores**, los reporta.

---

## 🧱 Estructura básica de un Bug Report

Un bug report profesional contiene:

- ID
- Título
- Precondición
- Pasos para reproducir
- Resultado esperado
- Resultado real

⚠️ Si falta una parte, el bug está mal reportado.

👉 Un bug está bien reportado si otra persona puede reproducirlo solo leyendo el reporte.

---

## 🔁 Relación entre Test Case y Bug

- El **test case** define lo que debería pasar
- El **bug** se reporta cuando el test case falla
- Un bug **siempre nace de un test case**

---

## 🧠 Severidad (Severity)

Indica **qué tan grave es el bug a nivel técnico**.

👉 ¿Cuánto impacto tiene este bug en el sistema?

- Alta (High / Critical)
- Media (Medium)
- Baja (Low)

---

## 🧠 Prioridad (Priority)

Indica **qué tan urgente es arreglar el bug**.

👉 ¿Con qué urgencia debe arreglarse?

- Alta
- Media
- Baja

---

## 🔁 Diferencia clave

- **Severidad** = impacto técnico  
- **Prioridad** = urgencia de arreglo  

👉 No son lo mismo y no siempre coinciden.

---

## 🧪 Ejemplos

- Botón de login no responde → Severidad Alta / Prioridad Alta  
- Error ortográfico → Severidad Baja / Prioridad Baja  
- Login lento → Severidad Media / Prioridad Media o Alta  

📌 La severidad la evalúa QA.  
📌 La prioridad se decide con el equipo o negocio.
