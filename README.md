# ProyectoPokemon

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Api rest 

Es una interfaz de programación de aplicaciones (API o API web) que se ajusta a los límites de la arquitectura REST y permite la interacción con los servicios web de RESTful. Las API son conjuntos de definiciones y protocolos que se utilizan para diseñar e integrar el software de las aplicaciones.Suele considerarse como el contrato entre el proveedor de información y el usuario, donde se establece el contenido que se necesita por parte del consumidor (la llamada) y el que requiere el productor (la respuesta).

## Fetch/Axios

La api fetch es un metodo del objeto en javascript llamado window, o sea que para utilizarlo no necesitamos instalar nada extra. Simplemente hacemos el llamado escribiendo fetch(url) y esto nos devuelve una promise con la respuesta. En el caso de hacer una petición http GET, el único parámetro obligatorio que recibe fetch es la URL.

Para extraer el body de la respuesta tendremos que usar el metodo .json(). Y con ese valor retornado obtendremos otra promesa en donde viajan los datos que pedimos, accedemos a ellos con .then y utilizando la respuesta pasada por parámetro.

Axios por otro lado es una libreria de javascript . Hay que en importarla en nuestro proyecto por cdn o instalarla. Al igual que fetch, axios se basa en promises. Si vamos a hacer una petición GET, sólo debemos llamar al método desde axios agregandole ..get(url).
La libreria axios directamente nos provee de la respuesta, y tan solo tenemos que indicarle que queremos el data de la respuesta y ya tenemos los datos que pedimos.

La sintaxis mucho no varía, la que nos provee axios es mucho más amigable y no tenemos que parsear ni el body de la petición ni la respuesta, esto nos ahorra tener que acordarnos de esos detalles. Por otro lado, a la hora del manejo de errores, axios gana ya que fetch no es muy intuitivo a la hora de fallar ya que siempre nos da una respuesta por más que falle.

## Servicios

Se creo un servicio poke-api.service.ts

## Componentes creados

Home.component
poke-header.component
poke-list.component
poke-search.component
poke-details.component
