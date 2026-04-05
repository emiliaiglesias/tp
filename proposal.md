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

Los usuarios podrán crear viajes, definir itinerarios con múltiples destinos y registrar los lugares visitados, incluyendo descripciones, fechas y contenido multimedia.

### Modelo
![BitacoraDeViajeMD](https://github.com/user-attachments/assets/83aff9b6-2274-4f56-bc8e-c63aa24662a3)

## Alcance Funcional 

|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Pais<br>3. CRUD Coordenada<br> 4. CRUD Lugar 5. CRUD Estadia|
|CRUD dependiente|1. CRUD Viaje {depende de} CRUD Usuario<br>2. CRUD Localidad {depende de} CRUD Pais<br> 3. CRUD Reseña {depende de} CRUD Lugar<br>|


|Listado<br>+<br>detalle| 1. Listado de Reseñas filtrado por lugar y fecha.<br> 2. Listado de Estadia filtrado por lugar.<br> |
|CUU/Epic|1. Alta de usuario<br>2. Alta de viaje.<br>3.Alta de reseña.<br>|
