# ClipFetch — Multi-Platform Video Downloader

**Web tool · Next.js + TypeScript**

A fast, single-purpose video downloader with all resolution handled server-side and a deliberately minimal dependency surface.

> **Source code is private.** This repository documents the architecture and engineering work.

## My role
Full-stack engineer

## Engineering highlights

**App Router architecture.** Next.js with React Server Components — metadata resolution happens server-side, so no extraction credentials or provider logic ever reach the browser.

**End-to-end TypeScript.** 99% TypeScript by volume, with typed contracts between route handlers and client components.

**Server-side processing.** Download resolution runs in route handlers rather than the client, avoiding CORS constraints and keeping the provider surface hidden.

**Minimal dependency surface.** Deliberately built on Next.js and React alone — no UI framework — keeping bundle size small for a single-purpose tool.


## Screenshots

<!-- ![Home](docs/home.png) -->
<!-- ![Result](docs/result.png) -->

_Screenshots pending — see `docs/README.md`._

## Stack

`Next.js` · `TypeScript` · `React`
