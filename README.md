# JioSaavn API Pro

An extended TypeScript/Bun API implementation for working with JioSaavn music data.

## Requirements

- Bun
- Node-compatible development environment when required by the tooling
- Wrangler for Cloudflare deployment if deploying the service there

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

Build:

```bash
bun run build
```

Start the built server:

```bash
bun start
```

## Testing and Quality

```bash
bun run test
bun run lint
bun run format
```

## Deployment

The repository provides a Wrangler deployment script:

```bash
bun run deploy
```

Review the Wrangler configuration and required environment variables before deploying.

## API Documentation

Check the source modules and API reference configuration for the currently available routes and response schemas.

## Notes

The API depends on an external music service, so upstream changes may affect availability.
