# WordpressDockerCompose
Práctica en la que en una máquina Vagrant corremos un docker-compose con Wordpress.

La tarea consiste en lanzar dentro de una máquina virtual Vagrant un Wordpress que será lanzado automáticamente gracias a docker-compose.

Este archivo docker-compose.yml nos lanza 2 dockers:
- El primero contiene el servicio del Wordpress y usará la base de datos alojada en el otro docker que lanzamos
- El segundo aloja la base de datos con Mariadb. Se configuran las variables de entorno para que los docker se comuniquen

En el host levantamos la máquina Vagrant con `vagrant up`

![wordpress2](https://user-images.githubusercontent.com/48716705/237036620-d8a7c780-2469-4e47-bd58-7fcd99aa15ff.png)

Y una vez está en marcha podemos ir a nuestro navegador y en la dirección `localhost:8080` encontramos el Wordpress


![wordpress1](https://user-images.githubusercontent.com/48716705/237036822-6e14f297-2920-4e06-82af-7e587b8963f0.png)
