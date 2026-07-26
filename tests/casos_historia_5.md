# Casos de prueba - Historia 5 (HU-05)

## Caso de prueba 1 - Flujo positivo

- ID del caso de prueba: TC-HU05-01
- Titulo breve: Confirmacion de pedido con pago simulado
- Objetivo: Validar que el usuario puede confirmar un pedido y recibir un numero de orden unico.
- Precondiciones:
  - El usuario tiene productos en el carrito.
  - El usuario se encuentra en la pantalla de resumen de pedido.
- Datos de prueba:
  - Productos en carrito: 1 Cafe Latte (3.20), 1 Muffin (2.10)
  - Metodo de pago: Tarjeta simulada
- Pasos:
  1. Revisar el resumen del pedido.
  2. Seleccionar Tarjeta simulada como metodo de pago.
  3. Confirmar el pedido cuando el sistema lo solicita.
- Resultado esperado:
  - El sistema muestra el resumen correctamente.
  - El sistema registra la confirmacion del usuario.
  - Se genera un numero de orden unico.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).

## Caso de prueba 2 - Flujo negativo

- ID del caso de prueba: TC-HU05-02
- Titulo breve: Intento de confirmar pedido sin metodo de pago
- Objetivo: Validar que el sistema no finaliza el pedido si no se selecciona un metodo de pago.
- Precondiciones:
  - El usuario tiene productos en el carrito.
  - El usuario se encuentra en la pantalla de resumen de pedido.
- Datos de prueba:
  - Productos en carrito: 1 Capuccino (3.00)
  - Metodo de pago: No seleccionado
- Pasos:
  1. Revisar el resumen del pedido.
  2. No seleccionar ningun metodo de pago.
  3. Presionar confirmar pedido.
- Resultado esperado:
  - El sistema impide finalizar la compra.
  - No se genera numero de orden.
  - Se muestra un mensaje para seleccionar un metodo de pago valido.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).
