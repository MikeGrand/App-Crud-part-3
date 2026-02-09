# android-registration-app-part-3

Este proyecto corresponde a la **tercera parte de un sistema de registro multiplataforma**, enfocado en el desarrollo de una **aplicación móvil Android** que consume una **API REST**, permitiendo realizar operaciones donde el sistema permite crear, listar, modificar, eliminar y ver los registros mediante una arquitectura basada en servicios.

La aplicación móvil reutiliza la API desarrollada en la **Parte 1**, demostrando la escalabilidad y reutilización del backend en diferentes plataformas.

---

## Descripción del sistema completo

El sistema está dividido en tres partes:

- **Parte 1:** Aplicación web + API REST (PHP + MySQL)
- **Parte 2:** Aplicación de escritorio (C# / Windows Forms)
- **Parte 3:** Aplicación móvil Android (**este repositorio**)

---

## Funcionalidades

- Crear registros desde la aplicación móvil
- Listar registros obtenidos desde la API REST
- visualizar todos los registros
- Editar información existente
- Eliminar registros
- Validación básica de datos
- Comunicación mediante respuestas JSON
- Arquitectura basada en servicios (cliente / API)

---

## Tecnologías utilizadas

- Android Studio
- Lenguaje: **Java / Kotlin** 
- XML para interfaces
- Consumo de API REST
- Gradle
- Git & GitHub

---

## Backend (API REST)

La aplicación consume una **API REST desarrollada en PHP**, la cual:

- Utiliza MySQL como base de datos
- Devuelve respuestas en formato JSON
- Implementa validaciones básicas
- Aplica prevención básica contra XSS (`htmlspecialchars`)

> ⚠️ Este repositorio **no incluye** la API ni la base de datos, solo el cliente móvil.
> toda la conexion esta en la parte 1


