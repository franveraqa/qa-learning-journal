# Test Plan — Funcionalidad Login

## Objetivo
Verificar que la funcionalidad de login permite a los usuarios acceder correctamente al sistema, gestionando de forma adecuada los casos válidos e inválidos.

---

## Alcance (In Scope)
Las pruebas incluirán:

- Login con credenciales válidas
- Login con credenciales inválidas
- Validación de campos obligatorios
- Mensajes de error mostrados al usuario
- Redirección tras login exitoso

---

## Fuera de alcance (Out of Scope)
Quedan fuera de este plan:

- Rendimiento y carga
- Envío de emails
- Recuperación de contraseña

---

## Tipos de pruebas
Se ejecutarán los siguientes tipos de pruebas:

- **Pruebas funcionales**  
  Para verificar el comportamiento esperado del login.

- **Smoke testing**  
  Para comprobar que el login funciona de forma básica antes de continuar con más pruebas.

- **Regression testing**  
  Para asegurar que cambios futuros no rompen la funcionalidad.

---

## Entorno de pruebas
- Navegador: Google Chrome
- Entorno: Test
- Dispositivo: Escritorio

---

## Criterios de entrada
Las pruebas comenzarán cuando:

- La funcionalidad de login esté desarrollada
- El entorno de pruebas esté disponible
- Existan usuarios de prueba creados

---

## Criterios de salida
Las pruebas finalizarán cuando:

- Todos los casos de prueba definidos hayan sido ejecutados
- Los bugs críticos y altos hayan sido reportados
- No existan bloqueos que impidan continuar las pruebas

---

## Notas finales
Este Test Plan sirve como documento guía para la ejecución de pruebas de la funcionalidad de login y podrá actualizarse en futuras versiones del producto.
