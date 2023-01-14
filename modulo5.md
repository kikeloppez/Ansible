## Desplegar servicios en Ansible

## Pasos a seguir
En el cliente, debemos crear un usuario con privilegios root.

Este usuario será el mismo que hemos colocado en el archivo .yml del servidor.

![foto1](https://github.com/kikelopser/Ansible/blob/main/Ansible/1-client.png)

En el servidor, creamos una key de ssh, la cual, vamos a enviar al cliente. Es importante enviar la key para los pasos posteriores.

![foto4](https://github.com/kikelopser/Ansible/blob/main/Ansible/4-server.png)
![foto5](https://github.com/kikelopser/Ansible/blob/main/Ansible/5-server.png)

Por ultimo, desplegamos el contenedor en el cliente de la siguiente manera.

![foto9](https://github.com/kikelopser/Ansible/blob/main/Ansible/9-server.png)

Para comprobarlo, vamos al navegador y colocamos la IP del cliente.

◀️ [VOLVER](https://github.com/kikelopser/Ansible)
