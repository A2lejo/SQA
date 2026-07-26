# Casos de prueba - Historia 4 (HU-04)

## Caso de prueba 1 - Flujo positivo

- ID del caso de prueba: TC-HU04-01
- Titulo breve: Agregar producto al carrito con cantidad valida
- Objetivo: Validar que un producto se agrega al carrito y el total se actualiza correctamente.
- Precondiciones:
  - El usuario se encuentra en el menu de productos.
  - El carrito esta disponible para agregar items.
- Datos de prueba:
  - Producto: Cafe Americano
  - Precio unitario: 2.50
  - Cantidad: 2
- Pasos:
  1. Seleccionar el producto Cafe Americano.
  2. Ingresar cantidad 2.
  3. Presionar agregar al carrito.
- Resultado esperado:
  - El producto se agrega al carrito con la cantidad indicada.
  - El total de compra se actualiza automaticamente (5.00).
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).

## Caso de prueba 2 - Flujo negativo

- ID del caso de prueba: TC-HU04-02
- Titulo breve: Agregar producto con cantidad no permitida
- Objetivo: Validar que el sistema impide agregar productos con cantidades invalidas.
- Precondiciones:
  - El usuario se encuentra en el menu de productos.
  - El carrito esta disponible para agregar items.
- Datos de prueba:
  - Producto: Croissant
  - Precio unitario: 1.80
  - Cantidad: 0
- Pasos:
  1. Seleccionar el producto Croissant.
  2. Ingresar cantidad 0.
  3. Presionar agregar al carrito.
- Resultado esperado:
  - El sistema rechaza la cantidad ingresada por no ser valida.
  - El producto no se agrega al carrito.
  - Se muestra un mensaje de validacion al usuario.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).
