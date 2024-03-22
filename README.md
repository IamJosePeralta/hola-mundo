# Mi Aplicación Dockerizada

Hola mundo en Python con flask

## Ejecución

Para ejecutar la aplicación utilizando Docker, sigue estos pasos:

1.Clonar el repositorio:

    ```bash
    git clone https://github.com/IamJosePeralta/hola-mundo
    ```
2. Construye la imagen Docker utilizando el Dockerfile proporcionado:

    ```bash
    docker build -t holamundo .
    ```

3.  Ya puedes ejecutar un contenedor basado en esa imagen:

    ```bash
    docker run -d -p 5000:5000 --name mi-aplicacion holamundo
    ```


6. Abre tu navegador web y navega a la siguiente URL para acceder a la aplicación:

    ```
    http://localhost:5000
    ```


