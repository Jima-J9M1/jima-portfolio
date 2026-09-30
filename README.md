# Jima Dube — Portfolio

Personal portfolio of Jima Dube, ML & data engineer in Addis Ababa.

A single static page (`index.html`, no build step) with a cursor-reactive particle hero, an animated RAG pipeline trace, a pinned horizontal reel of featured projects, and a filterable project library pulled from [github.com/Jima-J9M1](https://github.com/Jima-J9M1).

## Deploy

- **GitHub Pages:** pushes to `main` deploy automatically via `.github/workflows/pages.yml`.
- **Vercel:** import this repo at vercel.com/new — framework preset "Other", no build command.

## Edit content

Projects, featured builds and the tech stack are plain arrays at the top of the `<script>` block in `index.html` (`featured`, `projects`, `groups`).
