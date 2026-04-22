# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Single-page portfolio/landing page for **ionzaza** — an AI & automation consultancy. The site is a static HTML file (`index.html`) with embedded CSS and vanilla JavaScript. No build system, framework, or package manager.

## Working in this codebase

- **Making changes**: Edit `index.html` directly. CSS and JS are embedded in the file.
- **Previewing**: Open `index.html` directly in a browser, or serve it with any static file server.
- **No testing or linting**: There are no test suites or CI for this project.

## Commit approach

Make **small, frequent commits** rather than batching multiple changes together. Each commit should represent a single logical change (e.g., "Update hero headline", "Fix mobile nav padding", "Add new service card").