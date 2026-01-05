# 🧑‍💼 Sistema de Recursos Humanos – Full Stack Java & React

Aplicación **Full Stack** para la gestión de Recursos Humanos, desarrollada con **Java + Spring Boot** en el backend y **React** en el frontend.  
El proyecto implementa una arquitectura moderna basada en **API REST + SPA**, siguiendo buenas prácticas de desarrollo y escalabilidad.

Proyecto realizado con fines educativos y de práctica profesional.

---

## 📐 Arquitectura del Proyecto

SistemasDeRecursosHumanosJAVA  
├── backend/        API REST - Java + Spring Boot  
│   ├── controller  
│   ├── service  
│   ├── repository  
│   └── model  
└── frontend/       SPA - React  
    ├── components  
    ├── pages  
    └── services  

Separación clara de responsabilidades.  
Arquitectura desacoplada.  
Comunicación mediante JSON.

---

## 🚀 Tecnologías Utilizadas

### Backend
- Java  
- Spring Boot  
- Spring Data JPA  
- Hibernate  
- Maven  
- MySQL / H2  

### Frontend
- React  
- JavaScript (ES6+)  
- HTML5  
- CSS3  
- Axios  

---

## ⚙️ Requisitos Previos

- Java JDK 17 o superior  
- Maven  
- Node.js + npm  
- MySQL (opcional)  
- Git  

---

## 🔧 Instalación y Ejecución

### Clonar el repositorio

git clone https://github.com/JM29R/SistemasDeRecursosHumanosJAVA.git  
cd SistemasDeRecursosHumanosJAVA  

---

### Backend (Spring Boot)

cd backend  
mvn spring-boot:run  

El backend se ejecuta en:  
http://localhost:8080  

Configuración de base de datos en application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/rrhh  
spring.datasource.username=usuario  
spring.datasource.password=contraseña  

spring.jpa.hibernate.ddl-auto=update  
spring.jpa.show-sql=true  

---

### Frontend (React)

cd frontend  
npm install  
npm start  

El frontend se ejecuta en:  
http://localhost:3000  

---

## 🔗 Comunicación Frontend – Backend

El frontend consume la API REST del backend mediante Axios.

Ejemplo de endpoint:  
GET http://localhost:8080/api/empleados  

---

## 📚 Funcionalidades

- Gestión de empleados  
- Alta, baja y modificación  
- Listado de registros  
- API REST estructurada  
- Interfaz web interactiva  

---

## 👤 Autor

Juan Manuel Ríos  
Desarrollador Back-End Java  
GitHub: https://github.com/JM29R  

---

## ⭐ Objetivo del Proyecto

Demostrar conocimientos en:
- Programación orientada a objetos  
- Desarrollo backend con Java y Spring Boot  
- Consumo de APIs REST  
- Desarrollo frontend con React  
- Arquitectura Full Stack
