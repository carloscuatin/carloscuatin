<h1 align="center">👋✨ Carlos Cuatin 🦄</h1>

<p align="center">
  <strong>Senior Frontend Engineer</strong> · 10+ years · Bogotá, Colombia 🇨🇴
</p>

<p align="center">
  <a href="https://carloscuatin.com"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-carloscuatin.com-29D7FF?style=for-the-badge&logo=astro&logoColor=white"></a>
  <a href="https://linkedin.com/in/carloscuatin"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:cecg1996@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-12151A?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

## 🧭 About

Interfaces and frontend architecture at scale.

- 🏗️ Currently at **Eden** — microfrontends with **NX** and **Webpack Module Federation** for PACS and clinical management systems
- 🧑‍✈️ Previously **Mercado Libre**, **Rappi**, and **Tech Lead of a 7-person team at Treinta**, where I owned the architecture and stack decisions
- 🧩 Design systems, monorepos, and boundaries that let teams deploy independently
- 📱 Cross-platform mobile with React Native and Flutter
- 🐙 Open source contributor — webpack, react-boilerplate, mern-starter
- 🎤 Speaker at DevFest Bogotá
- 📆 Shipping production frontend since 2015

---

## 🌱 Open source

| Project | Contribution |
| --- | --- |
| **[webpack](https://github.com/webpack/webpack/pulls?q=author%3Acarloscuatin+is%3Amerged)** | **14 merged PRs** migrating the plugin and template layer to ES6 classes ([#3657](https://github.com/webpack/webpack/pull/3657) → [#4034](https://github.com/webpack/webpack/pull/4034)) — `DllReferencePlugin`, `LoaderOptionsPlugin`, `JsonpTemplatePlugin`, `NormalModuleReplacementPlugin`, and ten others |
| **[Hashnode/mern-starter](https://github.com/Hashnode/mern-starter/pulls?q=author%3Acarloscuatin)** | 3 merged PRs — React performance improvements ([#121](https://github.com/Hashnode/mern-starter/pull/121)), redux-devtools fix ([#118](https://github.com/Hashnode/mern-starter/pull/118)), nodemon config ([#117](https://github.com/Hashnode/mern-starter/pull/117)) |
| **[react-boilerplate](https://github.com/react-boilerplate/react-boilerplate/pull/1521)** | Enabled the `react/no-array-index-key` eslint rule across the boilerplate |
| **[remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools/pull/54)** | socketcluster-client upgrade |
| **[react-redux-toastr](https://github.com/diegoddox/react-redux-toastr/pull/83)** | Migrated the stylesheets from Less to Sass |
| **[vuesax](https://github.com/lusaxweb/vuesax/pull/119)** | Removed stray console logs across components |
| **[EDgrid](https://github.com/escueladigital/EDgrid/pulls?q=author%3Acarloscuatin)** | 2 merged PRs — npm packaging |

**[react-resize](https://github.com/carloscuatin/react-resize)** — my own: a React component that reports its own size to its children.

---

## 🚀 Projects

### [form-craft](https://github.com/carloscuatin/form-craft) · [live ↗](https://form-craft-pi.vercel.app)

A form builder SaaS. Drag fields into place, publish to a public link, and responses land in tables and charts in real time.

The interesting part is the permission model: an anonymous stranger must be able to insert a response into a published form, but must never read anyone's responses. That rule lives in **Postgres under Row Level Security** with a `SECURITY DEFINER` helper — not in the application server, where a forgotten check opens the hole. Realtime is a **domain port** rather than a `useEffect`, so swapping Supabase for another provider touches one adapter.

`21 test suites` · `CI-gated deploys` · `16 written architecture decisions`

### [carloscuatin.com](https://github.com/carloscuatin/carloscuatin.com)

This portfolio. Astro, no client framework, bilingual, and an accessibility gate in CI that runs axe-core across every route at three breakpoints in both themes.

---

## 🎤 Speaking

- 🗣️ **Progressive Web Apps** — DevFest Bogotá 2016 ([slides](https://github.com/carloscuatin/progressive-web-apps))
- 🗣️ **Introducción a ReactJS** — Dev Academy LATAM
- 🗣️ **Introducción a ReactJS y React Native** — Capital Junior College, Bogotá

---

## 🛠️ Stack

| Layer | Tools |
| --- | --- |
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Mobile** | ![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white) ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| **Architecture & Infra** | ![NX](https://img.shields.io/badge/NX-143055?style=flat-square&logo=nx&logoColor=white) ![Module Federation](https://img.shields.io/badge/Module%20Federation-8DD6F9?style=flat-square&logo=webpack&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |

---

## 📫 Contact

<p>
  <a href="mailto:cecg1996@gmail.com">cecg1996@gmail.com</a> ·
  <a href="https://linkedin.com/in/carloscuatin">LinkedIn</a> ·
  <a href="https://carloscuatin.com">carloscuatin.com</a>
</p>
