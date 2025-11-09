# Creative Agents Bridge 🧠

A universal WebSocket bridge that connects creative agents like Photoshop or Premiere Pro
to your web applications for automated content generation.

## Features
- Connects to multiple UXP / CEP agents (Photoshop, Premiere, etc.)
- Receives commands from the front-end (`social-media-manager-front`)
- Dispatches jobs and collects render results
- Uploads exports to S3 or any custom API
- Secure token-based authentication
- Reusable for any local creative automation setup

## Repositories
- 🎨 photoshop-ws-agent — UXP plugin for Photoshop
- 🎬 premiere-cep-agent — CEP extension for Premiere Pro
- 🌐 social-media-manager-front — Vue 3 front-end dashboard

## Dev
```bash
pnpm install
pnpm dev