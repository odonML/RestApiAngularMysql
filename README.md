# RestApiAngularMysql
rest api desarrollada con typescript nodejs expres angular y mysql

bueno es una api sencilla desarrollada en las tecnologias ya mencionadas 
en la carpeta AngularNodeMysql se encuentra la api (typescript nodejs expres y mysql)
y en AngularNodeMysql2 se encuentra el cliendte (Angular)

primeramente se necesita crear la base de datos de nombre node_db y crear las trabla el archivo para la creacion 
de la tabla se encuentra en src/mysql/node_db.sql ya con la base de datos creada

es hora de hechar a andar la api mediante el uso de dos consolas:
en la terminal numero uno se encargara de hacer la transpilacion de typescrip a javascript y de igual manera 
se encarga de ejecutar el modulo de copyfile el cual se encarga de mover los archivos de tipo HTML
todo esto se lleva acabo con el siguiente comando:

    npm run build

en la terminal numero dos es la que se encarga de ejecutar el modulo de nodemon el cual es el que ejecuta los 
archivos javascript e imprime los mensajes de consola del servidor, todo con el comando:

    npm run dev
    
posterior mente se tiene que hechar a andar el proyecto de angular dicho proyecto se encuentra en AngularNodeMysql2 
y solo se hecha a andar con el comando:

    ng serve 
    
NOTA : LA BASE DE DATOS TIENE QUE ESTAR CORRIENDO EN UN SERVIDOR LOCAL COMO XAMPP O WAMP 

en el siguiente link fue donde me base para consumir la rest api desde angular:

    https://blog.ng-classroom.com/blog/angular/rest-api-with-angular/
