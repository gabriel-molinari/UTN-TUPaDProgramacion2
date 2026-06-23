# UTN-TUPaDProgramacion2

# Sistema de Gestión Comercial (Consola)

Este proyecto consiste en una aplicación de consola robusta desarrollada en Java 21 que simula la operación de un sistema comercial, permitiendo la gestión completa (CRUD) de productos, categorías, usuarios y el procesamiento de pedidos con cálculo de totales.

El foco principal del proyecto está en el diseño y las buenas prácticas, implementando una estructura organizada en capas y persistencia memoria a través del Java Collections Framework, prescindiendo por completo de motores de bases de datos externos.

## 🚀 Requisitos Mínimos

Antes de ejecutar la aplicación, asegúrate de contar con los siguientes componentes instalados en tu equipo:

* **Java Development Kit (JDK) 21** o superior.
* Un entorno de desarrollo (IDE) como *IntelliJ IDEA*, *NetBeans* o *Eclipse*.
* **Git** (Para clonar el repositorio).

---

## 🛠️ Estructura del Proyecto (Capas)

El código fuente se encuentra modularizado en los siguientes paquetes bajo criterios de alta cohesión y bajo acoplamiento:
* `base`: Clase abstracta base para reutilización de ID y borrado lógico.
* `config`: Centralización del arranque y vinculación de dependencias por *setters*.
* `entities`: Modelos puros del dominio del negocio.
* `enums`: Tipificados fijos del sistema (Roles de acceso).
* `exception`: Excepciones personalizadas para el control fino de reglas de negocio.
* `interfaces`: Contratos de comportamiento del sistema (e.g., `Calculable`).
* `main`: Punto de entrada de la aplicación (`Main.java`).
* `service`: Capa de lógica de negocio y administración de colecciones (`HashMap`/`ArrayList`).
* `ui`: Interfaz de usuario por consola y capturadores de inputs.
* `util`: Componentes auxiliares y validadores globales de datos.

---

## 💻 Ejecución del Proyecto

Para compilar y ejecutar la aplicación, seguí estos pasos según tu preferencia:

*Abrí tu IDE de preferencia.

*Seleccioná la opción Open o Import Project y elegí la carpeta raíz del repositorio.

*Asegurate de que el IDE tenga configurado el JDK 21 en los settings del proyecto (Project Structure).

*Buscá el archivo Main.java dentro del paquete main, hacé clic derecho y seleccioná Run File.


/*********************************/

Link de Youtube de la presentación: https://youtu.be/VE2kflHTk24




