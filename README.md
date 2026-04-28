# ADHD Command Center

A Progressive Web App (PWA) for ADHD management and productivity.

## Features

- PWA with offline support
- Service worker for caching
- Responsive design
- Custom app icons for multiple device sizes

## Tech Stack

- HTML5
- Nginx (web server)
- Docker for containerization

## Quick Start

### Using Docker

```bash
docker-compose up -d
```

Access the app at: http://localhost:3333

### Stopping the App

```bash
docker-compose down
```

## Project Structure

```
.
├── index.html          # Main application
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── nginx.conf         # Nginx configuration
├── docker-compose.yml # Docker setup
├── icons/             # App icons (various sizes)
└── README.md          # This file
```

## License

MIT
