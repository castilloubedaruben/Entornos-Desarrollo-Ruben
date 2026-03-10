- [📂 Estructura del proyecto](#-estructura-del-proyecto)
- [⚙️ Métodos implementados](#️-métodos-implementados)
  - [Creación de entidades](#creación-de-entidades)
  - [Generación automática de códigos](#generación-automática-de-códigos)
  - [Gestión de horarios](#gestión-de-horarios)
- [📌 Conclusión](#-conclusión)

# 📂 Estructura del proyecto

La estructura del proyecto sigue una organización clara separando las diferentes responsabilidades del sistema.

```
src
 └─ main
     └─ java
         └─ com.cine
             ├─ model
             │   ├─ Pelicula.java
             │   └─ Proyeccion.java
             │
             ├─ service
             │   └─ CineService.java
             │
             └─ CineApplication.java
```

Esta estructura facilita:

- Mantener el código organizado
- Separar responsabilidades
- Escalar el proyecto fácilmente



# ⚙️ Métodos implementados

Los métodos para la gestion correcta del sistema son los siguientes:

## Creación de entidades

Permiten crear nuevas instancias de:

- Películas
- Proyecciones

Esto facilita la gestión dinámica del cine.

---

## Generación automática de códigos

Para identificar cada proyección se genera un código único con un prefijo.

Ejemplo:

```
P-1
P-2
P-3
```

Esto evita duplicados y facilita la identificación de cada sesión.

---

## Gestión de horarios

Se utilizan objetos `LocalDateTime` para trabajar con fechas y horas.

Esto permite:

- Establecer hora de inicio
- Calcular la hora de finalización
- Organizar correctamente las proyecciones


# 📌 Conclusión

Este proyecto ha permitido aplicar conceptos fundamentales del desarrollo en Java como:

- **Programación Orientada a Objetos**
- **Relaciones entre clases**
- **Gestión de dependencias con Maven**
- **Estructuración de proyectos con Spring Boot**
- **Documentacion de los metodos para su correcta utilización**
- **Creacion de un Readme ordenado y claro orientado a futuros proyectos personales**
