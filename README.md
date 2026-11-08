# Concesionaria de Vehiculos
¡Bienvenido a nuestra concesionaria!

Acá no vendemos autos ni motos de verdad (todavía no llegamos a ese nivel económico), pero sí 
tenemos un programa en Java que sabe administrar vehículos, comparar precios y ordenarlos mejor 
que un vendedor con calculadora en mano.

Este proyecto consiste en simular el funcionamiento de una concesionaria utilizando programación 
orientada a objetos y algunas herramientas de Java que hacen que todo funcione como un motor recién 
salido de fábrica.

--- 

## ¿De qué trata?

El programa carga una pequeña flota de vehículos, compuesta por autos y motos, y realiza distintas 
operaciones sin necesidad de que el usuario ingrese absolutamente nada.

Porque si algo podemos automatizar, ¿para qué trabajar de más?

La aplicación muestra por consola:

Todos los vehículos disponibles.
- El vehículo más caro.
- El vehículo más barato.
- El vehículo cuyo modelo contiene la letra "Y".
- Los vehículos ordenados por precio de mayor a menor.
- Los vehículos ordenados naturalmente por marca, modelo y precio.

--- 

## Tecnologías utilizadas
Para construir esta pequeña concesionaria se utilizaron:

**Java:** el principal programa de todo este asunto.
**Spring Boot:** porque una concesionaria moderna necesita tecnología moderna.
**Maven:** para gestionar las dependencias y mantener todo en orden.
**Lombok:** para evitar escribir getters, setters y constructores hasta quedarnos sin dedos.
**Collections Framework:** para almacenar y organizar nuestra flota.
**Stream API:** para buscar, filtrar, comparar y ordenar vehículos sin hacer un desfile de for.
**Programación Orientada a Objetos:** porque cada vehículo tiene su identidad y no todos son cuatro ruedas con techo.

--- 

## ¿Qué puse en práctica hoy?
Durante el desarrollo se aplicaron varios conceptos importantes (mi coco murio):

- Clase abstracta: para definir las características comunes de todos los vehículos.
- Interfaces: para establecer comportamientos que deben cumplir la clase.
- Herencia: porque los autos y las motos comparten características, aunque no sean exactamente iguales.
- Polimorfismo: para tratar distintos tipos de vehículos de manera genérica.
- Comparable: para establecer el orden natural de los vehículos.
- toString(): para mostrar la información de cada vehículo de forma clara.
- Collections: para almacenar y manipular la flota.
- Stream API: para realizar búsquedas, filtros, ordenamientos y etc etc.

--- 
## Nuestra flota
Actualmente contamos con cuatro unidades:
|Marca| |Modelo| |Tipo| |Precio|
|---| |---| |---| |---|
|Peugeot|	|206|	|Auto|	|$200.000,00|
|Honda|	|Titan|	|Moto|	|$60.000,00|
|Peugeot|	|208|	|Auto|	|$250.000,00|
|Yamaha|	|YBR|	|Moto|	|$80.500,50|
Perdón, pero no tenemos financiación suficiente y no nos gusta aceptar limosnas...  tampoco se cómo vamos a llegar a los
proximos modelos

--- 

## ¿Cómo ejecutar el proyecto?
No hace falta traer casco, licencia ni seguro.

Solamente necesitás:

Tener instalado Java.
Tener Maven configurado (o utilizar el Maven Wrapper incluido en el proyecto).
Clonar este repositorio:
