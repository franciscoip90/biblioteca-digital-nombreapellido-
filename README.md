# biblioteca-digital-nombreapellido-
Tarea Integradora: Desarrollar una aplicación en Python utilizando el paradigma de programación orientada a objetos, que permita gestionar una biblioteca digital con funcionalidades CRUD, consumo de APIs externas y almacenamiento seguro de datos en una base de datos. El proyecto debe ser entregado en un repositorio público de GitHub.


Requisitos del Proyecto:
1. Diseño y Modelado (UML)
•	Crear un diagrama de clases UML que represente las entidades principales del sistema: Libro, Prestamo, Usuario, etc.
•	Incluir el diagrama en el repositorio (/docs/diagrama_clases.png o .pdf).
2. Programación Orientada a Objetos
•	Implementar las clases en Python aplicando:
•	Herencia
•	Encapsulamiento
•	Polimorfismo
•	Organizar el código en módulos y carpetas (/models, /controllers, etc.).
3. Base de Datos
•	Conectar la aplicación a una base de datos (SQLite).
•	Usar librerías oficiales como sqlite3.
•	Implementar operaciones CRUD para las entidades principales.
4. Consumo de API Externa
•	Integrar una API pública (ej. Google Books API) para buscar libros.
•	Deserializar la respuesta en JSON.
•	Permitir registrar libros obtenidos desde la API en la base de datos.
5. Manejo de Errores
•	Implementar manejo de excepciones para errores comunes.
•	Mostrar mensajes claros al usuario.

Estructura del Repositorio en GitHub:
Pueden clonar el repositorio desde 
 biblioteca-digital/
├── models/
├── controllers/
├── database/
├── api/
├── docs/
│   └── diagrama_clases.png
├── 📄 main.py
├── 📄 requirements.txt
├── 📄 README.md
└── 📄 .gitignore



Entregables en GitHub:
1.	Código fuente completo y funcional.
2.	Diagrama de clases UML en /docs.
3.	Script SQL para crear la base de datos en /database.
4.	Archivo README.md con:
•	Descripción del proyecto
•	Instrucciones de instalación y ejecución
•	Librerías utilizadas
