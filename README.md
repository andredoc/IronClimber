# IronClimber APP - MARKDOWN

This project has been designed, code and thought by a team of two, Andre Documet and Jorge Garzón, during a 7 day week assignment on an Iron Hack Bootcamp context.

The aim of this project was to challenge us to create a Web App to show the most important places to climb in Spain using ExpressJS, Handlebars, MongoDB, GoogleMaps API and Google Places Library. 

A. Documet

## Build & development 

- From the terminal, in the project folder, type `npm install`
- After npm finished, from the terminal, in the project folder, type `npm start`

| Method | Url | Description | Protected |
| ----------- | ----------- | ----------- | ----------- |
| GET | /auth/signup | renderiza formulario de registro |  |
| POST | /auth/signup | envia formulario de registro |  |
| GET | /auth/login | renderiza formulario de ingreso |  |
| POST | /auth/login | envia formulario de ingreso |  |
| POST | /auth/logout | cierra sesion: usuario con mismo id y ADMIN |  	|
| GET | /places | muestra los lugares que están cerca: usuario logueado  |  |      
| GET | /places/create | renderiza formulario de creación de lugar: admin y Experto | ✅  | 
| POST | /places/create | permite crear un lugar: admin y Experto | ✅   |
| GET | /places/:id | muestra detalle del lugar seleccionado: usuario logueado |   |
| GET | /places/:id/edit | modificar detalles del lugar seleccionado: admin y Experto | 	✅ |
| POST | /places/:id/edit | modificar detalles del lugar seleccionado: admin y Experto | 	✅ |
| POST | /places/:id/delete | permite eliminar un lugar: admin y Experto | 	✅  |
| POST | /reviews/new-comment/:id | permite añadir comentarios del lugar seleccionado: usuario logueado |   |
| POST | /reviews/:id/delete | borra comentarios del lugar seleccionado: usuario con mismo id, admin y Experto | ✅   |
| GET | /user/search | permite ubicar a un usuario: usuario logueado |  |
| POST | /user/search | permite ubicar a usuario por email: usuario logueado |  |
| GET | /user/:id/details | permite ver los detalles de un usuario: usuario logueado |  |
| GET | /user/:id/edit | permite modificar los detalles de un usuario: Usuario mismo id | 	✅ |
| POST | /user/:id/edit | permite modificar los detalles de un usuario: Usuario mismo id, admin | 	✅ |
| POST | /user/:id/delete | permite eliminar un usuario: Usuario con mismo id & admin | ✅ |

## Web app ScreenShots

HOME PAGE

![Alt text](/public/images/screen_home_page.png)

LOGIN

![Alt text](/public/images/screen_login.png)

PLACE LIST

![Alt text](/public/images/screen_place_list.png)

PLACE DETAILS

![Alt text](/public/images/screen_place_details.png)

CREATE PLACE

![Alt text](/public/images/screen_create_place.png)

PROFILE USER

![Alt text](/public/images/screen_profile_user.png)