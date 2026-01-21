# Bug Reports — Recuperación de Contraseña

---

## BUG-REC-01 — Permite enviar solicitud sin email

**Precondición:**  
Usuario en la pantalla de recuperación de contraseña.

**Pasos para reproducir:**
1. Dejar el campo email vacío
2. Pulsar el botón de recuperar contraseña

**Resultado esperado:**  
El sistema bloquea el envío y muestra un mensaje de error.

**Resultado real:**  
El sistema permite enviar la solicitud sin mostrar ningún mensaje.

**Severidad:** Alta  
**Prioridad:** Alta

---

## BUG-REC-02 — No valida formato de email

**Precondición:**  
Usuario en la pantalla de recuperación de contraseña.

**Pasos para reproducir:**
1. Introducir un email sin formato válido
2. Pulsar el botón de recuperar contraseña

**Resultado esperado:**  
El sistema muestra un mensaje indicando formato incorrecto.

**Resultado real:**  
El sistema acepta el email y continúa el proceso.

**Severidad:** Media  
**Prioridad:** Alta

---

## BUG-REC-03 — Mensaje confuso tras solicitud correcta

**Precondición:**  
Usuario en la pantalla de recuperación de contraseña.

**Pasos para reproducir:**
1. Introducir un email válido
2. Pulsar el botón de recuperar contraseña

**Resultado esperado:**  
El sistema muestra un mensaje claro indicando que se ha enviado la solicitud.

**Resultado real:**  
El sistema muestra un mensaje ambiguo que no informa correctamente al usuario.

**Severidad:** Baja  
**Prioridad:** Media

---

## BUG-REC-04 — El botón no se deshabilita tras envío

**Precondición:**  
Usuario en la pantalla de recuperación de contraseña.

**Pasos para reproducir:**
1. Introducir un email válido
2. Pulsar el botón varias veces seguidas

**Resultado esperado:**  
El sistema deshabilita el botón tras el primer envío.

**Resultado real:**  
El botón permanece activo permitiendo múltiples envíos.

**Severidad:** Media  
**Prioridad:** Media

---

## BUG-REC-05 — No se muestra feedback al usuario

**Precondición:**  
Usuario en la pantalla de recuperación de contraseña.

**Pasos para reproducir:**
1. Introducir un email válido
2. Pulsar el botón de recuperar contraseña

**Resultado esperado:**  
El sistema muestra algún tipo de confirmación visual.

**Resultado real:**  
No se muestra ningún mensaje ni indicación visual.

**Severidad:** Baja  
**Prioridad:** Baja
