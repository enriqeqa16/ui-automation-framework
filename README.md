# UI Automation Framework

## Descripción del proyecto

Este proyecto consiste en el desarrollo de un framework de automatización de pruebas de interfaz de usuario (UI Testing), utilizando JavaScript, Playwright y Cucumber.

El objetivo es implementar una estructura de automatización organizada, escalable y mantenible, aplicando buenas prácticas de QA Automation, el patrón de diseño Page Object Model (POM) y la metodología BDD (Behavior Driven Development).

El framework permitirá automatizar escenarios de prueba funcionales sobre aplicaciones web, validar el comportamiento de sus componentes y generar evidencias de ejecución.

## Tecnologías utilizadas

- **JavaScript:** Lenguaje de programación.
- **Node.js:** Entorno de ejecución de JavaScript.
- **Playwright:** Herramienta para la automatización de navegadores.
- **Cucumber:** Ejecución de pruebas basadas en BDD.
- **Gherkin:** Lenguaje para describir escenarios de prueba.
- **Git:** Control de versiones.
- **GitHub:** Administración del repositorio y colaboración.
- **GitHub Actions:** Automatización de procesos CI/CD.

## Arquitectura del proyecto

El framework utiliza una estructura modular para separar las funcionalidades y facilitar su mantenimiento.

```text
ui-automation-framework/
│
├── features/              # Archivos Gherkin (.feature)
├── pages/                 # Page Object Model (POM)
├── step-definitions/      # Definición de los pasos de prueba
├── support/               # Hooks y configuración
├── test-data/             # Datos utilizados en las pruebas
├── reports/               # Reportes de ejecución
├── screenshots/           # Evidencias de ejecución
│
├── .gitignore
├── cucumber.js
├── package.json
├── package-lock.json
└── README.md
```

## Instalación y configuración

**1. Clonar el repositorio**

```bash
git clone https://github.com/enriqeqa16/ui-automation-framework.git
```

**2. Ingresar al proyecto**

```bash
cd ui-automation-framework
```

**3. Instalar las dependencias**

```bash
npm install
```

**4. Instalar los navegadores de Playwright**

```bash
npx playwright install chromium
```

## Ejecución de pruebas

Para ejecutar los escenarios automatizados:

```bash
npm test
```

Los resultados de ejecución se visualizarán en la terminal y se generará el reporte HTML según la configuración de Cucumber.

## Buenas prácticas implementadas

- Separación de responsabilidades.
- Organización modular del framework.
- Implementación del patrón Page Object Model.
- Uso de BDD y Gherkin.
- Reutilización de componentes y métodos.
- Control de versiones mediante Git.
- Gestión de ramas y Pull Requests.
- Evidencias de ejecución y reportes.
- Integración continua mediante GitHub Actions.

## Alcance del proyecto

Este framework está enfocado exclusivamente en la automatización de pruebas funcionales de interfaz de usuario (UI Testing).

No contempla pruebas de API, base de datos ni validaciones de backend.

## Mejoras futuras

- Implementación de reportes Allure.
- Mejoras en la gestión de datos de prueba.
- Ampliación de escenarios automatizados.
- Integración de evidencias en GitHub Actions.
- Optimización de la arquitectura y mantenibilidad del framework.

## Autor

Proyecto desarrollado como parte del proceso de aprendizaje y fortalecimiento de habilidades en QA Automation, con enfoque en herramientas y prácticas utilizadas en proyectos profesionales de aseguramiento de calidad de software.
