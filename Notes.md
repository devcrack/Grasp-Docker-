Cada vez que ejecutamos docker run <some_image> si la imagen no ha sido descargada anteriormente Docker descargara la imagen para despues ejecutarla. Una vez que ha sido descargada cada vez que ejecutemos la imagen, esta ya no sera descargada se utilizara la misma imagen cada vez que se genere un nuevo contendor.

Si no hay procesos que se tengan que ejecutar en el contenedor Docker simplemente termina el ese contenedor. 

## Docker Port and Volume Mapping 
Example: 

```docker -p <host_port>:<container_port> -v <host_directory_path> : <container_directory_path>```

In the next example we are going to map the container 80 to 8081 host port, and the volume Users/isol/Desktop/containers/nginx to /usr/share/nginx/html 

so we are going to do: 

```docker -p 8081:80 -v /Users/isol/Desktop/containers/nginx:/usr/share/nginx/html nginx```
