# Casos de prueba - Historia 3 (HU-03)

## Caso de prueba 1 - Flujo positivo

- ID del caso de prueba: TC-HU03-01
- Titulo breve: Visualizacion completa del menu
- Objetivo: Validar que el menu muestra productos con nombre, descripcion y precio de forma clara.
- Precondiciones:
  - El usuario esta en la pantalla de menu.
  - Existen productos cargados en el catalogo.
- Datos de prueba:
  - Usuario con acceso al menu.
- Pasos:
  1. Acceder a la seccion de menu.
  2. Revisar varios productos del listado.
  3. Desplazarse hacia abajo en la lista de productos.
- Resultado esperado:
  - Se muestran todos los productos disponibles.
  - Cada producto presenta nombre, descripcion y precio.
  - El listado se visualiza de forma clara y ordenada.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).

## Caso de prueba 2 - Flujo negativo

- ID del caso de prueba: TC-HU03-02
- Titulo breve: Producto sin datos completos en menu
- Objetivo: Validar que el sistema responde adecuadamente cuando un producto no tiene informacion completa.
- Precondiciones:
  - El usuario esta en la pantalla de menu.
  - Existe al menos un producto con campo faltante (nombre, descripcion o precio).
- Datos de prueba:
  - Producto de prueba con descripcion vacia.
- Pasos:
  1. Acceder a la seccion de menu.
  2. Ubicar el producto con informacion incompleta.
  3. Revisar como se muestra el item en pantalla.
- Resultado esperado:
  - El sistema no rompe la visualizacion del menu.
  - El usuario recibe informacion consistente (mensaje, valor por defecto o exclusion del item).
  - Se mantiene el orden y legibilidad del listado.
- Resultado obtenido: Pendiente de ejecucion.
- Estado: Pendiente
- Notas/Evidencias: Pendiente de adjuntar (capturas/logs).
