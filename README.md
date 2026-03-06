# CJK Layout Lab

[简体中文](./README.zh-Hans.md)

## Overview

This is an Astro-based typography lab focused on CJK layout using native Web standards (HTML/CSS first).
Created by Fuqiao Xue.

| Demo | Path | Description |
| :--- | :--- | :--- |
| Writing Modes | `/demos/writing-mode.html` | Contrasts horizontal and vertical text with `writing-mode`, `text-orientation`, multi-column layout, and first-line indent. |
| Traditional Book | `/demos/traditional-book.html` | Simulates a traditional book page with `vertical-rl`, paragraph indent, and proper-noun underline styling. |
| Chinese Line Breaking | `/demos/zh-line-breaking.html` | Prohibition rules for line start and line end. |
| Symbol of death | `/demos/shiwanghao.html` | Chinese symbol of death with †/‡ comparison. |

Upcoming demos include advanced Ruby annotation experiments.

## Development

All commands run from the project root.

| Command | Description |
| :--- | :--- |
| `npm install` | Install project dependencies. |
| `npm run dev` | Start local development server (`localhost:4321`). |
| `npm run build` | Build production static site into `./dist/`. |
| `npm run preview` | Preview the production build locally. |
