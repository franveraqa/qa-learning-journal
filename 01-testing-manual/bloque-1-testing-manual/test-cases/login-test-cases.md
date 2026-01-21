# Test Cases — Login

Este documento contiene los casos de prueba diseñados para validar la funcionalidad de login.

---

## TC-LOGIN-01  
**Título:** Verificar login con usuario y contraseña válidos  

**Precondición:**  
El usuario se encuentra en la página de login y dispone de credenciales válidas.

**Pasos:**  
1. Abrir la web  
2. Introducir un usuario válido  
3. Introducir una contraseña válida  
4. Pulsar el botón de login  

**Resultado esperado:**  
El sistema permite al usuario acceder a su cuenta.

---

## TC-LOGIN-02  
**Título:** Verificar login con campos vacíos  

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos:**  
1. Abrir la web  
2. Dejar los campos de usuario y contraseña vacíos  
3. Pulsar el botón de login  

**Resultado esperado:**  
El sistema muestra un mensaje de error indicando que los campos son obligatorios.

---

## TC-LOGIN-03  
**Título:** Verificar login con contraseña vacía  

**Precondición:**  
El usuario se encuentra en la página de login y el usuario está registrado.

**Pasos:**  
1. Abrir la web  
2. Introducir un usuario registrado  
3. Dejar vacío el campo de contraseña  
4. Pulsar el botón de login  

**Resultado esperado:**  
El sistema muestra un mensaje de error indicando que el campo contraseña es obligatorio.

---

## TC-LOGIN-04  
**Título:** Verificar login con usuario vacío  

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos:**  
1. Abrir la web  
2. Dejar vacío el campo de usuario  
3. Introducir cualquier contraseña  
4. Pulsar el botón de login  

**Resultado esperado:**  
El sistema muestra un mensaje de error indicando que el campo usuario es obligatorio.

---

## TC-LOGIN-05  
**Título:** Verificar login con credenciales incorrectas  

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos:**  
1. Abrir la web  
2. Introducir un usuario incorrecto  
3. Introducir una contraseña incorrecta  
4. Pulsar el botón de login  

**Resultado esperado:**  
El sistema muestra un mensaje de error indicando que las credenciales no son válidas.
