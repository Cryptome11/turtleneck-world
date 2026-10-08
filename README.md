# TURTLENECK WORLD 🐢

A browser-based multiplayer block world designed around shareable world URLs, inspired by the social-link model used by TweetCraft.

## Run locally
1. Install Node.js LTS.
2. Open this folder in Command Prompt.
3. Run `npm install`.
4. Run `npm start`.
5. Open `http://localhost:3000`.
6. Click **Create New World**.
7. Share the resulting `/world/<id>` URL.

## What is included
- Unique world URLs
- Real-time multiplayer per world
- Player names
- Block placement/removal
- Chat
- TURTLENECK branding
- Open Graph metadata for link previews

## Production note
The current server stores world state in memory. For a permanent public service, add a persistent database/world store and deploy the Node/WebSocket server on a host that supports long-lived WebSocket connections. Your `turtleneck.site` domain can then point to the deployed service.
