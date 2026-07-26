# Casos de prueba - Historia 6 (HU-06)

## Caso de prueba 1 - Flujo positivo

- ID del caso de prueba: TC-HU06-01
- Titulo breve: Consulta de historial con pedidos previos
- Objetivo: Validar que el usuario visualiza su historial y puede revisar el detalle de cada pedido.
- Precondiciones:
  - El usuario inicio sesion correctamente.
  - Existen pedidos previos asociados a la cuenta.
- Datos de prueba:
  - Usuario: cliente.historial@correo.com
  - Pedidos existentes: al menos 2 registros.
- Pasos:
  1. Acceder a la seccion Historial de pedidos.
  2. Revisar la lista de pedidos mostrada.
  3. Abrir el detalle de uno de los pedidos.
- Resultado esperado:
  - El sistema muestra la lista de pedidos del usuario.
  - Cada pedido incluye fecha, productos y total pagado.
  - El detalle del pedido seleccionado se visualiza correctamente.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).

## Caso de prueba 2 - Flujo negativo

- ID del caso de prueba: TC-HU06-02
- Titulo breve: Consulta de historial sin pedidos registrados
- Objetivo: Validar la respuesta del sistema cuando el usuario no tiene pedidos previos.
- Precondiciones:
  - El usuario inicio sesion correctamente.
  - La cuenta no tiene pedidos registrados.
- Datos de prueba:
  - Usuario: cliente.nuevo.sinpedidos@correo.com
- Pasos:
  1. Acceder a la seccion Historial de pedidos.
  2. Revisar el contenido de la pantalla de historial.
- Resultado esperado:
  - El sistema no muestra errores ni fallos de carga.
  - Se presenta un mensaje informativo indicando que no hay pedidos previos.
  - No se muestran detalles inexistentes.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).
