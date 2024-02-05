1. Instalar docker desktop
  https://www.docker.com/products/docker-desktop/
3.  Abrir la terminal de windows con CMD.
4. Introducir el siguiente comando para instalar la instancia de contenedor.
5.    ```docker pull odoo:16.0```
6. Crear una carpeta con el nombre Odoo
8. Crear un archivo llamado docker-compose con la extensión .yml dentro de la carpeta creada anteriormente
9. Copiar el contenido dentro del archivo .yml
10. Abrir un terminal en la carpeta y correr el siguiente comando .
11.   ```docker compose up -d```
12.   Se creará una carpeta llamada addons, en la cual se tiene que descomprimir el archivo odoo_rest-16.0.zip
13.   Una vez terminado el proceso del comando anterior, abrir un navegador y ingresar al puerto del local host señalado en el archivo .yml
14.   Rellenar el formulario de datos que se piden.
15.   Instalar los módulos que se requiera utilizar en odoo.
16.   En el buscador escribir Rest, para instalar el api_rest que servirá para la implementación de apis.
