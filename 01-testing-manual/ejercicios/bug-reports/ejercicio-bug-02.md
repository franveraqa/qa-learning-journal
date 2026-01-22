# Ejercicio Bug Report — BUG-02

## Bug

**ID:** BUG-02  
**Título:** Mensaje de error genérico al introducir credenciales incorrectas en el login  
**Precondición:** El usuario se encuentra en la página de login.

**Pasos para reproducir:**
1. Introducir un nombre de usuario inválido
2. Introducir una contraseña inválida
3. Pulsar el botón "Login"

**Resultado esperado:**  
El sistema muestra un mensaje claro indicando que las credenciales introducidas no son válidas.

**Resultado real:**  
El sistema muestra un mensaje de error genérico que no informa al usuario sobre el problema.

**Severidad:** Media  
**Prioridad:** Alta

---

## Justificación
El mensaje no es claro y no ayuda al usuario a entender qué ha hecho mal, lo que afecta negativamente a la experiencia de uso.  
La funcionalidad no está bloqueada, pero el problema puede generar confusión y repetición de errores.

---
