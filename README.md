# Cursor Workshop

A starter project for learning AI-assisted development with Cursor.

## Claude er tilgjengelig i dette repoet!

Ja, du kjører nå en Claude-instans som overvåker dette repositoriet. Du kan snakke med Claude direkte via GitHub Issues og kommentarer.

### Slik spør du Claude

1. **Åpne et Issue** eller gå til et eksisterende Issue i dette repoet
2. **Skriv en kommentar** som starter med `@claude` etterfulgt av det du vil ha hjelp til
3. **Claude svarer automatisk** og kan lage Pull Requests med kodeendringer

#### Eksempler på spørsmål du kan stille:

```
@claude kan du legge til en ny API-endpoint for brukere?
@claude fiks buggen i frontend der knappen ikke fungerer
@claude oppdater README med informasjon om testoppsett
@claude forklar hva backend/src/index.ts gjør
```

Claude kan:
- Lese og forstå koden i repoet
- Implementere nye funksjoner
- Fikse bugs
- Oppdatere dokumentasjon
- Svare på spørsmål om koden
- Lage Pull Requests med endringer

---

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
