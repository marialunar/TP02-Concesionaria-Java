# 🚗 Concesionaria - Java / Spring Boot

## Descripción

Este proyecto simula el funcionamiento de una **concesionaria de vehículos** en Java, utilizando programación orientada a objetos, **interfaces**, **Streams** y **Collections**.  
Permite gestionar y mostrar información de **autos y motos**, encontrar el vehículo más caro o más barato, filtrar por letra en el modelo y ordenar los vehículos por precio o por orden natural (marca, modelo, precio).

El proyecto se desarrolló utilizando **Lombok** para reducir código repetitivo y mejorar la legibilidad.

---

## Características principales

- Modelado de vehículos con herencia:
  - `Vehiculo` (abstracta) → atributos comunes `marca`, `modelo`, `precio`.
  - `Auto` → atributo extra: `puertas`.
  - `Moto` → atributo extra: `cilindrada`.
- Implementación de **orden natural** mediante `Comparable<Vehiculo>`.
- Gestión de vehículos mediante **interfaz de servicio** (`IConcesionaria`) y su implementación (`Concesionaria`).
- Uso de **Collections y Streams** para:
  - Filtrar vehículos por letra en el modelo.
  - Ordenar vehículos por precio descendente.
  - Ordenar vehículos por orden natural.
- Formateo de precios con **DecimalFormat**.
- Salida de información por consola de forma legible y estructurada.


