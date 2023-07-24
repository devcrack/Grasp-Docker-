- **docker ps**: Lista los contenedores que estan en ejecucion. 
### Flags
    - -a: Agregando el parametro -a veremos el historial de los contenedores que han sido ejectudaos en el Host.
- **docker images**: Lista las imagenes que estan descargadas. 

- -**it**:  En Docker se utiliza para ejecutar un contenedor en modo interactivo y asignar un terminal al contenedor. Es una combinación de dos opciones: -i y -t. La combinación -it es útil cuando necesitas interactuar con el contenedor en tiempo real, por ejemplo, para ejecutar comandos dentro del contenedor, explorar su sistema de archivos, ejecutar procesos o depurar aplicaciones que se están ejecutando dentro del contenedor.


- **-i**: Permite mantener abierta la entrada estándar (stdin) del contenedor, lo que permite interactuar con él a través del terminal.
- **-t**: Asigna un pseudo terminal (PTY) al contenedor, lo que hace que la salida sea más legible y permita el uso de comandos como si estuvieras trabajando directamente en el terminal del contenedor.
