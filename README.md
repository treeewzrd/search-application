# GitHub Candidate Search

**Coursework for school**

![Coursework](https://img.shields.io/badge/Coursework-blue)

Coursework application for browsing public GitHub profiles and saving candidates in the browser.

**Built with:** React, TypeScript, Vite.

## What I built

- Built candidate browsing and saved-candidate screens with React and TypeScript.
- Connected GitHub profile requests to reusable display components and navigation.

## Explore the source

- [src/pages/CandidateSearch.tsx](src/pages/CandidateSearch.tsx) — Candidate browsing.
- [src/api/API.tsx](src/api/API.tsx) — GitHub API requests.
- [src/components/SavedCandidateList.tsx](src/components/SavedCandidateList.tsx) — Saved-candidate interface.

## Run locally

Requires Node.js/npm. From the repository root:

```bash
npm ci
npm run dev
```

Open the address printed by Vite.

## Checks

```bash
npm run build
npm run lint
```

Requests now use the public GitHub API without a personal token; unauthenticated rate limits apply. Never put a personal access token in a `VITE_*` variable: browser code cannot keep it private.

Setup instructions were checked against source; builds and application behavior have not been rerun during this cleanup.
