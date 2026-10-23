# Gestión logística y transporte

Sistema web académico para la administración de operaciones logísticas terrestres y aéreas, desarrollado con Django y Django REST Framework.

Proyecto académico desarrollado durante **2025** para la **Evaluación 3 de Backend**.

## Autores

- Matías Gajardo
- Jean Pierre Avastia

Proyecto realizado en equipo como parte del proceso formativo en desarrollo backend.

## Descripción del proyecto

La aplicación representa una empresa ficticia de logística y transporte llamada *Logística Global LTDA*. Permite administrar procesos relacionados con clientes, recursos de transporte, cargas y despachos.

El sistema incluye:

- Gestión de clientes.
- Registro de vehículos y aeronaves.
- Administración de conductores y pilotos.
- Definición de rutas terrestres y aéreas.
- Control de cargas.
- Creación y seguimiento de despachos.

Además, incorpora una interfaz web responsive y una API REST documentada mediante Swagger y ReDoc.

## Características principales

- Operaciones CRUD para los módulos de negocio.
- API REST desarrollada con Django REST Framework.
- Documentación interactiva mediante Swagger y ReDoc.
- Filtros en módulos relevantes, como rutas y cargas.
- Interfaz web basada en plantillas Django y Bootstrap.

## Tecnologías

- Python 3.13
- Django 5.2
- Django REST Framework
- drf-yasg
- HTML, CSS y JavaScript
- Bootstrap

## Módulos del sistema

- Clientes
- Vehículos
- Aeronaves
- Conductores
- Pilotos
- Rutas
- Cargas
- Despachos

## Puesta en marcha local

### 1. Clonar el repositorio

```powershell
git clone <url-del-repositorio>
cd <nombre-del-repositorio>
```

### 2. Crear y activar el entorno virtual

```powershell
python -m venv .venv
.\.venv\Scripts\activate
```

### 3. Instalar dependencias

```powershell
pip install -r requirements.txt
```

### 4. Aplicar migraciones

```powershell
python manage.py migrate
```

### 5. Iniciar el servidor

```powershell
python manage.py runserver
```

## Rutas principales

| Ruta | Descripción |
|------|-------------|
| `http://127.0.0.1:8000/` | Sitio web de la aplicación |
| `http://127.0.0.1:8000/swagger/` | Documentación Swagger |
| `http://127.0.0.1:8000/redoc/` | Documentación ReDoc |

## Despliegue

Como parte del trabajo académico, el proyecto fue llevado a un entorno de despliegue en **AWS** durante la evaluación. La versión disponible en este repositorio está orientada a la ejecución y revisión local.

## Alcance académico

Este repositorio corresponde a una implementación académica funcional de alcance introductorio-intermedio. Su objetivo fue aplicar fundamentos de backend, modelado de entidades, operaciones CRUD, APIs REST y documentación de servicios en un dominio logístico.
