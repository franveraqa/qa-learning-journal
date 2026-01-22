# Ejercicio Bug Report — BUG-01

## Bug

**ID:** BUG-01  
**Título:** El formulario permite enviarse con el campo email vacío  
**Precondición:** El usuario se encuentra en la página del formulario de contacto.

**Pasos para reproducir:**
1. Introducir un nombre válido
2. Dejar el campo "Email" vacío
3. Pulsar el botón "Enviar"

**Resultado esperado:**  
El sistema bloquea el envío del formulario y muestra un mensaje indicando que el campo email es obligatorio.

**Resultado real:**  
El sistema procesa el envío del formulario sin mostrar ningún mensaje de error.

**Severidad:** Media  
**Prioridad:** Alta

---

## Justificación
La severidad es media porque el sistema sigue funcionando, pero permite datos incorrectos.  
La prioridad es alta porque afecta a la calidad de los datos enviados y a la experiencia del usuario.

---
