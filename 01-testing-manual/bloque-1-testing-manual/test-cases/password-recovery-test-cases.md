# Test Cases — Recuperación de Contraseña

---

## TC-REC-01 — Solicitud con email válido

**Precondición:**  
El usuario existe y se encuentra en la pantalla de recuperación de contraseña.

**Pasos:**
1. Introducir un email válido
2. Pulsar el botón de recuperar contraseña

**Resultado esperado:**  
El sistema muestra un mensaje confirmando que se ha enviado la solicitud de recuperación.

---

## TC-REC-02 — Campo email vacío

**Precondición:**  
El usuario se encuentra en la pantalla de recuperación de contraseña.

**Pasos:**
1. Dejar el campo email vacío
2. Pulsar el botón de recuperar contraseña

**Resultado esperado:**  
El sistema muestra un mensaje indicando que el campo es obligatorio.

---

## TC-REC-03 — Email con formato inválido

**Precondición:**  
El usuario se encuentra en la pantalla de recuperación de contraseña.

**Pasos:**
1. Introducir un email con formato inválido
2. Pulsar el botón de recuperar contraseña

**Resultado esperado:**  
El sistema muestra un mensaje indicando que el formato del email no es válido.

---

## TC-REC-04 — Email no registrado

**Precondición:**  
El usuario se encuentra en la pantalla de recuperación de contraseña.

**Pasos:**
1. Introducir un email no registrado
2. Pulsar el botón de recuperar contraseña

**Resultado esperado:**  
El sistema muestra un mensaje informativo sin indicar si el usuario existe o no.

---

## TC-REC-05 — Envío múltiple de solicitudes

**Precondición:**  
El usuario se encuentra en la pantalla de recuperación de contraseña.

**Pasos:**
1. Introducir un email válido
2. Pulsar el botón de recuperar contraseña varias veces seguidas

**Resultado esperado:**  
El sistema gestiona correctamente la solicitud y evita envíos repetidos.
