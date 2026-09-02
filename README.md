# API de Gestión de Productos y Categorías - FastAPI

Trabajo práctico desarrollado con una arquitectura modular por capas, utilizando **FastAPI** para la creación de la API, **Pydantic** para la validación de datos y el **Patrón Repository** para separar la lógica de negocio y persistencia.

---
## Integrantes 

Mejia Fabrizio 
Gutierrez Jose Maria

## Estructura del Proyecto

```text
tp-productos-api/
│
├── app/
│   ├── api/
│   │   └── v1/
│   │       ├── categorias/
│   │       └── productos/
│   ├── core/
│   ├── models/
│   ├── schemas/
│   └── main.py
│
├── .gitignore
├── README.md
└── requirements.txt
```
# para levantar la api en la terminal ejecutar estos 2 codigos
primera y unica vez 
paso 1
python -m venv venv
venv\Scripts\Activate.ps1

paso 2
pip install fastapi uvicorn pydantic
paso 2.5
pip install "fastapi[standard]"

paso 3 
fastapi dev app/main.py

paso 4 
venv\Scripts\Activate.ps1 

ven esto? 
