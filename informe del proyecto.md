## Informe de Problemas y Soluciones

Durante el desarrollo del proyecto se presentaron diferentes inconvenientes técnicos que fueron solucionados para poder completar satisfactoriamente las actividades propuestas.

Uno de los primeros problemas se presentó durante la instalación y configuración de Docker en Fedora dentro de VirtualBox. Las actualizaciones del sistema y la descarga de paquetes tardaban demasiado tiempo debido a problemas de conectividad y rendimiento de la máquina virtual.

También se presentó un error durante la creación del archivo `serve.py`, ya que inicialmente se escribieron comandos de terminal dentro del archivo Python. Esto generó errores de ejecución debido a que dichos comandos no forman parte del lenguaje Python. La solución consistió en separar correctamente los comandos de terminal del código fuente del programa.

Durante la práctica también surgieron dificultades para diferenciar los comandos propios de Linux de los comandos utilizados por Docker. Esta situación se resolvió mediante la revisión de documentación y la práctica constante de los comandos más utilizados.

Otro problema importante ocurrió durante la configuración de la red entre las máquinas virtuales. Inicialmente ambas máquinas fueron configuradas utilizando el modo **Red Interna** de VirtualBox; sin embargo, no fue posible obtener una dirección IP válida para establecer la comunicación remota mediante SSH. Después de analizar la situación, se modificó la configuración de red a **Adaptador Puente (Bridged Adapter)**, permitiendo obtener correctamente las direcciones IP mediante el comando `ip a` y establecer la conexión SSH entre los equipos.

Finalmente, debido a las dificultades encontradas durante la implementación de Docker en Fedora, se decidió crear una máquina virtual adicional con **Lubuntu 24.04**. Esta alternativa permitió continuar con el desarrollo de la práctica y completar correctamente la instalación y configuración de Docker.
