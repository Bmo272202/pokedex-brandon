# Despliegue pokedex en Azure

## Pasos para realizar el despliegue

#### 1. abrimos una terminal en vscode y usamos los comandos npm install y npm run build con el proyecto
#### 2. Esto genera la carpeta llamada dist, la cual tiene el contenido que desplegaremos en el app service
#### 3. Ingresamos al portal azure 
#### 4. Creamos el grupo de recursos
#### 5. Creamos la app web. Tener en cuenta que como es una aplicación que utiliza node js la app web tiene que estar configurada para node 
#### 6. Despues de haber creado nos dirigimos al recurso
#### 7 Nos dirigimos a la seccion de herramientas de desarrollo y dentro de este a herramientas avanzadas
#### 8. Presionamos en Debug console>CMD 
#### 9. Nos dirigimos en las carpetas site>wwwroot y en esta desplegamos, subiendo los archivos del dist.
#### Despues de esto subimos la carpeta raiz del proyecto.
#### para el apartado de los encabezados de seguridad
#### 10. Creamos un archivo llamado web.config y lo alojamos en la carpeta raiz del proyecto
#### 11. Le agregamos las directivas para seguridad y luego de esto miramos bien que no se haya afectado los estilos y revisamos en la pagina https://securityheaders.com/

