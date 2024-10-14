# Proyecto Transmilenio: Optimización de Rutas

Este proyecto tiene como objetivo desarrollar un sistema que permita buscar la mejor ruta dentro del sistema de portales y estaciones de Transmilenio, utilizando algoritmos de búsqueda en Inteligencia Artificial. Para lograrlo, se implementa una estructura de datos basada en árboles y grafos.

## Características

- Almacenamiento de un diccionario completo de estaciones, con sus respectivas coordenadas geográficas.
- Implementación de mediciones de distancia utilizando la librería `Geopy` y el algoritmo del gran círculo para mejorar la precisión.
- Flexibilidad para adaptar la medición de distancia según las necesidades, permitiendo el uso de otros métodos como la distancia euclidiana o Manhattan.

## Dependencias

Este proyecto requiere las siguientes librerías:

- `PriorityQueue`: Para implementar colas de prioridad.
- `Geopy.distance`: Para calcular distancias entre puntos geográficos.

Este sistema no solo se limita a la optimización de rutas en el ámbito del transporte público, sino que también puede ser aplicado en otros campos que requieran búsqueda y optimización.

* Brayan Steven Caballero Sanchez, 
* Universitaria Iberoamericana, 
* Inteligencia artificial
