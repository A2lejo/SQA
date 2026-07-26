# Casos de prueba - Historia 2 (HU-02)

## Caso de prueba 1 - Flujo positivo

- ID del caso de prueba: TC-HU02-01
- Titulo breve: Inicio de sesion exitoso
- Objetivo: Validar que un usuario registrado puede acceder con credenciales correctas.
- Precondiciones:
  - El usuario ya tiene una cuenta activa.
  - El usuario se encuentra en la pantalla de inicio de sesion.
- Datos de prueba:
  - Correo: cliente.activo@correo.com
  - Contrasena: ClaveCorrecta123
- Pasos:
  1. Ingresar el correo cliente.activo@correo.com.
  2. Ingresar la contrasena ClaveCorrecta123.
  3. Presionar el boton de iniciar sesion.
- Resultado esperado:
  - El sistema valida las credenciales.
  - El usuario accede correctamente a su cuenta.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).

## Caso de prueba 2 - Flujo negativo

- ID del caso de prueba: TC-HU02-02
- Titulo breve: Inicio de sesion con contrasena incorrecta
- Objetivo: Validar que el sistema impide el acceso con credenciales invalidas.
- Precondiciones:
  - El usuario ya tiene una cuenta activa.
  - El usuario se encuentra en la pantalla de inicio de sesion.
- Datos de prueba:
  - Correo: cliente.activo@correo.com
  - Contrasena: ClaveIncorrecta999
- Pasos:
  1. Ingresar el correo cliente.activo@correo.com.
  2. Ingresar la contrasena ClaveIncorrecta999.
  3. Presionar el boton de iniciar sesion.
- Resultado esperado:
  - El sistema rechaza las credenciales.
  - El usuario no accede al sistema.
  - Se muestra un mensaje de error por datos incorrectos.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).
