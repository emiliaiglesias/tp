# Propuesta TP DSW

## Grupo
### Integrantes
* 52886 - Caligaris, Nicolás
* 54274 - Iglesias, Emilia
* 53987 - Zanchi, Bianca

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Bitácora de viaje
### Descripción
El sistema consiste en una aplicación web de bitácora de viajes, que permite a los usuarios registrar, organizar y visualizar sus viajes, recorridos y experiencias en distintas ubicaciones geográficas.

Los usuarios podrán crear viajes, registrar los lugares visitados, incluyendo reseñas, descripciones, fechas y contenido multimedia.

### Modelo
<img width="851" height="900" alt="Bitacora de Viaje MD" src="https://github.com/user-attachments/assets/a5b31b63-0143-4043-a617-d4635a59020c" />

## Alcance Funcional

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Pais|
|CRUD dependiente|1. CRUD Viaje {depende de} CRUD Usuario<br> 2. CRUD Localidad {depende de} CRUD Pais|
|Listado<br>+<br>detalle| 1. Listado de Reseñas filtrado por lugar y fecha. <br> 2. Listado de Hospedaje filtrado por lugar|
|CUU/Epic|1. Registrar viaje nuevo. <br> 2. Registar reseña moderada con IA|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Pais<br>3. CRUD Hospedaje|
|CUU/Epic|1. Registrar viaje nuevo. <br> 2. Registar reseña moderada con IA. <br> 3. Creación de carrusel de multimedia|
