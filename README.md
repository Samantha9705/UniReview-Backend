# UniReview - Backend

Este repositorio contiene el backend de **UniReview**, una plataforma colaborativa donde estudiantes y postulantes pueden buscar y compartir reseñas sobre carreras universitarias en México.

This repository contains the backend for **UniReview**, a collaborative platform where students and applicants in Mexico can search and share reviews about university degrees.

---

## ⚙️ Tecnologías utilizadas | Technologies Used

- Java 17
- Spring Boot
- Spring Data JPA
- Gradle (build tool 🐘)
- MySQL (base de datos en repositorio separado)
- Postman (para pruebas de endpoints)
- Spring Security + JWT

---

## 📌 Funcionalidades principales | Main Features

- Registro y autenticación de usuarios
- Gestión de roles: postulante, estudiante, administrador
- Publicación, edición y eliminación de reseñas
- Búsqueda por carrera, universidad o categoría
- Validación de datos y manejo de errores

---

## 🧱 Estructura general | Project Structure

```bash
/
├── src/
│   ├── main/
│   │   ├── java/com/unireview/
│   │   │   ├── controller/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   ├── service/
│   │   │   └── config/
│   │   └── resources/
│   │       └── application.properties
├── build.gradle
├── settings.gradle

---

🧪 Pruebas de API | API Testing
Las pruebas de los endpoints fueron realizadas con Postman.
Postman was used to test the API endpoints.

---

🗃️ Base de datos | Database
La estructura y scripts de la base de datos están disponibles en este repositorio:
📦 unireview-database

---

🌐 Conexión con frontend
Este backend expone una API RESTful que es consumida por el frontend de UniReview.
This backend exposes a RESTful API consumed by the UniReview frontend.

---

📄 Licencia | License
Uso académico y personal únicamente.
Academic and personal use only.

