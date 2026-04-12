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
![Bitacora de Viaje DSW](https://github.com/user-attachments/assets/65332980-07b9-471c-883b-242a803c03a3)

## Alcance Funcional (para regularidad y aprobación directa)
<br>
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Pais<br>3. CRUD Hospedaje<br>|
|CRUD dependiente|1. CRUD Viaje {depende de} CRUD Usuario<br> 2. CRUD Localidad {depende de} CRUD Pais<br> 3. CRUD Lugar {depende de} CRUD Localidad<br>|
<br>
|Listado + detalle| <br> 1. Listado de Reseñas filtrado por lugar y fecha. <br> 2. Listado de Hospedaje filtrado por lugar. <br>
|CUU/Epic| <br> 1. Registrar viaje nuevo. <br> 2. Registar reseña moderada con IA. <br> 3. Creación de carrusel de multimedia.<br>
