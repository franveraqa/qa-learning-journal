# Ejercicio Test Plan — TP-03

## Objetivo
Definir cómo se van a realizar las pruebas de la funcionalidad de cierre de sesión (logout) para asegurar que el usuario sale correctamente del sistema y la sesión queda invalidada.

---

## Alcance (In Scope)
Las pruebas incluirán:
- Cierre de sesión desde una sesión activa
- Redirección a la pantalla de inicio de sesión
- Comportamiento tras refrescar la página después del logout
- Acceso bloqueado a páginas privadas tras cerrar sesión

---

## Fuera de alcance (Out of Scope)
Quedan fuera de este plan:
- Seguridad avanzada de sesiones
- Gestión de sesiones en múltiples dispositivos
- Rendimiento y carga
- Integraciones externas

---

## Tipos de prueba
- Pruebas funcionales  
- Smoke testing  
- Regression testing  

---

## Entorno de pruebas
- Navegador: Google Chrome  
- Entorno: Test  
- Dispositivo: Escritorio  

---

## Criterios de entrada
- El usuario está autenticado
- La opción de cerrar sesión está disponible
- El entorno de pruebas está operativo

---

## Criterios de salida
- Los casos de prueba definidos han sido ejecutados
- Los bugs críticos y altos han sido reportados
- No existen bloqueos que impidan finalizar las pruebas

---
