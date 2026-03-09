# Logistica Global LTDA 🚚✈️

Proyecto académico desarrollado durante **2025** para la **Evaluación 3 de Backend**.

Este sistema representa una **empresa ficticia de logística y transporte** llamada *Logistica Global LTDA*, enfocada en la gestión de operaciones terrestres y aéreas.

## 👥 Autores

- Matías Gajardo Castillo
- Jean Pierre Avastia

Trabajo realizado en conjunto como parte del proceso formativo en desarrollo backend.

## 🧩 Descripción del proyecto

La aplicación permite administrar los procesos principales de una operación logística moderna:

- Gestión de clientes
- Registro de vehículos y aeronaves
- Administración de conductores y pilotos
- Definición de rutas terrestres y aéreas
- Control de cargas
- Creación y seguimiento de despachos

Además de la parte de gestión, el proyecto incluye una interfaz web con diseño responsive y una API REST documentada con Swagger para pruebas y consumo de endpoints.

## ✨ Características principales

- CRUD completo para módulos de negocio
- API REST con Django REST Framework
- Documentación interactiva en Swagger y Redoc
- Filtros en módulos clave (por ejemplo, rutas y cargas)
- Interfaz web con plantillas Django + Bootstrap

## 🛠️ Stack tecnológico

- Python 3.13
- Django 5.2
- Django REST Framework
- drf-yasg (Swagger / Redoc)
- HTML, CSS, JS, Bootstrap

## 🗂️ Módulos del sistema

- `Clientes`
- `Vehículos`
- `Aeronaves`
- `Conductores`
- `Pilotos`
- `Rutas`
- `Cargas`
- `Despachos`

## 🚀 Puesta en marcha local

1. Clonar el repositorio.
2. Entrar a la carpeta del proyecto.
3. Crear y activar entorno virtual.
4. Instalar dependencias.
5. Aplicar migraciones.
6. Iniciar servidor.

Comandos sugeridos en Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Abrir en navegador:

- `http://127.0.0.1:8000/` (sitio web)
- `http://127.0.0.1:8000/swagger/` (documentación Swagger)
- `http://127.0.0.1:8000/redoc/` (documentación Redoc)

## ☁️ Despliegue

Como parte del trabajo académico, el proyecto también fue llevado a un entorno de despliegue en **AWS** durante la evaluación.

## 🎯 Contexto académico

Este repositorio conserva una entrega importante del curso para poder revisar decisiones, estructura y avances logrados en su momento.

En resumen: una base sólida de backend con enfoque práctico en logística, desarrollada en equipo y con valor como referencia para proyectos futuros.
