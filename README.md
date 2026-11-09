# Markdown Notes — Web App

A small single-page Markdown notes app. Write Markdown on the left, see a live
preview on the right. Notes are saved automatically in the browser
(`localStorage`) — nothing is uploaded anywhere.

## Features

- **Live Markdown preview** — headings, bold/italic, lists, links, inline code,
  fenced code blocks, blockquotes, tables and horizontal rules (small built-in
  parser, no external library needed)
- **Multiple notes** — create, rename, delete; notes are listed newest first
- **Auto-save** — every keystroke is saved to `localStorage`
- **Export** — download any note as a `.md` file
- **Responsive** — editor and preview stack vertically on small screens

## How to run

Just open `index.html` in any modern browser — no build step, no server, no
internet needed.

## What was practiced

- Writing a small Markdown parser in plain JavaScript (line-based, with inline
  formatting)
- `localStorage` persistence and state management without a framework
- Clean single-file HTML/CSS/JS structure
