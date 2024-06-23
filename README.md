# MyApp

## Descripción

Esta es una aplicación básica de Flask que muestra "¡Hola, mundo!" cuando se accede a la ruta principal. El proyecto incluye configuraciones para GitHub Actions que ejecutan `flake8` para el linting del código Python.

## Estructura del Proyecto

```bash
MyApp/
├── .github
      └── workflows
            └── lint-test.yml
├── src
      └── app.py  # Código principal de la aplicación Flask
├── Dockerfile
└── requirements.txt    # Archivo de dependencias de Python

## Requisitos

Python 3.8 o superior
Pip (gestor de paquetes de Python)

## Instalación

### 1. Clona el Repositorio
  git clone https://github.com/javimonaco/MyApp.git
  cd tu-repositorio

### 2. Crea y activa un entorno virtual
  python -m venv venv
  source venv/bin/activate   # En Windows usa `venv\Scripts\activate`

### 3. Instala las dependencias
  pip install -r requirements.txt

## Uso

### 1. Ejecuta la aplicación
  python app.py
