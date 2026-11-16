# Node.js TypeScript Docker Template

A minimal TypeScript and Node.js starter template with Docker support for building lightweight, containerized services.

## Features

- Node.js 24
- TypeScript
- Hot reload with tsx
- Unit testing with Vitest
- Multi-stage Docker build
- Docker Compose
- GitHub Actions CI

## Getting started

Create a new repository using **Use this template** on GitHub.

Clone your new repository and install dependencies:

```bash
npm ci
```

### Development

Start the application with hot reload:

```bash
npm run dev
```

### Production

Build and start the application:

```bash
npm run build
npm start
```

## Testing

Run all tests:

```bash
npm test
```

Run tests in watch mode:

```bash
npm run test:watch
```

Check TypeScript types:

```bash
npm run typecheck
```

## Docker

Build and run the application:

```bash
docker compose up -d --build
```

View logs:

```bash
docker compose logs -f
```

Stop the application:

```bash
docker compose down
```

## Project structure

```text
.
├── .github/
│   └── workflows/
│       └── ci.yml
├── src/
│   └── index.ts
├── tests/
│   └── index.test.ts
├── .dockerignore
├── .gitignore
├── Dockerfile
├── compose.yml
├── package.json
├── package-lock.json
├── tsconfig.json
└── README.md
```

## License

MIT License.
