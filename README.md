[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/o5bhAvJH)


## Sistema web para el registro y facturación del transporte vehicular aprovechando la tecnología OCR en la Empresa Agropecuaria, Transportes y Comunicaciones El Huáscar S.A.C. en la región de San Martín en el año 2023.

El Sistema Web para la Empresa Agropecuaria, Transportes y Comunicaciones El Huáscar S.A.C. es una aplicación diseñada para facilitar la gestión de registros de vehículos mediante el uso del sistema OCR (Reconocimiento Óptico de Caracteres). Además, integra un sistema de autenticación basado en JSON Web Tokens (JWT) para garantizar un acceso seguro a los usuarios trabajadores.

### Arquitectura del sistema web - Stack MEAN
- Base de datos: MySQL
- BackEnd: Express
- FrontEnd: Angular
- RunTime: NodeJS

## FrontEndHuascar

### Descripción
Esta carpeta contiene el código fuente y los archivos relacionados con la interfaz de usuario de la aplicación.

### Tecnologías Utilizadas

- AngularCli@16.0.1
- HTML5
- SCSS
- TypeScript

### Estructura de Carpetas

- **src**: Contiene los archivos fuente de la aplicación.
  - **app**: Contiene la estructura de las carpetas de la aplicacion.
    - **layouts**: Contiene los componentes como el sidevar y el navbar superior.
    - **models**: Contiene el modelo de clases para mapear las apis.
    - **pages**: Contiene los componentes de interfaz de usuario.
    - **services**: Contiene los servicios de la aplicacion.
  - **assets**: Contiene los archivos de diseño y recursos para la aplicacion.

### Comandos Disponibles
- `ng serve`: Inicia la aplicación en modo de desarrollo.

## Backend

### Descripción
Esta carpeta contiene el código fuente y los archivos relacionados con la lógica del servidor y la gestión de datos de la aplicación.

### Tecnologías Utilizadas
- Node.js
- Express.js
- MySQL
- OCR

### Estructura de Carpetas

- **src**: Contiene los archivos fuente del servidor.
  - **config**: Contiene la configuracion general de la aplicacion.
  - **Controllers**: Controllers de la aplicacion para cada entidad.
  - **database**: Conexion a la base de datos.
  - **pruebas**: Test de la funcion OCR.
  - **public**: Carpeta de acceso publico.
  - **routes**: Definicion de rutas para la api.

### Configuración y Uso
1. Instala las dependencias: `npm install`
2. Configura las variables de entorno en un archivo `.env`.
3. Inicia el servidor: `npm run dev`

### Comandos Disponibles
- `npm run dev`: Inicia el servidor.
- `npm test`: Ejecuta las pruebas de la aplicación.
