# Home Server

A Docker-based home server setup featuring OpenWebUI for Ollama and automated updates.

## Services

- **OpenWebUI**: A web interface for Ollama, accessible at `http://localhost:3000`
- **Watchtower**: Automated Docker container updates

## Prerequisites

- Docker and Docker Compose
- Ollama running locally (for OpenWebUI)

## Setup

1. Clone this repository
2. Ensure Ollama is running locally on port 11434
3. Start the services:
   ```bash
   docker compose up -d
   ```

## Maintenance

This repository uses Renovate for automated dependency updates. Updates are automatically merged for patch versions, while major updates require manual review.

## License

MIT
