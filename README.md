# Grupo 7

## Integrantes
- Alejandro Astudillo
- Sebatián Richiardi
- Matías Elgueta
- Sebatián Meneses

## Requerimientos
Se requieren tener instaladas las siguientes aplicaciones para realizar pruebas sobre la aplicacion:
- MongoDB
- Postman

## Instrucciones de ejecucion
- Descomprimir el archivo con la contraseña entregada
- Para la carpeta de Front-End:
  - Se debe entrar a la carpeta.
  - Ejecutar en consola dentro de la carpeta los comandos "**npm i && npm run dev**".
  - Ir al navegador y escribir 'http://localhost:5173/'.
  - De momento existen las rutas:
    - 'http://localhost:5173/': Ruta para el login.
    - 'http://localhost:5173/chat': Ruta a la pagina principal de chat
- Para la carpeta de Back-end:
  - Se debe entrar a la carpeta.
  - Ejecutar en consola dentro de la carpeta los comandos "**npm i && npm run dev**".
  - Mediante la aplicacion *PostMan* se pueden realizar pruebas al servidor de back-end.
  - Para *PostMan* se debe importar el archivo "**chat-backend.postman_collection.json**" a la aplicacion, y se podran ejecutar las peticiones:
    - Crear Usuario
    - Login
    - Mostrar usuarios de BD
    - Eliminar Usuarios
