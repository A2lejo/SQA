# Casos de prueba - Historia 1 (HU-01)

## Caso de prueba 1 - Flujo positivo

- ID del caso de prueba: TC-HU01-01
- Titulo breve: Registro exitoso de usuario
- Objetivo: Validar que un usuario nuevo puede registrarse con correo y contrasena validos.
- Precondiciones:
  - El usuario se encuentra en la pantalla de registro.
  - El correo de prueba no esta registrado en el sistema.
- Datos de prueba:
  - Correo: cliente.nuevo@correo.com
  - Contrasena: ClaveSegura123
- Pasos:
  1. Ingresar el correo cliente.nuevo@correo.com.
  2. Ingresar la contrasena ClaveSegura123.
  3. Presionar el boton de registro.
- Resultado esperado:
  - El sistema valida el formato del correo y confirma que no esta registrado.
  - La cuenta se crea correctamente.
  - Se muestra un mensaje de confirmacion de registro exitoso.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).

## Caso de prueba 2 - Flujo negativo

- ID del caso de prueba: TC-HU01-02
- Titulo breve: Registro con correo ya existente
- Objetivo: Validar que el sistema rechaza el registro cuando el correo ya fue utilizado.
- Precondiciones:
  - El usuario se encuentra en la pantalla de registro.
  - El correo cliente.registrado@correo.com ya existe en el sistema.
- Datos de prueba:
  - Correo: cliente.registrado@correo.com
  - Contrasena: ClaveSegura123
- Pasos:
  1. Ingresar el correo cliente.registrado@correo.com.
  2. Ingresar la contrasena ClaveSegura123.
  3. Presionar el boton de registro.
- Resultado esperado:
  - El sistema detecta que el correo ya esta registrado.
  - No se crea una nueva cuenta.
  - Se muestra un mensaje de error indicando que el correo ya existe.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).
