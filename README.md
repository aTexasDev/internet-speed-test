# Internet Speed Test

[![internet-speed-test](og-image.png)](https://internet-speed-test.app)


Free internet speed test - check download speed, upload speed, ping, and jitter instantly. No ads, no tracking, no signup. Includes educational content on gaming, streaming, and troubleshooting slow internet.

**Live:** [internet-speed-test.app](https://internet-speed-test.app)

## Tech Stack

- Vanilla JavaScript
- HTML5 / CSS3
- i18n internationalization support
- SEO-optimized content pages

## Features

- Download and upload speed testing
- Ping and jitter measurement
- Network quality scoring
- Gaming speed recommendations
- Streaming speed requirements guide
- Slow internet troubleshooting guide
- Multi-language support

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/aTexasDev/internet-speed-test-app.git
cd internet-speed-test-app
```

2. Open `index.html` in your browser, or serve with any static file server:
```bash
npx serve .
```

## Architecture

This is the frontend application. It communicates with a serverless backend (AWS Lambda + API Gateway) for authenticated operations and data persistence.

- **Authentication:** Google OAuth 2.0
- **Payments:** Stripe Checkout
- **Hosting:** AWS S3 + CloudFront CDN
- **Backend:** AWS Lambda (not included in this repo)

## License

MIT License - see [LICENSE](LICENSE) for details.

---

Built by [T.K. Flautt](https://snapitsoftware.com) | [SnapIT Software](https://snapitsoftware.com)
