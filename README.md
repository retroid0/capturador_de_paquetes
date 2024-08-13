# capturador_de_paquetes
Capturador de paquetes de la IP que elija
Instrucciones para la Instalación y Uso del Programa de Captura de Paquetes
1. Descarga e Instalación
Descargar la Aplicación:

Ve a la sección de Releases en este repositorio de GitHub.
Descarga el archivo .zip que contiene la versión más reciente del programa.
Extraer los Archivos:

Descomprime el archivo .zip en una carpeta de tu elección.

Instalar Npcap:

La aplicación requiere Npcap para capturar paquetes de red.
Si no lo tienes instalado, puedes descargarlo desde Npcap.
Enlace de Npcap https://npcap.com/#download

Durante la instalación, asegúrate de seleccionar la opción "Install Npcap in WinPcap API-compatible Mode".

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Ejecutar la Aplicación:

Navega a la carpeta donde descomprimiste los archivos y ejecuta el archivo MiAplicacion.exe.
Es recomendable ejecutar la aplicación con privilegios de administrador (clic derecho > "Ejecutar como administrador") para asegurar que pueda capturar el tráfico de red correctamente.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2. Uso del Programa

Seleccionar el Adaptador de Red
Al abrir la aplicación, verás un menú desplegable que muestra los adaptadores de red disponibles en tu sistema.
Selecciona el adaptador de red que deseas monitorear (por ejemplo, Wi-Fi o Ethernet).

Configurar la IP a Escanear
En el campo de texto etiquetado como "IP a escanear", introduce la dirección IP que deseas monitorear.
Esta IP puede ser local (dentro de tu red) o externa (en Internet).

Iniciar el Escaneo
Haz clic en el botón "Scanear" para comenzar a capturar los paquetes de red.
La aplicación mostrará el tráfico capturado en una tabla, que incluye detalles como IP de origen, IP de destino, puertos, y protocolo.

Detener el Escaneo
Cuando desees detener la captura, haz clic en el botón "Stop".
La captura se detendrá, pero los datos capturados permanecerán visibles en la tabla.

Limpiar los Datos Capturados
Si deseas limpiar la tabla de resultados, haz clic en el botón "Limpiar".
Esto eliminará todos los datos capturados hasta el momento.

Guardar los Datos Capturados
Para guardar los datos capturados en un archivo de texto:
Selecciona "Guardar Información" en el menú desplegable de acciones.
Haz clic en el botón "Ejecutar".
Aparecerá un cuadro de diálogo que te permitirá elegir la ubicación y el nombre del archivo de texto.
El archivo guardará todos los paquetes capturados con los detalles visibles en la tabla.

Salir del Programa
Para cerrar la aplicación, selecciona "Salir" en el menú desplegable de acciones.
Luego haz clic en el botón "Ejecutar" y la aplicación se cerrará.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3. Requisitos del Sistema
Sistema Operativo: Windows 7 o superior.
.NET Framework: .NET Framework 4.7.2 o superior.
Npcap: Necesario para la captura de paquetes.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4. Notas Adicionales
Es posible que necesites permisos de administrador para que la aplicación pueda capturar tráfico de red.
Si encuentras problemas al capturar paquetes, verifica que Npcap esté instalado correctamente y que el adaptador de red seleccionado esté activo y en uso.

![Imagen ejemplo](https://github.com/retroid0/capturador_de_paquetes/blob/main/capturador.png)


Licencia de Retroid. No esta disponible la venta o modificación de esta aplicación. 2024
