# OmniManageAPI

OmniManageAPI es una API REST multifuncional desarrollada con Spring Boot, diseñada para consolidar diversas herramientas y servicios en un solo proyecto. Este proyecto tiene como objetivo proporcionar una base unificada y extensible que facilita la gestión de múltiples dominios de aplicación, permitiendo la escalabilidad hacia una arquitectura de microservicios en el futuro.

## Licencia

Este proyecto está bajo la **Licencia Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)**. Puedes descargar y utilizar el proyecto para fines académicos siempre y cuando se mantenga el crédito adecuado.

**No se permite:**
- Modificar, transformar, o construir a partir de este trabajo.
- Usar el proyecto para fines comerciales.
- Distribuir el proyecto para fines comerciales.
- Reutilizar partes del código en otros proyectos de índole personal o comercial.

Para más detalles sobre la licencia, consulta el archivo [LICENSE](LICENSE) en este repositorio.

## Cómo Contribuir

Si deseas contribuir a este proyecto, por favor, consulta el archivo [CONTRIBUTING.md](CONTRIBUTING.md) para obtener más detalles sobre cómo puedes hacerlo.

## Contacto

Para cualquier consulta o información adicional, puedes ponerte en contacto con [lgzarturo@gmail.com](mailto:lgzarturo@gmail.com).

## Descripción del Proyecto

**OmniManageAPI** es una API RESTful multifuncional desarrollada con Spring Boot, diseñada para consolidar diversas herramientas y servicios en un solo proyecto. Este proyecto tiene como objetivo proporcionar una base unificada y extensible que facilita la gestión de múltiples dominios de aplicación, permitiendo la escalabilidad hacia una arquitectura de microservicios en el futuro.

### Características Principales

1. **Gestión de Proyectos y Estimación de Tiempos**:
    - Permite la gestión de proyectos, tareas y recursos.
    - Incluye herramientas para la estimación de tiempos y la planificación de proyectos.

2. **Herramientas para Desarrolladores**:
    - Proporciona utilidades y servicios para apoyar el desarrollo de software.
    - Incluye APIs para la gestión de herramientas y utilidades comunes.

3. **Portal de Videojuegos**:
    - Gestión de videojuegos y plataformas.
    - Servicios para la creación y administración de catálogos de juegos.

4. **Planificador de Gastos Personales**:
    - Registro y seguimiento de ingresos y egresos.
    - Herramientas de análisis financiero y proyección de gastos.

5. **Gestión de Suscripciones**:
    - Administración de suscripciones a servicios como Netflix, Amazon Prime, etc.
    - Notificaciones y recordatorios para la gestión de suscripciones.

6. **Scraper para Motor de Reservas**:
    - Listado de hoteles desde un motor de reservas.
    - API para generar sitios de promoción SEO orgánico y link building.

### Estructura del Proyecto

El proyecto está organizado en varios módulos que agrupan funcionalidades específicas, facilitando la futura migración a una arquitectura de microservicios. Cada módulo sigue una estructura estándar que incluye paquetes para dominios, repositorios, servicios, controladores y mapeadores.

#### Módulos Incluidos:

- **config**: Configuración de la aplicación, incluyendo seguridad y configuración web.
- **devtools**: Herramientas y utilidades para desarrolladores.
- **projectmanagement**: Gestión de proyectos y tareas.
- **videogames**: Administración de videojuegos y plataformas.
- **personalfinance**: Planificación y seguimiento de finanzas personales.
- **subscriptions**: Gestión de suscripciones a servicios.
- **bookingengine**: Scraping de hoteles y generación de sitios de promoción.
- **seopromotion**: SEO y link building.
- **util**: Utilidades comunes como DateUtil, StringUtil, y WebScraperUtil.

### Uso y Extensibilidad

El proyecto está diseñado para ser fácilmente extensible, permitiendo agregar nuevas funcionalidades y módulos según sea necesario. Utiliza DTOs para la comunicación entre servicios y controladores, y MapStruct para el mapeo de datos, garantizando una separación clara de responsabilidades y facilitando el mantenimiento del código.

### Dependencias y Compilación

El proyecto utiliza Maven para la gestión de dependencias y la compilación. Las utilidades comunes están empaquetadas en un módulo `common-utils`, que puede ser reutilizado en otros proyectos como una dependencia Maven (`com.lgzarturo.common-utils:0.0.1`).
