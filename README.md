<h1 align="center">Code Jr. Assessment Project</h1>
<p align="center">Academic and junior enterprise web development challenge</p>
<p align="center"><img src="https://skillicons.dev/icons?i=nextjs,react,typescript,tailwind" alt="Technology stack" /></p>

---

## Overview

A web application developed as part of a Code Jr. assessment. The project combines public-facing pages with a member-management interface, demonstrating component-based development and frontend organization.

## Features

- Home, contact and login pages.
- Member management screens for creating, editing, viewing and deleting members.
- Reusable interface components and a centralized theme.
- Local JSON data file for development.

## Tech stack

Next.js 13, React 18, TypeScript, Chakra UI, Tailwind CSS and Axios.

## Getting started

```bash
cd desafio-assessoria
npm ci
npm run dev
```

Open [localhost:3000](http://localhost:3000). See the [original setup notes](desafio-assessoria/README.md). The development server does not necessarily provide every data service required by the member-management screens.

## Project structure

- `src/pages/`: application routes.
- `src/components/`: reusable UI components.
- `src/styles/`: theme configuration.
- `public/`: visual assets.
- `db.json`: local data file.

All paths above are inside `desafio-assessoria/`.

## Status

Historical assessment project. Authentication, data persistence and dependency security have not been audited for production use. No live deployment is claimed.
