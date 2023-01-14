## Configurar un playbook en Ansible.
Estos son el lenguaje de configuración, implementación y orquestación de Ansible. Pueden describir la configuración que se desea que apliquen los equipos gestionados, o un conjuntos de fases en un proceso general de automatización.

## Pasos a seguir

Para configurar un Playbook, primeramente debemos crear un usuario con privilegios de root en el cliente.

![foto2](https://github.com/kikelopser/Ansible/blob/main/Ansible/1-client.png)

Una vez realizado el paso anterior, vamos al servidor y creamos un directorio de trabajo, para posteriormente crear un fichero de configuración donde apuntaremos el nombre del cliente al que nos dirigimos.

![foto3](https://github.com/kikelopser/Ansible/blob/main/Ansible/2-server.png)
![foto3](https://github.com/kikelopser/Ansible/blob/main/Ansible/3-server.png)

Guardamos el fichero y creamos una key de ssh, la cual, vamos a enviar al cliente. Es importante enviar la key para los pasos posteriores.

![foto4](https://github.com/kikelopser/Ansible/blob/main/Ansible/4-server.png)
![foto5](https://github.com/kikelopser/Ansible/blob/main/Ansible/5-server.png)

Tras enviar la key ssh, creamos otro fichero de configuración con formato .yml, este formato es el que reconoce Ansible.
Lo rellenamos de la siguiente forma para poder desplegar un servicio Nginx.

![foto8](https://github.com/kikelopser/Ansible/blob/main/Ansible/8-server.png)

Por ultimo, desplegamos el contenedor en el cliente de la siguiente manera.

![foto9](https://github.com/kikelopser/Ansible/blob/main/Ansible/9-server.png)

Para comprobarlo, vamos al navegador y colocamos la IP del cliente.
