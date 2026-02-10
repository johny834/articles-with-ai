# (PoC) News with AI

> 📰 AI-powered news feed aggregator

A modern web app that fetches and displays articles from Bluesky and Reddit with AI-generated titles and summaries.

## Features

- **🏠 News Feed** — Browse latest articles by category
- **🔍 Search** — Semantic search powered by embeddings
- **❤️ Favorites** — Save articles for later
- **📱 Responsive** — Works on desktop and mobile
- **🤖 AI Summaries** — Every article includes an AI-generated summary
- **🔄 Auto-auth** — Seamless background authentication

## Categories

- Technology, Science, Business, Politics
- Sports, Entertainment, Health, World

## Live Demo

👉 [View Demo](https://johny834.github.io/articles-with-ai/)

## API

Powered by the Bottlecap AI API (`backend-cap10.research-model-y.xyz`)

### Endpoints Used

| Endpoint | Description |
|----------|-------------|
| `POST /authentication/login` | Get access token |
| `POST /authentication/refresh` | Refresh token |
| `POST /embeddings/` | Create search embedding |
| `POST /articles/search` | Search articles |
| `GET /favorites/` | List favorites |
| `POST /favorites/{id}` | Add favorite |
| `DELETE /favorites/{id}` | Remove favorite |

## Tech Stack

- Vanilla JavaScript (no frameworks)
- CSS Grid & Flexbox
- LocalStorage for token persistence

## License

MIT
