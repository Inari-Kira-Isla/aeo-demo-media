# aeo-demo-media

## Project
AEO Demo — media industry template with Schema.org, llms.txt, FAQ, and AI-friendly markup. Language: HTML.

## Conventions
- Use semantic HTML5 elements
- Include Schema.org JSON-LD structured data on every page
- Generate llms.txt for AI crawler compatibility
- Implement FAQ schema for rich results
- Keep HTML minimal and readable

## Naming
- Use lowercase with hyphens for file names (e.g., `article-schema.html`)
- Name JSON-LD files with `-schema.json` suffix

## Architecture
- Static HTML files with embedded or linked Schema.org data
- Standalone demo templates showcasing AEO best practices
- No build tools required—just pure HTML with structured markup

## Commands
- No build commands needed; all files are static HTML
- Validate structured data with Google's Rich Results Test

## Do Not
- Avoid adding client-side JavaScript that modifies content structure
- Do not use non-semantic `<div>` tags when semantic elements exist
- Skip dynamic server-side rendering—keep it static