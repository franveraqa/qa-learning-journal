# Ejercicio Bug Report — BUG-05

## Bug

**ID:** BUG-05  
**Título:** El envío del formulario no muestra mensaje de confirmación  
**Precondición:** El usuario se encuentra en la página del formulario de contacto.

**Pasos para reproducir:**
1. Rellenar el campo "Nombre" con caracteres válidos
2. Rellenar el campo "Email" con un email válido
3. Rellenar el campo "Mensaje" con caracteres válidos
4. Pulsar el botón "Enviar"

**Resultado esperado:**  
El sistema envía el formulario correctamente y muestra un mensaje de confirmación al usuario.

**Resultado real:**  
El sistema envía el formulario correctamente, pero no muestra ningún mensaje de confirmación.

**Severidad:** Baja  
**Prioridad:** Media

---

## Justificación
La acción se realiza correctamente, pero la falta de feedback visual genera confusión en el usuario, que no sabe si el formulario se ha enviado correctamente.  
No bloquea la funcionalidad, pero afecta a la experiencia de usuario.

---
