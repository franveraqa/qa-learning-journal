# Test Cases — Registro de Usuario

---

## TC-REG-01 — Registro con datos válidos

**Precondición:**  
El usuario se encuentra en la página de registro.

**Pasos:**
1. Introducir un nombre válido
2. Introducir un email válido
3. Introducir una contraseña válida
4. Pulsar el botón de registro

**Resultado esperado:**  
El sistema crea el usuario y muestra un mensaje de confirmación.

---

## TC-REG-02 — Campos obligatorios vacíos

**Precondición:**  
El usuario se encuentra en la página de registro.

**Pasos:**
1. Dejar todos los campos vacíos
2. Pulsar el botón de registro

**Resultado esperado:**  
El sistema muestra mensajes de error indicando que los campos son obligatorios.

---

## TC-REG-03 — Registro con email inválido

**Precondición:**  
El usuario se encuentra en la página de registro.

**Pasos:**
1. Introducir un email con formato inválido
2. Completar el resto de campos correctamente
3. Pulsar el botón de registro

**Resultado esperado:**  
El sistema muestra un mensaje indicando que el email no es válido.

---

## TC-REG-04 — Registro con contraseña débil

**Precondición:**  
El usuario se encuentra en la página de registro.

**Pasos:**
1. Introducir una contraseña corta o simple
2. Completar el resto de campos correctamente
3. Pulsar el botón de registro

**Resultado esperado:**  
El sistema muestra un mensaje indicando que la contraseña no cumple los requisitos.

---

## TC-REG-05 — Registro con email ya existente

**Precondición:**  
Existe un usuario registrado con el mismo email.

**Pasos:**
1. Introducir un email ya registrado
2. Completar el resto de campos correctamente
3. Pulsar el botón de registro

**Resultado esperado:**  
El sistema muestra un mensaje indicando que el usuario ya existe.
