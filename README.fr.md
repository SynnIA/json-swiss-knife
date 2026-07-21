<div align="center">

# 🧰 JSON Swiss Knife

### La boîte à outils JSON tout-en-un — *formatage, validation, diff, conversion, réparation et génération de schémas.*

[🇬🇧 English](README.md) · **Français**

![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Monaco](https://img.shields.io/badge/Monaco_Editor-0078D4?style=flat-square)
![Tailwind](https://img.shields.io/badge/Tailwind-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![AJV](https://img.shields.io/badge/AJV-validation_de_sch%C3%A9ma-FF3D00?style=flat-square)

</div>

---

## 📖 Qu'est-ce que JSON Swiss Knife ?

JSON Swiss Knife est un éditeur JSON complet dans le navigateur, propulsé par Monaco Editor. Formatez du JSON brouillon, validez contre des schémas, comparez deux documents, convertissez entre JSON et CSV, réparez du JSON cassé et générez des schémas — tout dans un seul espace de travail.

## ✨ Fonctionnalités

- **Éditeur Monaco** — Éditeur JSON complet avec coloration syntaxique et autocomplétion
- **Formatage & Minification** — Embellir ou compresser le JSON en un clic
- **Validation de schéma** — Validez le JSON contre un JSON Schema (AJV)
- **Diff JSON** — Comparez deux documents JSON avec diff visuel
- **Conversion JSON ↔ CSV** — Conversion bidirectionnelle avec PapaParse
- **Parseur tolérant** — Répare automatiquement le JSON cassé (virgules finales, guillemets manquants, etc.)
- **Génération de schéma** — Inférez un JSON Schema depuis vos données
- **Web Worker** — Les opérations lourdes s'exécutent hors du thread principal
- **Mode sombre / clair** — Bascule de thème
- **Interface bilingue** — Anglais et français complets

## 🧰 Stack technique

| Couche | Technologie |
|-------|-----------|
| Framework | Next.js 16 (App Router) |
| Langage | TypeScript |
| Éditeur | Monaco Editor |
| UI | Tailwind CSS 4 + shadcn/ui + Radix UI |
| State | Zustand |
| Validation | AJV + ajv-formats |
| Diff | jsondiffpatch |
| CSV | PapaParse |
| Parseur | jsonc-parser |
| i18n | next-intl |

## 🚀 Démarrage rapide

```bash
npm install
npm run dev
```

Ouvrez [http://localhost:3000](http://localhost:3000).

---

<div align="center">
<sub>

Créé avec soin par <b><a href="https://nathanfernandes.fr">Nathan Fernandes</a></b> — Fondateur de SYNN-IA · Dijon, France

🌐 <a href="https://nathanfernandes.fr">Portfolio</a> · 💼 <a href="https://www.linkedin.com/in/nathan-fernandes-a5793b377/">LinkedIn</a> · 🐙 <a href="https://github.com/SynnIA">GitHub</a>

</sub>
</div>
