<div align="center">

# 🧰 JSON Swiss Knife

### The all-in-one JSON toolkit — *format, validate, diff, convert, fix, and generate schemas.*

**English** · [🇫🇷 Français](README.fr.md)

![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Monaco](https://img.shields.io/badge/Monaco_Editor-0078D4?style=flat-square)
![Tailwind](https://img.shields.io/badge/Tailwind-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![AJV](https://img.shields.io/badge/AJV-schema_validation-FF3D00?style=flat-square)

</div>

---

## 📖 What is JSON Swiss Knife?

JSON Swiss Knife is a feature-rich browser-based JSON editor powered by Monaco Editor. Format messy JSON, validate against schemas, diff two documents, convert between JSON and CSV, auto-fix broken JSON, and generate JSON schemas — all in one workspace.

## ✨ Features

- **Monaco Editor** — Full-featured JSON editor with syntax highlighting and autocomplete
- **Format & Minify** — Prettify or compress JSON with one click
- **Schema Validation** — Validate JSON against JSON Schema (AJV)
- **JSON Diff** — Compare two JSON documents with visual diff
- **JSON ↔ CSV Conversion** — Bidirectional conversion with PapaParse
- **Tolerant Parser** — Auto-fix broken JSON (trailing commas, missing quotes, etc.)
- **Schema Generation** — Infer JSON Schema from your data
- **Web Worker** — Heavy operations run off the main thread
- **Dark / Light Mode** — Theme toggle
- **Bilingual UI** — Full English & French interface

## 🧰 Tech stack

| Layer | Technology |
|-------|-----------|
| Framework | Next.js 16 (App Router) |
| Language | TypeScript |
| Editor | Monaco Editor |
| UI | Tailwind CSS 4 + shadcn/ui + Radix UI |
| State | Zustand |
| Validation | AJV + ajv-formats |
| Diff | jsondiffpatch |
| CSV | PapaParse |
| Parser | jsonc-parser |
| i18n | next-intl |

## 🚀 Getting started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

---

<div align="center">
<sub>

Built with care by <b><a href="https://nathanfernandes.fr">Nathan Fernandes</a></b> — Founder of SYNN-IA · Dijon, France

🌐 <a href="https://nathanfernandes.fr">Portfolio</a> · 💼 <a href="https://www.linkedin.com/in/nathan-fernandes-a5793b377/">LinkedIn</a> · 🐙 <a href="https://github.com/SynnIA">GitHub</a>

</sub>
</div>
