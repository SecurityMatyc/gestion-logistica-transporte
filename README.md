# Gestión logística y transporte

Sistema web académico para la administración de operaciones logísticas terrestres y aéreas, desarrollado con Django y Django REST Framework.

Proyecto desarrollado durante **2025** para la **Evaluación 3 de Backend**.

## Estado del proyecto

Implementación académica funcional de alcance introductorio-intermedio. El sistema representa una base de gestión logística con módulos de clientes, recursos de transporte, cargas, rutas y despachos.

La versión disponible está orientada a la ejecución local y la revisión técnica. Como parte del trabajo académico, el proyecto también fue llevado a un entorno de despliegue en AWS durante la evaluación.

## Contexto y objetivo

La aplicación representa una empresa ficticia de logística y transporte llamada *Logística Global LTDA*.

El objetivo fue aplicar fundamentos de desarrollo backend para organizar procesos asociados a operaciones terrestres y aéreas, desde el registro de recursos y cargas hasta la creación y seguimiento de despachos.

## Autores

- Matías Gajardo
- Jean Pierre Avastia

Proyecto realizado en equipo como parte del proceso formativo en desarrollo backend.

## Flujo general de operación

1. Se registran clientes y recursos de transporte disponibles.
2. Se incorporan vehículos, aeronaves, conductores y pilotos.
3. Se definen rutas terrestres o aéreas.
4. Se registran y asocian cargas a una operación logística.
5. Se crea un despacho con la información correspondiente.
6. Se consulta y actualiza el seguimiento del despacho.

## Funcionalidades principales

### Gestión de recursos

- Registro de vehículos.
- Registro de aeronaves.
- Administración de conductores.
- Administración de pilotos.
- Asociación de recursos con operaciones logísticas.

### Gestión de operaciones

- Registro y gestión de clientes.
- Definición de rutas terrestres y aéreas.
- Registro y control de cargas.
- Creación y seguimiento de despachos.
- Filtros en módulos relevantes, como rutas y cargas.

### Interfaz y API

- Operaciones CRUD para los módulos de negocio.
- Interfaz web responsive basada en plantillas Django.
- Componentes visuales desarrollados con Bootstrap.
- API REST implementada con Django REST Framework.
- Documentación interactiva mediante Swagger y ReDoc.

## Arquitectura y módulos

El proyecto está organizado alrededor de los principales conceptos del dominio logístico:

- Clientes.
- Vehículos.
- Aeronaves.
- Conductores.
- Pilotos.
- Rutas.
- Cargas.
- Despachos.

La aplicación utiliza Django como framework principal para el modelado de datos, las vistas web, las rutas y la exposición de servicios REST.

## Tecnologías

- Python 3.13
- Django 5.2
- Django REST Framework
- drf-yasg
- HTML, CSS y JavaScript
- Bootstrap

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

## Rutas y documentación de la API

| Método | Ruta | Descripción |
|--------|------|-------------|
| `GET` | `http://127.0.0.1:8000/` | Sitio web de la aplicación |
| `GET` | `http://127.0.0.1:8000/swagger/` | Documentación Swagger |
| `GET` | `http://127.0.0.1:8000/redoc/` | Documentación ReDoc |

## Despliegue

Como parte del trabajo académico, el proyecto fue llevado a un entorno de despliegue en **AWS** durante la evaluación.

La versión disponible en este repositorio está orientada a la ejecución local y utiliza la configuración necesaria para revisar el sistema sin depender del entorno original de despliegue.

## Alcance y limitaciones

Este repositorio representa una implementación académica funcional de alcance introductorio-intermedio. Antes de utilizarlo como solución productiva sería necesario revisar, entre otros aspectos:

- Validaciones y reglas de negocio más completas.
- Control de acceso y autenticación para todos los módulos.
- Gestión de variables de entorno y secretos.
- Configuración de una base de datos para producción.
- Registro de eventos, monitoreo y respaldos.
- Pruebas automatizadas y controles de seguridad.
- Integración con servicios externos de transporte o seguimiento en tiempo real.

## Contexto académico

Este repositorio conserva una entrega desarrollada durante la **Evaluación 3 de Backend**. Su propósito fue aplicar modelado de entidades, operaciones CRUD, organización de un dominio logístico, desarrollo de una interfaz web, exposición de una API REST y documentación de servicios.
