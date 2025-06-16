# DRCars - Sistema Integral de Gestión de Vehículos

Este repositorio contiene el Trabajo de Fin de Grado (TFG) titulado **"DRCars"**, un sistema completo para la gestión de vehículos que incluye una aplicación web, una API backend, una aplicación de escritorio y el script para la creación de la base de datos.

## 🗂 Estructura del Proyecto

El repositorio está organizado en las siguientes carpetas:

### 📁 `DRCarsWeb`
Contiene el **código fuente de la aplicación web** desarrollada con **Next.js**. Esta interfaz permite a los usuarios interactuar con el sistema desde el navegador.

- **Tecnología**: Next.js (React)
- **Características principales**:
  - Autenticación de usuarios
  - Visualización y gestión de vehículos
  - Acceso a funcionalidades conectadas a la API REST

### 📁 `DRCarsApiREST`
Incluye el **backend desarrollado con Spring Boot**, encargado de gestionar la lógica de negocio y actuar como puente entre las aplicaciones cliente y la base de datos.

- **Tecnología**: Java con Spring Boot
- **Características principales**:
  - Endpoints RESTful
  - Gestión de usuarios, vehículos, y reservas
  - Seguridad y validación
  - Conexión con base de datos MySQL

### 📁 `DRCarsDesktop`
Contiene la **aplicación de escritorio desarrollada en C#** con **Visual Studio**, orientada a tareas administrativas o uso local por parte del personal autorizado.

- **Tecnología**: C# (.NET)
- **Características principales**:
  - Interfaz de escritorio amigable
  - Conexión directa con la API REST
  - Gestión local y remota de datos

### 📄 `BBDD.sql`
Archivo SQL que define la **estructura de la base de datos MySQL**, incluyendo la creación de tablas, relaciones, restricciones e índices necesarios para el funcionamiento del sistema.

---

## ⚙️ Requisitos

### General
- Git
- MySQL Workbench
- JDK 17+ (para Spring Boot)
- Node.js y npm (para Next.js)
- Visual Studio (para la app de escritorio)
