

## 🧪 WP Consent API Simulation with AdOpt CMP

This project simulates the integration between the [AdOpt CMP](https://goadopt.io) and the [WP Consent API](https://developer.wordpress.org/plugins/wp-consent-api/) by listening to consent events and displaying them on screen.

### ✅ What it does

- Listens for:

  - `wp_consent_type_defined`
  - `wp_set_consent(category, status)`

- Logs these events in a readable UI
- Useful for testing how your CMP setup triggers WP Consent API behavior

### 🚀 How to run

You can use any static server. The easiest way:

```bash
npm install -g live-server
live-server
```

Then open `index.html` in your browser.

### ⚠️ Disclaimer

> This is a **test environment** intended only for development and debugging.
> No real consent data or cookies are managed.
