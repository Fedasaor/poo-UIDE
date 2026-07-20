# Sistema de Gestión Académica (SGA)

Sistema desarrollado en **Go (Golang)** enfocado en la aplicación práctica de los principios de la Programación Orientada a Objetos (POO).

## 🚀 Características
- **Gestión de Alumnos:** Registro, actualización de estados y cálculo de edades.
- **Control de Matrículas:** Vinculación cronológica de estudiantes con niveles específicos.
- **Catálogo de Niveles:** Estructura modular para la oferta de cursos (A1, A2, B1, etc.).
- **Persistencia Decoupled:** Implementación de patrones de diseño mediante interfaces de repositorio en memoria.

## 🛠️ Tecnologías utilizadas
- **Lenguaje:** Go (Golang)

## 📁 Estructura del Proyecto
- `/internal/domain`: Modelos y entidades de negocio (`alumno.go`, `matricula.go`, `nivel.go`).
- `/internal/repository`: Interfaces e implementaciones de almacenamiento (`repositorio.go`).
- `/main.go`: Punto de entrada del sistema.

## ✒️ Autores
- **Felipe Daniel Sanguil** - *Desarrollo e Implementación*
