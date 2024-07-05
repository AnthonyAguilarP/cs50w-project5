# Proyecto E-Learning

## Descripción

Este proyecto es una plataforma de E-Learning desarrollada utilizando Django como framework principal para el backend, PHP para la creación de APIs y Vite para el desarrollo de un editor de código integrado en el sistema web. La plataforma permite la gestión de cursos, tareas, archivos, inscripciones y proporciona un sistema de sugerencias y reportes. Además, incluye funcionalidades avanzadas como la creación y contestación de preguntas relacionadas con las tareas, así como la gestión de notas.

## Características

- **Gestión de usuarios:** Registro, autenticación y autorización de usuarios con roles personalizados.
- **Gestión de cursos:** Creación, edición y eliminación de cursos.
- **Gestión de tareas:** Asignación de tareas a los cursos con diferentes tipos de contenido (archivos y respuestas).
- **Subida de archivos:** Los estudiantes pueden subir archivos como parte de sus tareas.
- **Sistema de inscripción:** Inscripción y finalización de cursos por parte de los estudiantes.
- **Sistema de preguntas y respuestas:** Creación de preguntas para las tareas y contestación de las mismas por parte de los estudiantes.
- **Sistema de sugerencias y reportes:** Los usuarios pueden enviar sugerencias y reportes.
- **Gestión de notas:** Evaluación y calificación de tareas por parte de los profesores.
- **Editor de código:** Integración de un editor de código utilizando Vite.

## Tecnologías Utilizadas

- **Backend:** Django, Python, PHP
- **Frontend:** HTML, CSS, JavaScript, Vite
- **Base de datos:** SQLite (puede ser cambiada a PostgreSQL, MySQL, etc.)
- **Autenticación y Autorización:** Sistema de autenticación incorporado de Django
- **APIs:** PHP para la creación de endpoints personalizados

## Estructura del Proyecto

### Modelos (models.py)

- **Usuario:** Modelo personalizado de usuario con roles y permisos.
- **Sugerencia:** Modelo para gestionar las sugerencias de los usuarios.
- **Reporte:** Modelo para gestionar los reportes de los usuarios.
- **Curso:** Modelo para gestionar los cursos.
- **Tarea:** Modelo para gestionar las tareas de los cursos.
- **Archivo:** Modelo para gestionar los archivos subidos por los estudiantes.
- **Inscripción:** Modelo para gestionar las inscripciones de los estudiantes a los cursos.
- **Pregunta:** Modelo para gestionar las preguntas relacionadas con las tareas.
- **Contestación:** Modelo para gestionar las respuestas a las preguntas.
- **Notas:** Modelo para gestionar las notas de las tareas.

### Vistas (views.py)

- **User Views:** Vistas para gestionar la creación, edición y eliminación de usuarios.
- **Course Views:** Vistas para gestionar la creación, edición y eliminación de cursos.
- **Task Views:** Vistas para gestionar la creación, edición y eliminación de tareas.
- **File Views:** Vistas para la subida y gestión de archivos.
- **Inscription Views:** Vistas para gestionar las inscripciones.
- **Question Views:** Vistas para la creación y gestión de preguntas.
- **Answer Views:** Vistas para la contestación de preguntas.
- **Grade Views:** Vistas para la evaluación y gestión de notas.

### Estilos (styles.css)

El archivo `styles.css` contiene todos los estilos necesarios para la presentación del sitio web. Este archivo se encuentra en la ruta `static/styles.css`.

### Configuración de Vite

Vite se utiliza para la creación de un editor de código integrado en el sistema web. La configuración de Vite se encuentra en el archivo `vite.config.js` en el directorio raíz del proyecto.

## Instalación

### Clonar el repositorio:

```bash
git clone https://github.com/tu-usuario/proyecto-elearning.git
extrae el proyecto .rar por que es pesado
cd proyecto-elearning
Configuración del entorno:
Configurar el servidor PHP: Justo en el directorio donde se encuentra manage.py, utiliza un servidor o algún plugin que ejecute PHP. En mi caso, hago clic derecho sobre cualquier archivo PHP y selecciono "Run Server", lo que ejecuta el servidor en el puerto 3000 y permite usar las APIs PHP.

Ejecutar Vite:

bash
Copiar código
cd carpeta-donde-se-encuentra-vite
npm run dev
Ejecutar Django:

bash
Copiar código
cd directorio-donde-se-encuentra-manage.py
python manage.py runserver
Funcionalidades adicionales:
Editor de código HTML, CSS, JS
Editor de PDF
Creación y administración de cursos
Administración por roles
Gráficas de análisis de información básica de estudiantes
Boleta de información de notas
Páginas para balances generales
Calculadora IMC
Calculadora
Calculadora de IR para Nicaragua
Visualizador de .docx que convierte .docx a HTML para visualizar en la web
Buen diseño UI y excelente experiencia de usuario (UX)
¡Listo! Ahora puedes usar la página con todas las funcionalidades descritas, desde el editor de código hasta la gestión completa de cursos y tareas.
