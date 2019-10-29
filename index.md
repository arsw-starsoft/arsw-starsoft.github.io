# Synchdrive

## Integrantes
* [Julian Benitez](https://github.com/julianbenitez99)
* [Luis Pizza](https://github.com/luis572)
* [Juan Ospina](https://github.com/QSARJP)

## Indice
* [Resumen](#resumen)
* [Arquitectura Backend - Synchdrive](#arquitectura-backend---synchdrive)
    * [Diagrama de Clases - Modelo](#diagrama-de-clases---modelo)
    * [Diagrama de Entidad-Relación](#diagrama-de-entidad-relación)
    * [Diagrama de Componentes](#diagrama-de-componentes)
* [Arquitectura Backend - Uber](#arquitectura-backend---uber)
    * [Diagrama de Clases - Modelo - Uber](#diagrama-de-clases---modelo-uber)
    * [Diagrama de Entidad-Relación - Uber](#diagrama-de-entidad-relación---uber)
    * [Diagrama de Componentes - Uber](#diagrama-de-componentes---uber)
* [Arquitectura Frontend](#arquitectura-frontend)
* [Arquitectura Despliegue](#arquitectura-despliegue)
* [Diagrama de Casos de uso](#diagrama-de-casos-de-uso)
* [Continuidad de desarrollo - Github](#continuidad-de-desarrollo---github)
* [Despliegue - Heroku](#despliegue---heroku)
* [Manual de Uso](#manual-de-uso)
* [Enlace a las Historias de Usuario](#enlace-a-las-historias-de-usuario)
* [Estado del Backend de Synchdrive](#estado-del-backend-de-synchdrive)


## Resumen
Actualmente se ofrece una gran variedad de aplicaciones que proporcionan el servicio de transporte contactando a los pasajeros con los vehículos registrados en sus plataformas. Esto resulta beneficioso tanto para el conductor generando utilidades con su automóvil, como para el pasajero que pueden viajar a gusto. El problema radica en que la mayoría de los conductores y usuarios manejan dos o más de las aplicaciones móviles disponibles, les resulta tedioso tener que abrir y cerrar las aplicaciones, en el caso de los usuarios para comparar precios, servicios y solicitar diversos servicios, como para los conductores a la hora de buscar y aceptar los servicios. Tomando en cuenta esta problemática surgió Synchdrive una aplicación web en donde los diferentes usuarios podrán interactuar con las diferentes aplicaciones de transporte en las que estén registrados para poder así tomar la mejor decisión en cuanto al servicio que se requiera según el caso.

## Arquitectura Backend - Synchdrive
El backend se está desarrollando en el siguiente [repositorio](https://github.com/arsw-starsoft/Synchdrive-Backend)
### Diagrama de Clases - Modelo
![](/img/backend/clases.png)

### Diagrama de Entidad-Relación
![](/img/backend/entidad-relacion.png)

### Diagrama de Componentes
![](/img/backend/componentsSD.png)

## Arquitectura Backend - Uber
El backend se está desarrollando en el siguiente [repositorio](https://github.com/arsw-starsoft/Uber-Backend)
### Diagrama de Clases - Modelo - Uber
![](/img/uber/clases.png)

### Diagrama de Entidad-Relación - uber
![](/img/uber/entidad-relacion.png)

### Diagrama de Componentes - Uber
![](/img/uber/componentsUB.PNG)





## Arquitectura Frontend

![](/img/frontend/componentsFE.png)


## Arquitectura Despliegue
![](/img/deployment.png)

### Diagrama de casos de uso
![](/img/casosUso.png)


## Continuidad de desarrollo - Github
El proyecto se está desarrollando en la organización [arsw-starsoft](http://github.com/arsw-starsoft)

## Despliegue - Heroku
El despliegue se realizó en [Heroku](https://arswsynchdrive.herokuapp.com)

## Manual de Uso

En el siguiente enlace podemos encontrar la página inicial de la aplicación, aquí se puede elegir el registro ya sea de conductor o usuario y los respectivos login.

[Pagina de incio](arswsynchdrive.herokuapp.com)

![](/img/manualUsuario/inicio.png)


### User
* Cuando le damos la opción de Sign Up User encontraremos 3 casillas las cuales nos permitirán tener la información básica de la aplicación como lo es el username, el correo y la contraseña.
![](/img/manualUsuario/registrarUsuario.png)
Cuando se le da la opción de Sign Up este nos avisara por medio de una notificación si ha sido exitosa o no. Si es exitosa nos redirigía hacia otro enlace que el cual contiene el respectivo login.

* En el enlace de login podremos colocar el respectivo correo electrónico con el cual nos registramos y la contraseña, cuando seleccionamos el botón de login podremos acceder a la aplicación siendo usuario de las aplicaciones de transporte. 
![](/img/manualUsuario/loginUser.png)

* En el perfil del usuario podremos acceder a toda la información que se tiene dentro de la aplicación desde ahí podremos actualizar los datos suministrados.
![](/img/manualUsuario/perfilUsuario.png)

* Si se desea realizar cualquier modificación de la información se debe acceder a los espacios asignados dependiendo de lo que se quiera modificar ya sea desde información básica como nombre hasta las cuentas asociadas que se pueden tener y luego accionar el botón de update user, Luego nos aparecerá un mensaje el cual nos dirá el estado de la petición, si es exitosa podremos ver que la información ha sido cambiada y cada vez que se intente acceder al perfil esta información se mantiene.

![](/img/manualUsuario/ActualizarUser.png)

Por último, se podrá acceder a los servicios prestados por la aplicación donde el usuario podrá elegir los diferentes tipos de servicios que desea dependiendo de las aplicaciones seleccionadas los filtros necesarios y numero que desee pedir. y además podrá ver el mapa la ubicación donde se encuentra el usuario al momento de pedir un servicio.

![](/img/manualUsuario/userServices.png)



### Driver
* Cuando le damos la opción de Sign Up Driver encontraremos 4 casillas las cuales nos permitirán tener la información básica de la aplicación como lo es el username, el correo, la contraseña y el numero de celular.
![](/img/manualUsuario/registrerDriver.png)
Cuando se le da la opción de Sign Up este nos avisara por medio de una notificación si ha sido exitosa o no. Si es exitosa nos redirigía hacia otro enlace que el cual contiene el respectivo login.

* En el enlace de login podremos colocar el respectivo correo electrónico con el cual nos registramos y la contraseña, cuando seleccionamos el botón de login podremos acceder a la aplicación siendo usuario de las aplicaciones de transporte. 
![](/img/manualUsuario/loginDriver.png)


* En el perfil del driver podremos acceder a toda la información que se tiene dentro de la aplicación desde ahí podremos actualizar los datos suministrados.
![](/img/manualUsuario/driverProfile.png)


* Si se desea realizar cualquier modificación de la información se debe acceder a los espacios asignados dependiendo de lo que se quiera modificar ya sea desde información básica como nombre hasta las cuentas asociadas que se pueden tener y luego accionar el botón de update user, Luego nos aparecerá un mensaje el cual nos dirá el estado de la petición, si es exitosa podremos ver que la información ha sido cambiada y cada vez que se intente acceder al perfil esta información se mantiene.
![](/img/manualUsuario/ActualizarDriver.png)

Por último, se podrá acceder a los servicios prestados por la aplicación para el conductor, donde el podrá elegir los diferentes tipos de servicios que desea ofrecer en las aplicaciones que seleccione y también el tipo de servicios que desea ver con prioridad dependiendo de los filtros escogidos. Además podrá ver la posición exacta del conductor en el mapa que se ve en la imagen.

![](/img/manualUsuario/driverServices.png)



## Enlace a las Historias de Usuario
[![Managed with Taiga.io](https://img.shields.io/badge/managed%20with-TAIGA.io-709f14.svg)](https://tree.taiga.io/project/qsarjp-proyectoarsw-starsoft/backlog "Managed with Taiga.io")


## Estado del Backend de Synchdrive

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/7e83bd6874c943bb97de8bf5825f082d)](https://www.codacy.com/manual/JulianBenitez99/Synchdrive-Backend?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=arsw-starsoft/Synchdrive-Backend&amp;utm_campaign=Badge_Grade)
[![CircleCI](https://circleci.com/gh/arsw-starsoft/Synchdrive-Backend.svg?style=svg)](https://circleci.com/gh/arsw-starsoft/Synchdrive-Backend)

