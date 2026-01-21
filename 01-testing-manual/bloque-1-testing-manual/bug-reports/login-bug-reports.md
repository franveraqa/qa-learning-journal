# Bug Reports — Login

Este documento contiene los bugs detectados durante las pruebas de la funcionalidad de login.

---

## BUG-LOGIN-01  
**Título:** El login con contraseña vacía no muestra mensaje de error  

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos para reproducir:**  
1. Abrir la web  
2. Introducir un usuario válido  
3. Dejar vacío el campo de contraseña  
4. Pulsar el botón de login  

**Resultado esperado:**  
El sistema muestra un mensaje de error indicando que el campo contraseña es obligatorio.

**Resultado real:**  
El sistema no muestra ningún mensaje.

**Severidad:** Alta  
**Prioridad:** Alta  

---

## BUG-LOGIN-03  
**Título:** El botón de login no responde al hacer clic  

**Precondición:**  
El usuario se encuentra en la página de login y dispone de credenciales válidas.

**Pasos para reproducir:**  
1. Abrir la web  
2. Introducir un usuario válido  
3. Introducir una contraseña válida  
4. Pulsar el botón de login  

**Resultado esperado:**  
El sistema procesa el login y permite al usuario acceder a su cuenta.

**Resultado real:**  
El sistema no responde al pulsar el botón de login.

**Severidad:** Alta  
**Prioridad:** Alta  

---

## BUG-LOGIN-04  
**Título:** El login con usuario no registrado no muestra mensaje de error claro  

**Precondición:**  
El usuario se encuentra en la página de login.

**Pasos para reproducir:**  
1. Abrir la web  
2. Introducir un usuario no registrado  
3. Introducir cualquier contraseña  
4. Pulsar el botón de login  

**Resultado esperado:**  
El sistema muestra un mensaje de error indicando que el usuario no existe.

**Resultado real:**  
El sistema muestra un mensaje genérico o no muestra información clara.

**Severidad:** Media  
**Prioridad:** Media  
