# Instalación

## 1. Software necesario
- Node.js y npm.
- curl

## 2. Obtener el proyecto
Descomprime el archivo `api-productos-a14.zip` y accede a la carpeta desde la terminal.

## 3. Instalar dependencias

Para instalar las dependencias deberemos ejecutar, npm install.

## 4. Iniciar la aplicación

Para arrancar el servidor de la Api deberemos ejecutar npm start.


## 5. Comprobar funcionamiento

Para comprobar que todo funciona usaremos curl y lo podriamos hacer asi para:

#### Obtener todos los productos:
curl http://localhost:3333/api/productos

#### Obtener un producto filtrado por id:
curl http://localhost:3333/api/productos/1 