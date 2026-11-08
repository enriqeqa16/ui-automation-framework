# UI Automation Framework

## 1. Descripción del proyecto

UI Automation Framework es un proyecto enfocado en el desarrollo de un framework de automatización de pruebas funcionales de interfaz de usuario (UI Testing).

El propósito es implementar una estructura organizada, reutilizable y escalable que permita automatizar escenarios de prueba en aplicaciones web, aplicando buenas prácticas de QA Automation y herramientas utilizadas en la industria del desarrollo de software.

El framework se construye utilizando JavaScript, Playwright y Cucumber, incorporando el enfoque BDD (Behavior Driven Development) mediante escenarios escritos en Gherkin.

## 2. Objetivos del proyecto

- Desarrollar un framework de automatización desde cero.
- Automatizar escenarios funcionales de aplicaciones web.
- Implementar pruebas utilizando Cucumber y Gherkin.
- Aplicar el patrón de diseño Page Object Model (POM).
- Implementar buenas prácticas de programación y organización del código.
- Gestionar el control de versiones mediante Git y GitHub.
- Incorporar integración continua utilizando GitHub Actions.

## 3. Tecnologías y herramientas

| Tecnología | Descripción |
|---|---|
| JavaScript | Lenguaje de programación. |
| Node.js | Entorno de ejecución de JavaScript. |
| Playwright | Herramienta para automatización de navegadores. |
| Cucumber | Framework para ejecutar pruebas basadas en BDD. |
| Gherkin | Lenguaje para describir escenarios de prueba. |
| Git | Sistema de control de versiones. |
| GitHub | Plataforma para gestionar el repositorio. |
| GitHub Actions | Herramienta de integración continua. |

## 4. Arquitectura del proyecto

El framework utiliza una estructura modular que permite separar las responsabilidades y facilitar el mantenimiento de las pruebas automatizadas.

```text
ui-automation-framework/
│
├── features/
│   └── login.feature
│
├── step-definitions/
│   └── login.steps.js
│
├── pages/
│   └── LoginPage.js
│
├── support/
│   └── hooks.js
│
├── test-data/
│
├── reports/
│
├── screenshots/
│
├── cucumber.js
├── package.json
├── package-lock.json
└── .gitignore
```

## 5. Instalación y configuración

Para ejecutar el proyecto localmente, se requiere tener instalado Node.js y Git.

### Clonar el repositorio

```bash
git clone URL_DEL_REPOSITORIO
```

### Ingresar al directorio del proyecto

```bash
cd ui-automation-framework
```

### Instalar las dependencias

```bash
npm install
```

### Instalar Chromium

```bash
npx playwright install chromium
```

## 6. Ejecución de pruebas

Para ejecutar los escenarios automatizados mediante Cucumber, utilizar el siguiente comando:

```bash
npm test
```

Al finalizar la ejecución, se generarán los resultados y las evidencias correspondientes según la configuración del framework.

## 7. Buenas prácticas implementadas

El desarrollo del framework contempla las siguientes prácticas:

- Page Object Model (POM) para separar la lógica de interacción con las páginas.
- Separación entre escenarios, definiciones de pasos y elementos de interfaz.
- Reutilización de métodos y componentes.
- Gestión del navegador mediante hooks de Cucumber.
- Captura de screenshots cuando se producen fallos.
- Generación de reportes de ejecución.
- Control de versiones mediante Git.
- Trabajo colaborativo mediante ramas y Pull Requests.

## 8. Integración continua

Se contempla la implementación de GitHub Actions para automatizar la ejecución de las pruebas ante cada actualización del repositorio.

El objetivo es validar los cambios realizados y almacenar las evidencias de ejecución mediante un artefacto denominado:

`cucumber-test-evidence`

## 9. Alcance del proyecto

El alcance actual se concentra exclusivamente en la automatización de pruebas funcionales de interfaz de usuario.

No se contemplan pruebas de API ni pruebas de bases de datos.

## 10. Estado del proyecto

**Estado:** En desarrollo.

El framework se construye progresivamente, incorporando nuevas funcionalidades, configuraciones y mejoras conforme avanza su implementación.

---

**UI Automation Framework**

Proyecto de aprendizaje y desarrollo profesional orientado a QA Automation.