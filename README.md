
## Seminario 1
Priamo Ramirez
2007 5194


## Proposito
Aplicacion CRUD que interactue con una API (REST) Node.js

(Visual) Bootstrap 3 + Angular.js o Ember.js + Controller -> Node.js (devolver al controller para que alimente aplicación a través de un request HTTP.)

Campos:

- Imagen Responsive(class= "img-responsive")
- Descripción
- Fecha de Creación
- Fecha de Modificación


Incluir Documentación de estructura de la aplicación (Un readme)
Subirlo en GITHUB

##Aplicacion

Es una aplicacion para manejar una metodologia de tipo Sprint.


## Stack

* DB: [MongoDB](http://www.mongodb.org/) 
* Backend: [Node.js](http://nodejs.org/)
* Cliente: [AngularJS](http://www.angularjs.org/)
* CSS:[Twitter's bootstrap](http://getbootstrap.com/)

## Instalar

### Platform & tools

Primero instalar Node.js y despues sus herramientas de desrrollador.

npm install -g grunt-cli karma

### Servidor

Nuestro servidor de aplicaciones back-end es una aplicación NodeJS que se basa en algunos paquetes tercera NGP Parte. Es necesario instalar los siguientes: 

* Instale las dependencias locales (de la carpeta raíz del proyecto):

    ```
    cd server
    npm install
    cd ..
    ```

  (This will install the dependencies declared in the server/package.json file)

### Cliente

* Instale las dependencias locales (de la carpeta raíz del proyecto):

    ```
    cd client
    npm install
    cd ..
    ```



### Correr Servidor

    ```
    cd server
    node server.js
    cd ..
    ```
* Entrar a[http://localhost:3000]
