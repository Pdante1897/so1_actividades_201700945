Servicio de Saludo y Fecha

Este repositorio contiene un servicio de systemd que ejecuta un script para imprimir un saludo y la fecha actual.

Instalación:

1. Clona este repositorio en tu sistema.

2. Navega al directorio del repositorio:

   cd servicio-saludo-fecha

3. Otorga permisos de ejecución al script:

   chmod +x print_date.sh

4. Copia el archivo del servicio a la carpeta systemd:

   sudo cp print-date.service /etc/systemd/system/

5. Recarga systemd para que reconozca el nuevo servicio:

   sudo systemctl daemon-reload

6. Habilita el servicio para que se inicie automáticamente en el arranque:

   sudo systemctl enable print-date.service

7. Inicia el servicio:

   sudo systemctl start print-date.service

Uso:

Una vez que el servicio esté instalado y en funcionamiento, el saludo y la fecha actual se imprimirán en el registro del sistema. Puedes revisar el registro usando:

sudo journalctl -u print-date.service

¡Listo! Ahora el servicio está instalado y puedes verificar el saludo y la fecha en el registro del sistema.

Espero que esta información te sea útil y te ayude a crear y utilizar el servicio de systemd.
