# Ejercicio Bug Report — BUG-04

## Bug

**ID:** BUG-04  
**Título:** El formulario permite enviar un email con formato inválido  
**Precondición:** El usuario se encuentra en la página del formulario de contacto.

**Pasos para reproducir:**
1. Introducir un nombre válido
2. Introducir un email con formato inválido
3. Introducir un mensaje válido
4. Pulsar el botón "Enviar"

**Resultado esperado:**  
El sistema muestra un mensaje indicando que el formato del email es incorrecto y bloquea el envío del formulario.

**Resultado real:**  
El sistema permite enviar el formulario correctamente sin mostrar ningún mensaje de error.

**Severidad:** Media  
**Prioridad:** Alta

---

## Justificación
El campo email debería validar el formato para evitar datos incorrectos.  
Aunque el sistema no se bloquea, aceptar emails inválidos afecta a la calidad de la información y al funcionamiento posterior del sistema.

---
