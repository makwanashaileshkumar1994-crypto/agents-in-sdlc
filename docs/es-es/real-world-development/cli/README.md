---
slug: es-es/real-world-development/cli
title: "GitHub Copilot CLI"
description: "Crea, verifica y entrega dos cambios de Tailspin Toys mientras aprendes a usar los modos de Copilot CLI, las personalizaciones, las herramientas MCP y la automatización de solicitudes de incorporación de cambios."
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

**[GitHub Copilot CLI][about-copilot-cli]** incorpora GitHub Copilot a tu terminal como asistente de programación con agentes. Explora bases de código, genera código, ejecuta comandos y se conecta a herramientas externas, todo desde la línea de comandos, para que puedas mantener el flujo sin cambiar a un editor gráfico.

El taller sigue un flujo de trabajo continuo en Tailspin Toys:

1. Prepara el proyecto en GitHub Codespaces, instala Copilot CLI y familiarízate con la herramienta.
2. Añade una estrella como cambio específico, revisa el resultado en el navegador y fusiona manualmente tu primera solicitud de incorporación de cambios (PR).
3. Empieza por la incidencia de filtrado, define el enfoque en el modo Plan, impleméntalo en el modo Autopilot y revísalo en el modo Interactive.
4. Actualiza las instrucciones del repositorio y aplícalas al trabajo de filtrado.
5. Personaliza la habilidad existente `quality-checks` y úsala para ejecutar las comprobaciones del proyecto.
6. Añade el servidor Model Context Protocol (MCP) de Playwright y úsalo para explorar el filtrado en un navegador.
7. Crea un agente personalizado de control de calidad (QA) y úsalo para revisar los requisitos, la cobertura y las pruebas de verificación.
8. Revisa todos los cambios de filtrado y usa Agent Merge para la PR de filtrado.
9. Explora comandos de barra útiles para gestionar el contexto, los modelos, el uso compartido y la delegación opcional al agente en la nube.

Para mantener el enfoque del taller, crearás dos PR: una para las estrellas y otra para el filtrado, que incluirá las actualizaciones de instrucciones y habilidades, el perfil de QA y las pruebas. El flujo de filtrado y calidad comparte una conversación y una rama para que puedas continuar el trabajo mientras exploras cada herramienta.

## Lecciones

| Lección | Tema | Descripción |
| ------ | ----- | ----------- |
| [0. Requisitos previos][ex0] | Configuración | Crea el repositorio y el codespace |
| [1. Instala Copilot CLI][ex1] | Instalación | Instala y autentica Copilot CLI, y familiarízate con la herramienta |
| [2. Añade estrellas: un logro rápido][ex2] | Primer cambio | Muestra las estrellas existentes y el valor alternativo si no hay ninguna; después, fusiona tu primera PR |
| [3. Modos de agente: Plan y Autopilot][ex3] | Modos de agente | Planifica la funcionalidad desde su incidencia, impleméntala con Autopilot y revísala en Interactive |
| [4. Guía a Copilot con instrucciones personalizadas][ex4] | Contexto | Explora y actualiza las instrucciones, y aplícalas al filtrado |
| [5. Personaliza y usa la habilidad quality-checks][ex5] | Comprobaciones reutilizables | Explora la habilidad existente, cambia el formato del informe y ejecútala |
| [6. Valida la funcionalidad con Playwright MCP][ex6] | Observación en el navegador | Configura MCP en la CLI e inspecciona el comportamiento del filtrado |
| [7. Crea y usa un agente de QA][ex7] | Requisitos y cobertura | Crea y selecciona un perfil especializado, y reúne pruebas de verificación |
| [8. Crea y fusiona la PR de funcionalidad][ex8] | Revisión y fusión | Revisa todos los cambios, crea la PR y usa Agent Merge |
| [9. Comandos de barra de GitHub Copilot CLI][ex9] | Funciones de la CLI | Explora el contexto, los modelos, el uso compartido y la delegación opcional al agente en la nube |
| [10. Repaso y pasos siguientes][ex10] | Resumen | Repasa el flujo de trabajo, las personalizaciones reutilizables y otros recursos |
| [Opcional: Incorpora Foundry][foundry] | Agentes hospedados | Prepara un modelo, despliega un agente basado en el catálogo y conéctalo al sitio web |

## Requisitos previos

Antes de asistir a este taller, asegúrate de tener:

- [ ] Una cuenta de GitHub con un plan activo **Copilot Student, Pro, Pro+, Business o Enterprise**
- [ ] Permiso para crear un repositorio y un codespace
- [ ] Conocimientos básicos de operaciones de terminal o línea de comandos

> [!TIP]
> ¿No tienes un plan de pago? Los estudiantes verificados pueden obtener GitHub Copilot gratis a través de [GitHub Education][student-plan]. El plan **Copilot Student** incluye las funciones de agente, MCP, revisión de código y Copilot CLI que se usan en este taller.

> [!NOTE]
> Si usas Copilot Business o Copilot Enterprise, asegúrate de que tu administrador haya habilitado Copilot CLI.

## Primeros pasos

**[Empieza con los requisitos previos →][ex0]**

[about-copilot-cli]: https://docs.github.com/copilot/concepts/agents/about-copilot-cli
[student-plan]: https://github.com/education/students
[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
[foundry]: 8-foundry-agent/
