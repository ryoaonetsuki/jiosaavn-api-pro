# JioSaavn API Pro

An extended TypeScript/Bun API implementation for working with JioSaavn music data.

## Requirements

- Bun
- Wrangler for Cloudflare deployment when required

## Installation

```bash
git clone https://github.com/ryoaonetsuki/jiosaavn-api-pro.git
cd jiosaavn-api-pro
bun install
```

## Development

```bash
bun run dev
```

Build and start:

```bash
bun run build
bun start
```

## Testing and Quality

```bash
bun run test
bun run lint
bun run format
```

## Deployment

The project provides a Wrangler deployment script:

```bash
bun run deploy
```

Review Wrangler configuration and required environment variables first.

## API

Check the source modules and API reference configuration for the current routes and response schemas.
