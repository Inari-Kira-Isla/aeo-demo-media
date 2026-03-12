# aeo-demo-media

## Overview
AEO Demo template designed for the media industry. It showcases how to structure HTML to be "AI-friendly" using Schema.org, llms.txt, and FAQ markup for better visibility in AI search results (SGE, ChatGPT, etc.).

## Tech Stack
- **HTML5**: Core markup language.
- **Schema.org**: JSON-LD for structured data (NewsArticle, FAQ).
- **CSS**: Basic styling (optional).

## Architecture
- `index.html`: The main entry point containing the content, semantic tags, and embedded JSON-LD.
- **AI-Friendly Features**: 
  - `<link rel="llms.txt">` tag.
  - FAQ `<script type="application/ld+json">`.

## Commands
- **View**: Simply open `index.html` in any modern web browser.
- **Validate**: Use Google's Rich Results Test to verify Schema markup.

## Coding Style
- Semantic HTML (use `<article>`, `<header>`, `<main>`).
- Valid JSON-LD for all schema types.
- Clean, readable indentation.

## Important Rules
- **Schema**: Ensure all schema data matches the visible content.
- **AI Access**: Do not block AI bots (User-agents: GPTBot, Google-Extended) in `robots.txt`.
- **Maintain**: Keep the `llms.txt` link in the `<head>`.