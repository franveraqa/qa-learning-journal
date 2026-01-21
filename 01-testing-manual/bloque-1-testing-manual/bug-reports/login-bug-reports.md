# Bug Reports — Funcionalidad Login

Este documento contiene los **bugs detectados durante la ejecución de los casos de prueba de la funcionalidad de login**.

Los bugs están documentados de forma clara y reproducible, siguiendo buenas prácticas de QA Manual.

---

## BUG-LOGIN-01 — El botón de login no responde

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos para reproducir:**
1. Introducir un nombre de usuario válido
2. Introducir una contraseña válida
3. Pulsar el botón de login

**Resultado esperado:**  
El sistema autentica al usuario y lo redirige a la página principal.

**Resultado real:**  
Al pulsar el botón de login no ocurre ninguna acción.

**Severidad:** Alta  
**Prioridad:** Alta

---

## BUG-LOGIN-02 — Mensaje de error incorrecto con credenciales inválidas

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos para reproducir:**
1. Introducir un nombre de usuario válido
2. Introducir una contraseña incorrecta
3. Pulsar el botón de login

**Resultado esperado:**  
El sistema muestra un mensaje indicando que las credenciales son incorrectas.

**Resultado real:**  
El sistema muestra un mensaje genérico que no informa correctamente del error.

**Severidad:** Media  
**Prioridad:** Media

---

## BUG-LOGIN-03 — No se muestra validación al enviar campos vacíos

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos para reproducir:**
1. Dejar los campos de usuario y contraseña vacíos
2. Pulsar el botón de login

**Resultado esperado:**  
El sistema bloquea el acceso y muestra un mensaje indicando que los campos son obligatorios.

**Resultado real:**  
El sistema no muestra ningún mensaje de error y permanece en la misma pantalla.

**Severidad:** Media  
**Prioridad:** Alta

---

## BUG-LOGIN-04 — El campo contraseña permite caracteres no visibles

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos para reproducir:**
1. Introducir espacios en blanco como contraseña
2. Introducir un nombre de usuario válido
3. Pulsar el botón de login

**Resultado esperado:**  
El sistema valida la contraseña y muestra un mensaje de error.

**Resultado real:**  
El sistema permite enviar el formulario sin mostrar ninguna validación.

**Severidad:** Media  
**Prioridad:** Media

---

## BUG-LOGIN-05 — No se muestra mensaje tras múltiples intentos fallidos

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos para reproducir:**
1. Introducir credenciales incorrectas repetidas veces
2. Pulsar el botón de login en cada intento

**Resultado esperado:**  
El sistema muestra un mensaje informando del bloqueo o del número de intentos fallidos.

**Resultado real:**  
El sistema permite intentos ilimitados sin mostrar ninguna advertencia.

**Severidad:** Media  
**Prioridad:** Baja

---

## 📌 Notas
- Todos los bugs provienen de la ejecución de casos de prueba
- La severidad refleja el impacto técnico
- La prioridad refleja la urgencia de corrección
- QA documenta los bugs, no los soluciona
