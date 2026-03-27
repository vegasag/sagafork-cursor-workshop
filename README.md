# Cursor Workshop

A starter project for learning AI-assisted development with Cursor.

## Claude AI Assistant

This repository is integrated with Claude, an AI assistant from Anthropic. Claude can help you with code, answer questions, and implement changes directly in this repository.

### How to ask Claude for help

You can interact with Claude by mentioning `@claude` in GitHub Issues or Pull Requests:

1. **Open or comment on an issue** — write `@claude` followed by your request in English or Norwegian.
2. **Examples:**
   - `@claude add a search feature to the blog`
   - `@claude fix the bug in the API endpoint`
   - `@claude explain how the frontend works`
   - `@claude oppdater README og legg til dokumentasjon`
3. Claude will automatically create a pull request with the implementation.

> Yes — you are running a live Claude instance! This README was updated by Claude in response to a request in issue #1.

## Project Structure

```
cursor-workshop/
├── frontend/          # Next.js application
├── backend/           # Express API server
└── micros/            # Micro-frontends (navbar, footer)
```

## Getting Started

### Install dependencies

```bash
npm install
```

### Run development servers

```bash
npm run dev
```

This starts both:
- Frontend: http://localhost:3000
- Backend: http://localhost:3001

### Run individually

```bash
npm run dev:frontend    # Frontend only
npm run dev:backend     # Backend only
```

## API Endpoints

- `GET /api/posts` - List blog posts
- `GET /api/posts/:slug` - Get single post
- `GET /api/tags` - Get all tags
- `GET /api/health` - Health check
