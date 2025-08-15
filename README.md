# 📚 Challenge Literatura Alura/Oracle
Una aplicación de consola desarrollada en Java con Spring Boot que permite buscar, registrar y gestionar libros y autores utilizando la API de Gutendex. Este proyecto forma parte del programa Oracle ONE - Alura LATAM.

## 🎯 Características Principales

- 🔍 Búsqueda de libros por título utilizando la API de Gutendex
- 📋 Listado completo de libros registrados en la base de datos
- 👥 Gestión de autores con información detallada
- 📅 Filtrado de autores por año de vida
- 🌐 Filtrado de libros por idioma
- 💾 Persistencia de datos con PostgreSQL
- 🔄 Integración con API externa para obtener información actualizada

## 🛠️ Tecnologías utilizadas

<p align="center">
  <img src="https://img.icons8.com/?size=100&id=13679&format=png&color=000000" alt="JAVA" width="80"/>
  <img src="https://img.icons8.com/?size=100&id=90519&format=png&color=000000" alt="SpringBoot" width="80"/>
  <img src="https://img.icons8.com/?size=100&id=JRnxU7ZWP4mi&format=png&color=000000" alt="PostgreSQL" width="80"/>
  <img src="https://img.icons8.com/?size=100&id=DuPGo_P_q_-x&format=png&color=000000" alt="Jackson Json" width="80"/>
  <img src="https://img.icons8.com/?size=100&id=t5FJr3NzrPSm&format=png&color=000000" alt="Maven" width="80"/>
</p>

- Java 17+
- Spring Boot 3.3.5
- Spring Data JPA
- PostgreSQL
- Jackson (para procesamiento JSON)
- Maven (gestión de dependencias)
- Gutendex API (fuente de datos de libros)

## 📋 Requisitos Previos
Antes de ejecutar el proyecto, asegúrate de tener instalado:

- ✅ Java 17 o superior
- ✅ PostgreSQL
- ✅ Maven (opcional, se incluye wrapper)
- ✅ Git

## ⚙️ Configuración del Proyecto
1. Clonar el repositorio
```bash git clone https://github.com/tu-usuario/challenge-literatura-alura.git
cd challenge-literatura-alura
```
2. Configurar la base de datos
Crea una base de datos PostgreSQL y configura las siguientes variables de entorno:
```bash export DB_HOST=localhost:5432
export DB_NAME=literatura_db
export DB_USER=tu_usuario
export DB_PASSWORD=tu_contraseña
```

## 🚀 Uso de la Aplicación
Una vez ejecutada la aplicación, verás el siguiente menú interactivo:
```
---------------------
Ingrese una opcion:

1 - Buscar libro por titulo
2 - Listar libros registrados
3 - Listar autores registrados
4 - Listar autores vivos en un determinado año
5 - Listar libros por idioma
0 - Salir
```

## 📖 Funcionalidades Detalladas
1. Buscar libro por título
- Permite buscar libros en la API de Gutendx por título
- Guarda automáticamente el libro y autor en la base de datos
- Evita duplicados de autores

2. Listar libros registrados
- Muestra todos los libros almacenados en la base de datos local
- Incluye información del título, tema, idioma y autor

3. Listar autores registrados
- Presenta todos los autores con sus años de nacimiento y muerte
- Información completa de cada autor registrado

4. Listar autores vivos en un año específico
- Filtra autores que estuvieron vivos en un año determinado
- Considera tanto el año de nacimiento como el de muerte

5. Listar libros por idioma
- Filtra libros según el idioma especificado
- Soporta códigos de idioma estándar (es, en, fr, etc.)

## 🔧 API Externa
Este proyecto consume la API de *Gutendx* para obtener información de libros:

. URL Base: https://gutendx.com/
- Endpoint utilizado: /books/?search={titulo}
- Formato: JSON

## 📸 Capturas de Pantalla

### Menú Principal
<img width="1920" height="320" alt="image" src="https://github.com/user-attachments/assets/25a27fb4-4bf8-4ec8-83e4-58128ca5a709" />

### Búsqueda de Libros
<img width="1920" height="500" alt="image" src="https://github.com/user-attachments/assets/52e245a9-34d6-4bcd-8f1a-238441c82710" />

### Listado de Autores
<img width="1920" height="500" alt="image" src="https://github.com/user-attachments/assets/57c5b5f7-e61f-40cb-8e5e-c945c512ae22" />

## 👨‍💻 Autor
Carlos Ramírez Wong

- GitHub: @CarlosRW
- LinkedIn: www.linkedin.com/in/carlosrw

## 🙌 Agradecimientos

- Oracle ONE y Alura LATAM por proporcionar este desafío
- Gutendx por su API gratuita de libros
- La comunidad de Spring Boot por la excelente documentación

---
⭐ ¡No olvides darle una estrella al proyecto si te ha sido útil! ⭐

