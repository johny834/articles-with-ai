# A01 API Security PoC

> 🔓 Proof of Concept demonstrating authentication bypass vulnerability

## Overview

This PoC demonstrates critical security vulnerabilities discovered in the A01 News API backend (`backend-cap10.research-model-y.xyz`).

## Vulnerabilities

| Severity | Issue |
|----------|-------|
| 🔴 **CRITICAL** | Authentication bypass - `/login` accepts ANY credentials |
| 🟠 **HIGH** | Full API schema exposed at `/docs`, `/redoc`, `/openapi.json` |
| 🟡 **MEDIUM** | Server version disclosure (uvicorn) |

## Demo

Open `index.html` in a browser to run the interactive PoC:

1. **Authentication Bypass** - Login with any email/password combination
2. **Access User Data** - Fetch profile data with the obtained token
3. **Search Articles** - Full API access demonstration

## Live Demo

👉 [View Demo](https://johny834.github.io/articles-with-ai/)

## Affected System

- **API:** `https://backend-cap10.research-model-y.xyz`
- **App:** A01: Your Personal News Agent (iOS)
- **App Store ID:** 6745206011

## Responsible Disclosure

This PoC includes a built-in report generator for responsible disclosure purposes.

## Disclaimer

This tool is for educational and authorized security testing purposes only. Use responsibly.

## License

MIT
