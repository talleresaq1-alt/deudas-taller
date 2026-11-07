# Deudas y trabajos · versión móvil

Aplicación de consulta adaptada al móvil. Permite buscar y filtrar presupuestos y pagos, abrir el enlace del presupuesto y ver anotaciones guardadas en las columnas de pagos o fechas.

## Cargar el libro

Pulsa **Cargar Excel** y elige `Deudas.xlsm`. En Chrome y otros navegadores compatibles, la webapp puede recordar en ese navegador el archivo elegido y volver a leerlo al abrir la página, si el permiso sigue activo. Si el navegador pide permiso, toca **Actualizar desde archivo**. La referencia queda guardada solo en ese dispositivo; el libro se lee en el navegador, no se modifica ni se envía a esta web. Si el navegador no ofrece esa función (por ejemplo, Safari u otros navegadores sin acceso persistente a archivos), puedes seguir eligiendo el libro manualmente desde OneDrive.

El lector de Excel se carga desde el CDN oficial de SheetJS, por lo que hace falta conexión a Internet para importar un archivo.

## Añadirla al móvil

Para instalarla como aplicación, hay que alojar esta carpeta en un sitio HTTPS. Después abre su dirección en el navegador del móvil y elige **Añadir a pantalla de inicio** o **Instalar aplicación**. El alojamiento y el inicio de sesión privado todavía no están configurados.

Esta primera versión no sincroniza los datos automáticamente: hay que seleccionar el archivo actualizado cuando se quiera consultar la última versión. El Excel original y sus macros siguen siendo el archivo de trabajo.



