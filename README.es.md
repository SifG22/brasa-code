<p align="center">
  <img src="resources/brasa-code.svg" width="120" alt="Logo de Brasa Code">
</p>

<h1 align="center">Brasa Code</h1>

<p align="center">
  <strong>El editor de código gratis, rápido y privado.</strong><br>
  Sin cuentas. Sin IA de pago. Sin rastreo. Solo tú y tu código.
</p>

<p align="center">
  <a href="https://sifg.net/brasa"><img alt="Descargar" src="https://img.shields.io/badge/descargar-sifg.net%2Fbrasa-FF6B35?style=for-the-badge"></a>
</p>

<p align="center">
  <img alt="Plataforma: Windows" src="https://img.shields.io/badge/plataforma-Windows%20x64%20%7C%20ARM64-1A1614?style=flat-square">
  <img alt="Precio: gratis" src="https://img.shields.io/badge/precio-gratis-4ADE80?style=flat-square">
  <img alt="Telemetría: apagada" src="https://img.shields.io/badge/telemetr%C3%ADa-apagada-4ADE80?style=flat-square">
  <a href="https://open-vsx.org"><img alt="Extensiones: Open VSX" src="https://img.shields.io/badge/extensiones-Open%20VSX-C160EF?style=flat-square"></a>
</p>

<p align="center">
  <a href="README.md">English</a> · <b>Español</b>
</p>

<p align="center">
  <img src="docs/screenshots/es/editor-dark.png" alt="Editor de Brasa Code con el tema Brasa Dark" width="900">
</p>

---

## Descarga

1. Descarga el instalador en **[sifg.net/brasa](https://sifg.net/brasa)**.
2. Ábrelo. Siempre instala la última versión y comprueba que la descarga está intacta.
3. A programar. Brasa Code se actualiza solo.

¿Prefieres el instalador completo? Todas las versiones están también en [Releases](https://github.com/SifG22/brasa-code/releases), con `SHA256SUMS.txt` para comprobarlas.

## ¿Por qué Brasa Code?

| | |
|---|---|
| 🔥 **Gratis para siempre** | Todas las funciones son gratis. No hay planes, ni pruebas, ni botón de "Pásate a Pro". |
| 🔒 **Privado por defecto** | Telemetría, experimentos, informes de errores y encuestas apagados. No se envía nada a ningún sitio salvo que tú lo pidas. |
| 🙅 **Sin cuenta** | Ni avisos para iniciar sesión ni menú de cuentas. Solo se usa GitHub cuando *tú* haces push o clonas con Git. |
| 🩺 **Errores explicados** | El panel Errores te dice, en palabras claras, qué significa cada error y cómo arreglarlo. Sin IA y sin cuenta. |
| ⚡ **Te ahorra horas** | Guardado automático, arreglos y formato al guardar, imports ordenados, renombrado de etiquetas pareadas y corrector ortográfico, listos desde el principio. |
| 🏠 **Como en casa** | Importa tus ajustes, atajos, snippets y extensiones de VS Code o Cursor en un clic. |
| 🧩 **Miles de extensiones** | Miles de extensiones gratis de [Open VSX](https://open-vsx.org). |
| 🌍 **Español e inglés** | Toda la interfaz está en los dos idiomas. |

## Comparación

|  | **Brasa Code** | VS Code | Cursor | Devin Desktop<br><sub>(antes Windsurf)</sub> |
|---|:---:|:---:|:---:|:---:|
| Precio | **Gratis, todo** | Editor gratis; Copilot tiene un plan gratis limitado y planes de pago | Plan gratis limitado; Pro desde 20 $/mes | Plan gratis limitado; Pro desde 20 $/mes |
| Funciona sin cuenta | ✅ | ✅ (Copilot necesita cuenta de GitHub) | El editor sí; la IA pide cuenta | El editor sí; la IA pide cuenta |
| Telemetría apagada de serie | ✅ | ❌ | Modo privacidad opcional | Configurable |
| Errores explicados en palabras claras, sin IA | ✅ | ❌ | ❌ | ❌ |
| Importar de VS Code **y** Cursor en un clic | ✅ | ❌ | Desde VS Code | Desde VS Code y Cursor |
| Asistente de IA integrado | ❌ Solo extensiones gratis | ✅ Copilot | ✅ | ✅ |
| Extensiones | Open VSX | Visual Studio Marketplace | Open VSX | Open VSX |

Brasa Code es para quien quiere un editor rápido, limpio y privado, sin suscripciones. Si lo que más necesitas es un agente de IA que escriba el código por ti, Cursor y Devin Desktop están pensados para eso.

<sub>Precios y planes a octubre de 2026. Consulta la web de cada producto para ver los datos más recientes.</sub>

## Un primer arranque que se adapta a ti

La primera vez que abres Brasa Code, una configuración corta te pregunta qué quieres hacer, tu idioma, tu estilo, de qué editor vienes y qué vas a crear. Después instala las herramientas gratis adecuadas: clangd para C/C++, las herramientas de Astro, Ruff para Python y más.

<p align="center">
  <img src="docs/screenshots/es/onboarding.png" alt="Configuración inicial de Brasa Code" width="900">
</p>

## Ajustes de Brasa

Todo lo importante en un solo sitio, sin sección de cuenta y sin nada que comprar. Ábrelo con <kbd>Ctrl</kbd>+<kbd>Mayús</kbd>+<kbd>J</kbd> o con la llama de la barra de estado.

<p align="center">
  <img src="docs/screenshots/es/settings.png" alt="Ajustes de Brasa" width="900">
</p>

## Bonito de día y de noche

Dos temas ajustados a mano con una paleta cálida de brasa y sus propios colores de sintaxis, más los iconos de archivo Material.

<table>
  <tr>
    <td><img src="docs/screenshots/es/editor-dark.png" alt="Brasa Dark"></td>
    <td><img src="docs/screenshots/es/editor-light.png" alt="Brasa Light"></td>
  </tr>
  <tr>
    <td align="center">Brasa Dark</td>
    <td align="center">Brasa Light</td>
  </tr>
</table>

## Ahorradores de tiempo incluidos

| Función | Qué hace |
|---|---|
| Panel Errores | Todos los problemas del proyecto, agrupados por archivo, con qué significan y cómo arreglarlos. |
| Guardado automático | Los archivos se guardan mientras escribes. |
| Arreglar y formatear al guardar | Pasa tu formateador, aplica arreglos seguros del linter y ordena los imports. |
| Renombrar etiquetas pareadas | Al editar `<div>` también cambia `</div>`. |
| Actualizar imports al mover | Al mover o renombrar un archivo se actualizan todos los imports. |
| Corrector ortográfico | Detecta faltas en código, comentarios y Markdown, en español e inglés. |
| Desplazamiento fijo | La función y la clase actuales siguen visibles mientras te desplazas. |
| Soporte de lenguajes inteligente | Abre un archivo `.astro`, `.vue`, `.svelte`, `.mdx`, `.toml` o `.prisma` y Brasa te ofrece la extensión gratis adecuada en un clic. |

Todas se pueden activar o desactivar en **Ajustes de Brasa**.

## Acerca de

Brasa Code lo hace [SifG22](https://github.com/SifG22). Es gratis; su código fuente no es público.

Brasa Code está construido sobre [Code - OSS](https://github.com/microsoft/vscode) (licencia MIT). Las licencias y avisos de Code - OSS y de todos los componentes de terceros van incluidos con la aplicación.

Brasa Code es un proyecto independiente y no está afiliado ni respaldado por Microsoft, Anysphere ni Cognition. "Visual Studio Code" y "VS Code" son marcas de Microsoft. "Cursor" es una marca de Anysphere. "Devin" y "Windsurf" son marcas de Cognition.

<p align="center">Hecho con 🔥 por <a href="https://github.com/SifG22">SifG22</a> · <a href="https://sifg.net">sifg.net</a></p>
