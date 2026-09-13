# Privacy Policy

This policy applies to the `hermes-app` OAuth client used by Roman Maliushkin's personal automation tooling (Hermes Agent). The app accesses Google APIs (Calendar, Sheets, Drive, Maps) only on behalf of the developer, never for third-party users.

**Data accessed.** Google Calendar events, Google Sheets spreadsheets, and Google Maps lookups — only for tasks the developer explicitly invokes from their own agent sessions.

**Data storage.** OAuth credentials (access tokens, refresh tokens) are stored locally on the developer's personal server, file-mode `600`. Tokens are never transmitted off-host except to Google's token endpoint during refresh.

**Data sharing.** None. The app has no backend, no telemetry, no third-party SDKs. All API calls go directly from the developer's server to `googleapis.com`.

**Contact.** malyushkinr@gmail.com