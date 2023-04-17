### Enunciado

La actividad consiste en desarrollar el diagrama ER y los esquemas de las relaciones resultantes del siguiente dominio de problema:
Se trata de una base de datos para administrar una **empresa de transportes**.
La empresa desea mantener rutas de entrega **fijas**, cada ruta es una secuencia de localidades en un cierto orden y tiene una duración estimada. En cada ruta se pueden visitar varios clientes por localidad. Por una localidad puede pasar mas de una ruta.
Mantiene una flota de **camiones** con *datos de marca, modelo, año, carga máxima*. 
Los choferes tienen asignadas rutas, las rutas pueden ser asignadas a mas de un **chofer** y un chofer puede tener asignadas mas de una ruta.
De cada **viaje** que se realiza se registra la ruta, la hora de partida, el o los choferes, la hora de llegada.

### 0. Analisis Previo / Debate / Dominio del problema

- Tenemos una Empresa de Transportes
- Como toda empresa tiene clientes, por lo que va requerir informacion del **cliente** como numero de telefono, direccion entrega, nombre, domicilio.
- El cliente debe abonar un monto mediante algun medio pago (Pero no se tomara en consideracion) (Haremos Logistica no cobros)
- La empresa tiene emplados, pero los que nos incumben en logistica son los **choferes**. De ellos es necesario saber dni, nombre, telefono, domicilio.
- Los choferes transporaan y entregan la entraga realizando **viajes** por **rutas** pre establecidas. Pueden requerirse varios choferes por ruta.
- Cada ruta es una secuencia de localidades en cierto orden.
- Cada ruta tiene un duracion (atributo).
- ==Definimos que un viaje puede tener una sola ruta y una ruta puede constituir un solo viaje ?==
- ==Es una empresa de transporte pero que transporta== 
- ==Hace faalta una entidad pedido?==


### 1. Analizar el enunciado detectando los sustantivos y sus interrelaciones, los sustantivos son candidatos a entidades
- Sustantivos Candidatos:
  - Empresa de Transporte NOT
  - Rutas de Entrega (duracion) OK
  - Localidades OK
  - Cliente OK
  - Camion o vehiculo (marca,modelo,año,marca,carga maxima) OK
  - Choferes OK
  - Viaje OK
- Supuestos:
  - Cada viaje hace uso de unaa sola ruta
- Entidades Elegidas
  - E1: Viaje
  - E2: Ruta
    - E3: Chofer
    - E4: Vehiculo
    - E5: Localidad
    - E6: Cliente
  
### 2. Formar la matriz de entidades

<table>
  <tr>
  <td>E \ E</td>
    <td>Viaje</td>
    <td>Ruta</td>
    <td>Empleado</td>
    <td>Vehiculo</td>
    <td>Localidad</td>
    <td>Cliente</td>
  </tr>
  <tr>
  <td>Viaje</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Ruta</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
  <td>Empleado</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
  <td>Vehiculo</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
  <td>Localidad</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
  <td>Cliente</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
</table>



### 3. Construir un primer DER
### 4. Análisis de cardinalidades
### 5. Detectar e eliminar redundancias
### 6. Convertir el DER en entidades relacionales (o tablas)
### 7. Implementar en el motor usando DDL
