# Bug Reports — Registro de Usuario

---

## BUG-REG-01 — Permite registrar usuario sin email

**Precondición:**  
Usuario en la página de registro.

**Pasos para reproducir:**
1. Dejar el campo email vacío
2. Completar el resto de campos
3. Pulsar registrar

**Resultado esperado:**  
El sistema bloquea el registro y muestra un mensaje de error.

**Resultado real:**  
El sistema permite continuar con el registro.

**Severidad:** Alta  
**Prioridad:** Alta

---

## BUG-REG-02 — No valida formato de email

**Precondición:**  
Usuario en la página de registro.

**Pasos para reproducir:**
1. Introducir un email sin “@”
2. Completar el resto de campos
3. Pulsar registrar

**Resultado esperado:**  
El sistema muestra un mensaje de email inválido.

**Resultado real:**  
El sistema acepta el email y permite el registro.

**Severidad:** Media  
**Prioridad:** Alta

---

## BUG-REG-03 — Mensaje de error poco claro en contraseña

**Precondición:**  
Usuario en la página de registro.

**Pasos para reproducir:**
1. Introducir una contraseña débil
2. Pulsar registrar

**Resultado esperado:**  
El sistema muestra un mensaje claro sobre los requisitos de contraseña.

**Resultado real:**  
El sistema muestra un mensaje genérico poco informativo.

**Severidad:** Baja  
**Prioridad:** Media

---

## BUG-REG-04 — El botón registrar no se deshabilita tras envío

**Precondición:**  
Usuario en la página de registro.

**Pasos para reproducir:**
1. Completar el formulario correctamente
2. Pulsar registrar varias veces seguidas

**Resultado esperado:**  
El sistema deshabilita el botón tras el primer envío.

**Resultado real:**  
El botón permanece activo y permite múltiples envíos.

**Severidad:** Media  
**Prioridad:** Media

---

## BUG-REG-05 — No se muestra mensaje tras registro exitoso

**Precondición:**  
Usuario en la página de registro.

**Pasos para reproducir:**
1. Completar el formulario con datos válidos
2. Pulsar registrar

**Resultado esperado:**  
El sistema muestra un mensaje confirmando el registro.

**Resultado real:**  
El sistema no muestra ningún mensaje de confirmación.

**Severidad:** Baja  
**Prioridad:** Baja
