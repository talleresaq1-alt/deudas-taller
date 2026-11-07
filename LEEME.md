# Deudas y trabajos · versión móvil

Aplicación de consulta adaptada al móvil. Permite buscar y filtrar presupuestos y pagos, y abrir el enlace de presupuesto guardado en la columna NUMERO del Excel.

## Cargar el libro

Pulsa **Cargar Excel** y elige `Deudas.xlsm`. En el móvil, si OneDrive está disponible en el selector de archivos del dispositivo, puedes navegar hasta el libro allí. La lectura se realiza en el navegador: el archivo no se modifica ni se envía a esta web.

El lector de Excel se carga desde el CDN oficial de SheetJS, por lo que hace falta conexión a Internet para importar un archivo.

## Añadirla al móvil

Para instalarla como aplicación, hay que alojar esta carpeta en un sitio HTTPS. Después abre su dirección en el navegador del móvil y elige **Añadir a pantalla de inicio** o **Instalar aplicación**. El alojamiento y el inicio de sesión privado todavía no están configurados.

Esta primera versión no sincroniza los datos automáticamente: hay que seleccionar el archivo actualizado cuando se quiera consultar la última versión. El Excel original y sus macros siguen siendo el archivo de trabajo.

