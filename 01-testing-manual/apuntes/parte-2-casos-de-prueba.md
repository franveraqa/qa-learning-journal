# Parte 2 — Casos de Prueba

## ¿Qué es un caso de prueba?

Un **caso de prueba (Test Case)** es una instrucción clara que indica:

- Qué probar
- Cómo probarlo
- Qué resultado se espera

Sirve para:

- Verificar funcionalidades
- Repetir pruebas siempre igual
- Evitar probar “de memoria”
- Permitir que otra persona ejecute la prueba

---

## 🧱 Estructura de un caso de prueba

Un caso de prueba debe contener siempre:

- ID
- Título
- Precondición
- Pasos
- Resultado esperado

⚠️ Si falta una parte, el caso de prueba está incompleto.

👉 Un buen caso de prueba lo puede ejecutar cualquier persona sin preguntar nada.

---

## 📝 Ejemplo de caso de prueba

**ID:** TC-LOGIN-03  
**Título:** Verificar login con campos vacíos  
**Precondición:** El usuario se encuentra en la página de login  

**Pasos:**
1. Abrir la web  
2. Dejar los campos de usuario y contraseña vacíos  
3. Pulsar el botón de login  

**Resultado esperado:**  
El sistema muestra un mensaje de error indicando que los campos son obligatorios.

---

## 📌 Nota sobre el Resultado Esperado

El resultado esperado:

- Describe **el comportamiento correcto** del sistema
- **No describe el bug**

Si el usuario se equivoca, el sistema debe:
- Bloquear la acción
- Mostrar un mensaje de error

---

## 🧩 Tipos de situaciones al probar

- **Error del usuario:** el sistema responde con un mensaje y bloquea la acción  
- **Error del sistema:** el sistema debería funcionar y no lo hace → **bug**
