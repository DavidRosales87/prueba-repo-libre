# Proyecto de Azure Functions con Node.js (Modelo v4)

Este proyecto es una muestra de cómo configurar y trabajar con Azure Functions utilizando Node.js y el modelo v4.

## Prerrequisitos

Antes de comenzar, asegúrate de tener instaladas las siguientes herramientas:

1. **Node.js** (versión 18)
2. **npm** (que viene con Node.js)
3. **Azure Functions Core Tools**:
    ```bash
    npm install -g azure-functions-core-tools@4 --unsafe-perm true
    ```
## Extensiones de Visual Studio Code

Para una mejor experiencia de desarrollo, instala las siguientes extensiones en Visual Studio Code:

- **Azure Functions**: Para crear, depurar, administrar y desplegar funciones de Azure.
- **Azure Account**: Para autenticarte en tu cuenta de Azure directamente desde VS Code.
- **Azure Tools**: Conjunto de herramientas de Azure, incluidas App Service, Cosmos DB, Functions, Storage, etc.

## Creación de un Proyecto de Azure Functions

1. Abre Visual Studio Code.
2. Abre la paleta de comandos (Ctrl+Shift+P) y escribe `Azure Functions: Create New Project...`.
3. Selecciona una carpeta para tu proyecto.
4. Selecciona el lenguaje: **Node.js**.
5. Selecciona un template de función (por ejemplo, **HTTP trigger**).
6. Proporciona un nombre para la nueva función.
7. Selecciona un nivel de autorización (por ejemplo, **Anonymus**).

## Crear una Nueva Función

Sigue los siguientes pasos para agregar una nueva función a tu proyecto de Azure Functions:

1. Abre la paleta de comandos (Ctrl+Shift+P).
2. Escribe y selecciona `Azure Functions: Create Function...`.
3. Selecciona la carpeta de tu proyecto si es necesario.
4. Elige un lenguaje para tu función: **JavaScript**.
5. Selecciona un template de función (por ejemplo, **HTTP trigger**).
6. Proporciona un nombre para la nueva función.
7. Selecciona un nivel de autorización (por ejemplo, **Anonymus**).

## Desarrollo y Pruebas Locales

Para desarrollar y probar tus funciones localmente, usa el siguiente comando:

```bash
func start
```