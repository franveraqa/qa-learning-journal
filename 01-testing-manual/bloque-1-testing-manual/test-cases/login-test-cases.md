# Test Cases — Funcionalidad Login

Este documento contiene los **casos de prueba diseñados para validar la funcionalidad de login**, siguiendo buenas prácticas de testing manual.

---

## TC-LOGIN-01 — Login con credenciales válidas

**Precondición:**  
El usuario existe en el sistema y se encuentra en la página de login.

**Pasos:**
1. Introducir un nombre de usuario válido
2. Introducir una contraseña válida
3. Pulsar el botón de login

**Resultado esperado:**  
El sistema autentica al usuario y lo redirige a la página principal.

---

## TC-LOGIN-02 — Login con contraseña incorrecta

**Precondición:**  
El usuario existe y se encuentra en la página de login.

**Pasos:**
1. Introducir un nombre de usuario válido
2. Introducir una contraseña incorrecta
3. Pulsar el botón de login

**Resultado esperado:**  
El sistema no permite el acceso y muestra un mensaje indicando que las credenciales son incorrectas.

---

## TC-LOGIN-03 — Login con campos obligatorios vacíos

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos:**
1. Dejar los campos de usuario y contraseña vacíos
2. Pulsar el botón de login

**Resultado esperado:**  
El sistema muestra un mensaje de error indicando que los campos son obligatorios y no permite el acceso.

---

## TC-LOGIN-04 — Login con usuario inexistente

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos:**
1. Introducir un nombre de usuario inexistente
2. Introducir una contraseña cualquiera
3. Pulsar el botón de login

**Resultado esperado:**  
El sistema no permite el acceso y muestra un mensaje de error informando que las credenciales no son válidas.

---

## TC-LOGIN-05 — Persistencia de sesión tras login exitoso

**Precondición:**  
El usuario ha iniciado sesión correctamente.

**Pasos:**
1. Iniciar sesión con credenciales válidas
2. Refrescar la página del navegador

**Resultado esperado:**  
La sesión del usuario se mantiene activa y no se solicita volver a iniciar sesión.

---

## 📌 Notas
- Todos los casos de prueba describen únicamente el comportamiento esperado
- Los bugs detectados durante la ejecución se documentan en la carpeta `bug-reports`
- Estos casos de prueba sirven como base para pruebas funcionales, smoke y regression
