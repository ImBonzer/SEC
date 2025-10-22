# Sistema para la Generación Automática de Constancias Escolares

Este proyecto tiene como finalidad facilitar la creación de constancias escolares dentro de una institución educativa.  
A menudo, el proceso de elaborar constancias es lento y se hace manualmente, lo que genera errores y pérdida de tiempo.  
Con este sistema, buscamos automatizar esa tarea, permitiendo generar constancias en PDF a partir de una plantilla base y los datos del alumno.  

El objetivo es ofrecer una herramienta práctica, rápida y confiable para secretarías, coordinaciones o departamentos académicos que constantemente emiten documentos de este tipo.

---

## ¿Qué hace este sistema?

- Permite crear constancias personalizadas a partir de un formato base en PDF.  
- Genera archivos automáticamente llenando los campos con la información de cada alumno.  
- Puede añadir firmas digitales para validar la autenticidad (en futuras versiones).  
- Guarda un registro histórico de constancias emitidas.  
- Se puede usar por consola o con una interfaz web (si se implementa Flask).

---

## Tecnologías utilizadas

Este proyecto fue desarrollado principalmente con Python, por su facilidad para manejar archivos PDF y su amplia comunidad de soporte.  

**Lenguajes y herramientas:**

| Categoría | Tecnología | Descripción |
|------------|-------------|-------------|
| Lenguaje principal | Python | Lógica del sistema y generación de PDFs |
| Librerías clave | ReportLab, PyPDFForm, Pillow, qrcode | Creación de PDFs, edición de plantillas y generación de códigos QR |
| Base de datos (opcional) | SQLite | Para guardar información de alumnos y constancias |
| Frontend (opcional) | HTML, CSS, JavaScript | Para la interfaz web si se desarrolla |
| Control de versiones | Git / GitHub | Para el trabajo colaborativo y registro del progreso |

---