# Proyecto: EBFPC - Análisis y Gestión del Fútbol Colombiano

## Descripción
EBFPC es una aplicación web diseñada para ofrecer información organizada y herramientas de análisis sobre el fútbol colombiano. El proyecto busca facilitar el acceso a datos relevantes como resultados, clasificaciones, videos de goles y herramientas interactivas como la calculadora de ascenso y descenso.

## Tecnologías Utilizadas
- **HTML, CSS y JavaScript**: Para la estructura, estilos y funcionalidades de la aplicación.
- **Firebase**: Para el manejo de autenticación de usuarios y almacenamiento de datos.
- **Hosting**: Se utilizará un servicio gratuito para desplegar la aplicación.
- **YouTube API**: Para la integración de videos de goles.

## Estructura del Proyecto
```
Proyecto-de-grado/
│── index.html           # Página de inicio de sesión (Login)
│── home.html            # Página principal después de iniciar sesión
│── contacto.html        # Página de contacto
│── registro.html        # Página de registro
│
├── css/                 # Archivos de estilos
│   ├── styles.css       # Estilos generales
│   ├── styleshome.css   # Estilos específicos para la página principal
│
├── js/                  # Archivos de scripts
│   ├── login.js         # Lógica de inicio de sesión
│   ├── registro.js      # Lógica de registro
│
├── pages/               # Otras páginas de información
│   ├── info1.html       # Página de información sobre la Liga Colombiana
│   ├── info2.html       # Calculadora de Ascenso y Descenso
│   ├── info3.html       # Sistemas de Ascenso
│   ├── info4.html       # Videos de Goles del FPC
│
├── assets/              # Recursos como imágenes o documentos
│   ├── img/             # Carpeta para imágenes
│   ├── docs/            # Carpeta para documentos PDF, etc.
│
└── README.md            # Información del proyecto
```

## Funcionalidades
- **Autenticación de Usuarios**: Registro e inicio de sesión con Firebase.
- **Calculadora de Ascenso y Descenso**: Herramienta interactiva para proyectar posibles escenarios.
- **Videos de Goles**: Sección con los mejores goles de la Liga Colombiana.
- **Sistemas de Ascenso**: Explicación del formato y regulaciones para ascender a la Liga BetPlay.
- **Página de Contacto**: Para recibir retroalimentación de los usuarios.

## Instalación y Uso
1. Clonar el repositorio:
   ```sh
   git clone https://github.com/tuusuario/proyecto-ebfpc.git
   ```
2. Abrir el archivo `index.html` en un navegador.
3. Configurar Firebase en el archivo `js/login.js` y `js/registro.js` con tus credenciales.
4. Subir el proyecto a un hosting gratuito (ej. Firebase Hosting, GitHub Pages, 000webhost, etc.).

## Contribución
Si deseas contribuir, por favor abre un issue o envía un pull request con mejoras.

## Licencia
Este proyecto se encuentra bajo la licencia MIT.

