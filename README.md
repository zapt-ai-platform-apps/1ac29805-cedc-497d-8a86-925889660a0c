# Fitness Club

This is a simple React application that welcomes you to the Fitness Club. It provides a minimal home screen and a PWA setup.

Below is a list of journeys you can follow in this app:

1. [View Homepage](docs/journeys/view-homepage.md) - Access the main Fitness Club welcome screen

## Environment Variables

Please ensure these environment variables are set, typically in the `.env` file:

- COCKROACH_DB_URL: (not currently used, but required for Drizzle ORM if implemented in the future)
- NPM_TOKEN: (not used in this example, but included for completeness)
- VITE_PUBLIC_APP_ID: used for linking with Sentry and ZAPT
- VITE_PUBLIC_APP_ENV: tracks the environment (e.g., development, production)
- VITE_PUBLIC_SENTRY_DSN: Sentry DSN for error logging
- VITE_PUBLIC_UMAMI_WEBSITE_ID: Umami analytics ID for usage tracking

## External Services

- [Sentry](https://sentry.io): Used for error logging on both front-end and back-end.
- [Progressier](https://progressier.com/): Adds PWA support and service worker to the app.
- [Umami](https://umami.is/): Used for analytics to track basic usage stats.
