# DAQ Visualizer

Este proyecto contiene una aplicación para la visualización de datos de adquisición (DAQ).

## Uso

Para ejecutar la aplicación, sigue estos pasos:

1. Ejecuta el archivo `DAQ_Visualizer.exe`.
2. En tu navegar ingresa a 127.0.0.1:5000

## Funcionalidad

   * Adquisición de Datos en Tiempo Real: Se conecta a un puerto serial (COM) para leer datos de un
     dispositivo externo (como un microcontrolador o sensor).
   * Guardado de Datos: Los datos recibidos se guardan automáticamente en un archivo CSV con un nombre basado
     en la fecha y hora (ej. datos_YYYYMMDD_HHMMSS.csv).
   * Visualización en Tiempo Real: Utiliza WebSockets (Flask-SocketIO) para enviar los datos adquiridos a una
     interfaz web (index.html) en tiempo real, permitiendo su visualización instantánea.
   * Carga de Datos Históricos: Permite cargar y visualizar datos de archivos CSV previamente guardados
     (referidos como "misiones").
   * Interfaz de Usuario: Proporciona una interfaz web donde el usuario puede seleccionar el puerto serial, la
      velocidad de transmisión (baudrate) y el número de variables a leer, así como iniciar/detener la
     adquisición y cargar misiones.


## Contacto

Vicente Jerez
vicente.jerez@ug.uchile.cl
