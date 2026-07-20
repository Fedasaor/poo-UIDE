# Sistema de Gestión Académica (SGA)

Sistema desarrollado en **Go (Golang)** enfocado en la aplicación práctica de los principios de la Programación Orientada a Objetos (POO).

## Características

- **Gestión de Alumnos:** Registro, actualización de estados y cálculo de edades.
- **Control de Matrículas:** Vinculación cronológica de estudiantes con niveles específicos.
- **Catálogo de Niveles:** Estructura modular para la oferta de cursos (A1, A2, B1, etc.).
- **Persistencia Decoupled:** Implementación de patrones de diseño mediante interfaces de repositorio en memoria.

## Tecnologías utilizadas

- Lenguaje: Go (Golang)

## Estructura del Proyecto

- `/cmd`: Punto de entrada del sistema (`main.go`).
- `/internal/alumno`: Modelo y lógica de negocio del struct `Alumno`.
- `/internal/matricula`: Modelos y lógica de negocio de `Matricula` y `Nivel`.
- `/internal/storage`: Interfaz `Repositorio` e implementaciones de persistencia (en memoria, extensible a base de datos).
- `/pkg`: Utilidades compartidas (validaciones, formateo).

## Roadmap

- Etapa 2: implementación de código (structs, interfaces, lógica de negocio).
- Etapas futuras: gestión de pagos, control de asistencia, gestión de materiales.

## Autores

- Felipe Daniel Sanguil - *Programación Orientada a Objetos*
