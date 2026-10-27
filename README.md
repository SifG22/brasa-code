<p align="center">
  <img src="resources/brasa-code.svg" width="120" alt="Brasa Code logo">
</p>

<h1 align="center">Brasa Code</h1>

<p align="center">
  <strong>The free, fast and private code editor.</strong><br>
  No accounts. No paid AI. No tracking. Just you and your code.
</p>

<p align="center">
  <a href="https://sifg.net/brasa"><img alt="Download" src="https://img.shields.io/badge/download-sifg.net%2Fbrasa-FF6B35?style=for-the-badge"></a>
</p>

<p align="center">
  <img alt="Platform: Windows" src="https://img.shields.io/badge/platform-Windows%20x64%20%7C%20ARM64-1A1614?style=flat-square">
  <img alt="Price: free" src="https://img.shields.io/badge/price-free-4ADE80?style=flat-square">
  <img alt="Telemetry: off" src="https://img.shields.io/badge/telemetry-off-4ADE80?style=flat-square">
  <a href="https://open-vsx.org"><img alt="Extensions: Open VSX" src="https://img.shields.io/badge/extensions-Open%20VSX-C160EF?style=flat-square"></a>
</p>

<p align="center">
  <b>English</b> · <a href="README.es.md">Español</a>
</p>

<p align="center">
  <img src="docs/screenshots/en/editor-dark.png" alt="Brasa Code editor with the Brasa Dark theme" width="900">
</p>

---

## Download

1. Get the installer from **[sifg.net/brasa](https://sifg.net/brasa)**.
2. Run it. It always installs the latest version and checks that the download is intact.
3. Start coding. Brasa Code updates itself.

Prefer the full installer? Every version is also on the [Releases](https://github.com/SifG22/brasa-code/releases) page, with `SHA256SUMS.txt` to verify it.

## Why Brasa Code?

| | |
|---|---|
| 🔥 **Free forever** | Every feature is free. There is no plan, no trial and no "Upgrade to Pro" button. |
| 🔒 **Private by default** | Telemetry, experiments, crash reports and surveys are off. Nothing is sent anywhere unless you ask for it. |
| 🙅 **No account needed** | No sign-in prompts and no account menu. GitHub sign-in is only used when *you* push or clone with Git. |
| 🩺 **Errors explained** | The Errors panel tells you, in plain words, what each error means and how to fix it. No AI, no account. |
| ⚡ **Saves you hours** | Auto save, fix & format on save, organized imports, paired tag renaming and spell checking, ready out of the box. |
| 🏠 **Feels at home** | Import your settings, shortcuts, snippets and extensions from VS Code or Cursor in one click. |
| 🧩 **Huge extension library** | Thousands of free extensions from [Open VSX](https://open-vsx.org). |
| 🌍 **English & Spanish** | The whole interface is available in both languages. |

## How it compares

|  | **Brasa Code** | VS Code | Cursor | Devin Desktop<br><sub>(formerly Windsurf)</sub> |
|---|:---:|:---:|:---:|:---:|
| Price | **Free, everything** | Free editor; Copilot has a limited free plan and paid plans | Limited free plan; Pro from $20/month | Limited free plan; Pro from $20/month |
| Works without an account | ✅ | ✅ (Copilot needs a GitHub account) | Editor yes, AI needs an account | Editor yes, AI needs an account |
| Telemetry off out of the box | ✅ | ❌ | Optional privacy mode | Configurable |
| Errors explained in plain words, without AI | ✅ | ❌ | ❌ | ❌ |
| One-click import from VS Code **and** Cursor | ✅ | ❌ | From VS Code | From VS Code and Cursor |
| Built-in AI assistant | ❌ Free extensions only | ✅ Copilot | ✅ | ✅ |
| Extension library | Open VSX | Visual Studio Marketplace | Open VSX | Open VSX |

Brasa Code is for people who want a fast, clean and private editor without subscriptions. If an AI agent writing code for you is what you need most, Cursor or Devin Desktop are built around that.

<sub>Prices and plans as of October 2026. Check each product's website for the latest details.</sub>

## A first run that adapts to you

The first time you open Brasa Code, a short setup asks what you want to do, your language, your style, the editor you come from and what you are going to build. It then installs the right free tools for you: clangd for C/C++, the Astro language tools, Ruff for Python, and more.

<p align="center">
  <img src="docs/screenshots/en/onboarding.png" alt="Brasa Code welcome setup" width="900">
</p>

## Brasa Settings

Everything that matters in one place, with no account section and nothing to buy. Open it with <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>J</kbd> or the flame in the status bar.

<p align="center">
  <img src="docs/screenshots/en/settings.png" alt="Brasa Settings" width="900">
</p>

## Looks great, day and night

Two hand-tuned themes with a warm ember palette and their own syntax colors, plus Material file icons.

<table>
  <tr>
    <td><img src="docs/screenshots/en/editor-dark.png" alt="Brasa Dark"></td>
    <td><img src="docs/screenshots/en/editor-light.png" alt="Brasa Light"></td>
  </tr>
  <tr>
    <td align="center">Brasa Dark</td>
    <td align="center">Brasa Light</td>
  </tr>
</table>

## Built-in time savers

| Feature | What it does |
|---|---|
| Errors panel | Every problem in your project, grouped by file, with what it means and how to fix it. |
| Auto save | Files are saved as you type. |
| Fix & format on save | Runs your formatter, applies safe lint fixes and organizes imports. |
| Rename paired tags | Editing `<div>` also updates `</div>`. |
| Update imports on move | Moving or renaming a file updates every import. |
| Spell checker | Catches typos in code, comments and Markdown, in English and Spanish. |
| Sticky scroll | The current function and class stay visible while you scroll. |
| Smart language support | Open an `.astro`, `.vue`, `.svelte`, `.mdx`, `.toml` or `.prisma` file and Brasa offers the right free extension in one click. |

Every one of them can be switched on or off in **Brasa Settings**.

## About

Brasa Code is made by [SifG22](https://github.com/SifG22). It is free to use; its source code is not public.

Brasa Code includes open source components. Their licenses and notices are included with the app.

Brasa Code is an independent project and is not affiliated with or endorsed by Microsoft, Anysphere or Cognition. "Visual Studio Code" and "VS Code" are trademarks of Microsoft. "Cursor" is a trademark of Anysphere. "Devin" and "Windsurf" are trademarks of Cognition.

<p align="center">Made with 🔥 by <a href="https://github.com/SifG22">SifG22</a> · <a href="https://sifg.net">sifg.net</a></p>
