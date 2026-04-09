# Remindly 🔔

**Remindly** es una solución multiplataforma diseñada para la gestión eficiente de recordatorios y tareas diarias. Permite a los usuarios organizar su día a día, marcar objetivos cumplidos y mantener un seguimiento constante de sus pendientes con una interfaz limpia y moderna.

## 🚀 Funcionalidades Principales

* **Gestión de Recordatorios:** Crea, edita y organiza tareas con facilidad.
* **Seguimiento de Estado:** Marca tareas como terminadas para visualizar tu progreso.
* **Arquitectura Modular:** Construido con un enfoque de micro-paquetes para facilitar el mantenimiento y la escalabilidad.
* **Diseño Atómico:** Sistema de diseño basado en componentes reutilizables (`atomic_design`).

## 🏗️ Estructura del Proyecto (Workspace)

Este proyecto utiliza un espacio de trabajo modular para separar las responsabilidades:

* **`remindly`**: La aplicación principal de Flutter.
* **`atomic_design`**: Librería de componentes UI basada en diseño atómico.
* **`common`**: Utilidades, extensiones y código compartido.
* **`models`**: Definición de entidades de datos y modelos de lógica de negocio.
* **`localizations`**: Gestión de idiomas y textos de la app.
* **`dependencies`**: Centralización de las dependencias de terceros.

## 🛠️ Stack Tecnológico

* **Framework:** [Flutter](https://flutter.dev)
* **Lenguaje:** [Dart](https://dart.dev)
* **Arquitectura:** Modular / Clean Architecture.

## 📦 Instalación y Configuración

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/remindly.git](https://github.com/tu-usuario/remindly.git)
    ```
2.  **Abrir el Workspace:**
    Abre el archivo `remindly.code-workspace` en VS Code para cargar todos los módulos.
    
3.  **Instalar dependencias:**
    Ejecuta el siguiente comando en la raíz para obtener los paquetes de todos los módulos:
    ```bash
    flutter pub get
    ```

---
Desarrollado con ❤️ por el equipo de Remindly.