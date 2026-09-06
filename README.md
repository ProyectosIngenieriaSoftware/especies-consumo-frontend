# Plantas Consumo - Frontend

Repositorio oficial para el componente de **Frontend** del proyecto **Plantas de Consumo Humano** dentro de la organización **Proyectos Ingeniería de Software**.

---

## 📌 Descripción del Proyecto
Este repositorio contiene la interfaz de usuario web y diseño responsivo para la exploración, consulta e interacción de usuarios con el catálogo de plantas de consumo humano no tradicionales.

---

## 🌿 Flujo de Ramas y Entornos
- `main`: Rama de producción (protegida). Requiere revisión y aprobación obligatoria del equipo **DevOps** (Code Owners) mediante Pull Request.
- `qa`: Rama para pruebas y control de calidad (protegida). Requiere aprobación previa de pruebas (equipo **QA**) mediante Pull Request.
- `develop`: Rama principal de integración continua y desarrollo activo.

---

## 👥 Equipos y Responsabilidades
- **DevOps (`@ProyectosIngenieriaSoftware/devops`)**: Administración de infraestructura y custodia del despliegue en `main`.
- **QA (`@ProyectosIngenieriaSoftware/qa`)**: Certificación de interfaz, experiencia de usuario y aprobación de PRs hacia `qa`.
- **Frontera Web & Experiencia Móvil**: Desarrollo activo de componentes visuales y Pull Requests hacia `develop`.

---

## 📋 Guía para Desarrolladores
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/ProyectosIngenieriaSoftware/plantas-consumo-frontend.git
   ```
2. Crear una nueva rama a partir de `develop`:
   ```bash
   git checkout develop
   git pull origin develop
   git checkout -b feature/nombre-componente
   ```
3. Subir cambios y abrir Pull Request hacia `develop`:
   ```bash
   git push -u origin feature/nombre-componente
   ```