# Carlos Cuatin

**Senior Frontend Engineer** · Bogotá, Colombia · [carloscuatin.com](https://carloscuatin.com)

Interfaces and frontend architecture at scale. Currently at **Eden**, building
microfrontends with NX and Webpack Module Federation for PACS and clinical
management systems. Before that: **Mercado Libre**, **Rappi**, and **Tech Lead of a
7-person team at Treinta**, where I owned the architecture and stack decisions.

10+ years shipping production frontend, since 2015.

---

## Open source

**[webpack](https://github.com/webpack/webpack)** — 14 merged pull requests
migrating webpack's plugin and template layer to ES6 classes
([#3657](https://github.com/webpack/webpack/pull/3657) →
[#4034](https://github.com/webpack/webpack/pull/4034), Dec 2016 – Jan 2017).
`DllReferencePlugin`, `LoaderOptionsPlugin`, `JsonpTemplatePlugin`,
`NormalModuleReplacementPlugin`, `EvalSourceMapDevToolPlugin`, and nine others.

**[react-resize](https://github.com/carloscuatin/react-resize)** — a React
component that reports its own size to its children.

**[suntory](https://github.com/carloscuatin/suntory)** — appends arbitrary events
to React components.

---

## Selected projects

**[form-craft](https://github.com/carloscuatin/form-craft)** ·
[live](https://form-craft-pi.vercel.app) — A form builder SaaS. Drag fields into
place, publish to a public link, and responses land in tables and charts in real
time.

The interesting part is the permission model: an anonymous stranger must be able to
insert a response into a published form, but must never read anyone's responses.
That rule lives in Postgres under Row Level Security with a `SECURITY DEFINER`
helper, not in the application server where a forgotten check opens the hole.
Realtime is a domain port rather than a `useEffect`, so swapping Supabase for
another provider touches one adapter. 21 test suites, CI-gated deploys, and 16
written architecture decisions.

**[carloscuatin.com](https://github.com/carloscuatin/carloscuatin.com)** — This
portfolio. Astro, no client framework, bilingual, and an accessibility gate in CI
that runs axe-core across every route at three breakpoints in both themes.

---

## Speaking

- **Progressive Web Apps** — DevFest Bogotá 2016
  ([slides](https://github.com/carloscuatin/progressive-web-apps))
- **Introducción a ReactJS** — Dev Academy LATAM
- **Introducción a ReactJS y React Native** — Capital Junior College, Bogotá

---

## Stack

**Languages** TypeScript · JavaScript · Go · Java

**Frontend** React · Next.js · Astro · Tailwind · styled-components

**Backend** Node.js · NestJS · GraphQL · REST

**Data** PostgreSQL · MongoDB

**Architecture** Microfrontends (NX, Module Federation) · Design systems ·
Microservices

**Infra** Docker · AWS (SQS, SNS, IaC) · Vercel · GitHub Actions

---

## Contact

[cecg1996@gmail.com](mailto:cecg1996@gmail.com) ·
[LinkedIn](https://linkedin.com/in/carloscuatin) ·
[carloscuatin.com](https://carloscuatin.com)
