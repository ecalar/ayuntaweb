# AyuntaWeb 🏛️

Plataforma web para conectar ciudadanos con su ayuntamiento. Gestión de incidencias, trámites y comunicación municipal.

## 🚀 Stack Tecnológico

- **Backend**: Java 17, Spring Boot 3.x, Spring Security, JPA
- **Base de datos**: PostgreSQL 16
- **Testing**: JUnit 5, Mockito, Testcontainers
- **DevOps**: Docker, GitHub Actions

## 📋 Estado del Proyecto

| Fase | Estado | Descripción |
|------|--------|-------------|
| MVP | 🚧 En desarrollo | Funcionalidades básicas |
| Avanzado | 📝 Planeado | Trámites y notificaciones |
| Producción | ⏳ Pendiente | Despliegue y monitoreo |

## 🛠️ Desarrollo Local

### Requisitos
- Java 17+
- Docker y Docker Compose
- Maven 3.8+

### Instalación

```bash
# 1. Clonar repositorio
git clone https://github.com/TU_USUARIO/ayuntaweb.git
cd ayuntaweb

# 2. Levantar PostgreSQL
docker-compose up -d

# 3. Compilar y ejecutar
./mvnw spring-boot:run

📚 Documentación

    Documentación de la API (cuando esté disponible)

    Guía de contribución

📄 Licencia

Este proyecto está bajo la licencia MIT. Ver LICENSE para más detalles.


---

## 💾 Paso 6: Hacer commit y push

```bash
# Ver qué archivos han cambiado
git status

# Añadir todos los archivos nuevos
git add .

# Ver qué se va a commitear
git status

# Crear commit con mensaje descriptivo
git commit -m "feat: configuración inicial del proyecto Spring Boot

- Añadidas dependencias principales (Web, JPA, Security, Validation)
- Configurado docker-compose con PostgreSQL 16
- Creada estructura de paquetes base
- Configurado application.yml para desarrollo
- Actualizado README con información del proyecto

Closes #1"

# Subir la rama a GitHub
git push -u origin feature/setup-inicial
