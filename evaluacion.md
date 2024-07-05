# Prueba Técnica para Maestro Angular
## Objetivo
- Desarrollar una aplicación Angular que gestione un sistema de gestión de proyectos, optimizando el rendimiento, aplicando técnicas avanzadas de lazy loading y asegurando la aplicación.

## Requisitos

### 1. Configuración Inicial

#### Descripción:
- Configura un nuevo proyecto Angular utilizando Angular CLI con SCSS como preprocesador de estilos y habilita el enrutamiento.

### 2. Estructura de la Aplicación
#### Descripción:
- Crea los siguientes módulos y componentes:

- CoreModule: Contendrá los servicios singleton y componentes compartidos a nivel de aplicación.
- SharedModule: Contendrá componentes, directivas y pipes reutilizables.
- ProjectsModule: Gestionará la funcionalidad relacionada con los proyectos.

### 3. Optimización del Rendimiento
#### Descripción:
- Implementa las siguientes técnicas de optimización del rendimiento:

- Lazy loading avanzado para módulos.
- Utiliza la estrategia de cambio de detección OnPush.
- Implementa PreloadAllModules para pre-cargar módulos cuando la aplicación esté inactiva.

### 4. Seguridad
#### Descripción:
- Implementa las siguientes características de seguridad:

- Guards para proteger rutas según la autenticación y los roles de usuario.
- Manejo de tokens JWT para autenticación.

### 5. Formularios Reactivos y Validaciones
#### Descripción:
- Implementa formularios reactivos con validaciones personalizadas y asíncronas.

### 6. Enrutamiento Avanzado
#### Descripción:
- Configura el enrutamiento en el módulo ProjectsModule para gestionar las rutas:

- /projects: Muestra el ProjectListComponent.
- /projects/:id: Muestra el ProjectDetailComponent para el proyecto seleccionado.
- /projects/new: Muestra el ProjectFormComponent para agregar un nuevo proyecto.
- /projects/edit/:id: Muestra el ProjectFormComponent para editar un proyecto existente.

### 7. Animaciones
#### Descripción:
- Añade animaciones a la lista de proyectos utilizando @angular/animations:

- Animaciones para agregar y eliminar proyectos de la lista.
- Animaciones de transición entre los componentes ProjectListComponent y ProjectDetailComponent.

### 8. Servicio para Obtener Proyectos
#### Descripción:
- Inyecta un servicio que simule una solicitud GET y llene la lista de proyectos con los datos obtenidos.