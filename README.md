<h1 align="center">🧰 MyCyberTool</h1>

<p align="center">
  <strong>An offensive-security Swiss Army knife in your browser.</strong><br>
  Recon, web testing, TLS, cloud, secrets, JWT, CyberChef — all in one privacy-first web app at <a href="https://mycybertool.com">mycybertool.com</a>.
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/osherassor/MyCyberTool?style=for-the-badge&logo=github&color=ffd700" alt="Stars">
  <img src="https://img.shields.io/github/last-commit/osherassor/MyCyberTool?style=for-the-badge&logo=git&color=00d4aa" alt="Last commit">
  <img src="https://img.shields.io/badge/live-mycybertool.com-ff4081?style=for-the-badge&logo=firefoxbrowser&logoColor=white" alt="Live">
  <img src="https://img.shields.io/badge/license-as--is-informational?style=for-the-badge" alt="License">
</p>

<p align="center">
  <a href="https://mycybertool.com">🌐 Open the live site →</a>
</p>

---

## What is this?

The thing you wish was a single tab when you're doing security work. Instead of context-switching between online security headers checkers, JWT debuggers, CyberChef, a separate CORS tool, and yet another DNS lookup site — they're all here, in one place, with consistent UX.

**Privacy first:** inputs are processed on the spot. Nothing's stored.

## ✨ What's inside

### 🔎 Reconnaissance & discovery

| Tool | What it does |
|---|---|
| 🌐 **Subdomains** | Enumerate using curated wordlists |
| 📋 **RDAP** | Modern WHOIS-style registration data for domains and IPs |
| 🧭 **DNS resolver** | A / AAAA / CNAME / MX / TXT / NS and more |
| 🧬 **Tech fingerprint** | Identify frameworks, CMS, libraries, hosting |
| ⚠️ **IP reputation** | Quick trust signals for an IP |
| 🪤 **Takeover checker** | Spot subdomain takeover risks |

### 🛡️ Web security testing

| Tool | What it does |
|---|---|
| 🪪 **Security headers** | CSP, X-Frame-Options, X-Content-Type-Options, Referrer-Policy… |
| 🌍 **CORS checker** | Validate behavior across methods and origins |
| 🔒 **HSTS checker** | Verify config + preload readiness |
| 🪟 **Clickjacking checker** | Test framing protections |
| 🚪 **403 bypass tester** | Common path / case / verb / header tricks |
| 🪢 **SRI checker** | Generate / verify Subresource Integrity hashes |

### 🔐 TLS & networking

- 📜 **TLS checker** — cert chain, expiration, config signals

### ☁️ Cloud & storage

- 🪣 **Bucket explorer** — probe public buckets, enumerate where permitted
- 🔍 **S3 audit** — misconfig + exposure pattern checks

### 🕵️ Secrets & sensitive data

- 🔑 **Secrets scanner** — pages, repos, or text blobs for keys / tokens / creds

### 🛠️ Data transformation & utilities

- 🍳 **CyberChef** (embedded) — encoding, decoding, encryption, analysis
- 🎫 **JWT editor** — decode, inspect, experiment
- 📐 **JSON / XML tools & beautifier** — pretty-print, minify, convert
- 📚 **Wordlists** — built-in lists for discovery and tuning

### ✨ UX

- ♿ **Accessibility** — widget + checks baked into every screen
- 🌗 **Theme + i18n** — dark mode, multilingual

## 🌟 Philosophy

- 🛡️ **Privacy-first** — just-in-time processing, nothing persisted
- 🧭 **Transparent** — clear outputs with actionable guidance, not opaque scores
- 🚀 **Pragmatic** — fast checks for triage, validation, and demos

## 🤝 Pairs well with

- 🧪 **[passive-pentest-profiler](https://github.com/osherassor/passive-pentest-profiler)** — Chrome extension for the *passive* side: cookies, JWTs, secrets in JS bundles. MyCyberTool then handles active server-side checks (CORS, 403 bypass, S3 audit).
- 📚 **[AwesomeWL](https://github.com/osherassor/AwesomeWL)** — the wordlists section uses these.
- 🌐 **[selfit](https://github.com/osherassor/selfit)** — when you need to *find* the targets first (web service discovery, screenshots, fuzzing), then bring them here for analysis.

## ⚖️ Responsible use

Ethical security testing and education only. Test only what you own or are explicitly authorized to assess. You're responsible for legal + policy compliance.

## 💬 Feedback

Suggestions or feature requests welcome.

- 👤 [Osher Assor](https://www.linkedin.com/in/osher-assor/) on LinkedIn
- 🌐 [mycybertool.com](https://mycybertool.com)

## 📄 License

Code and content are provided as-is, no warranty. Review and include applicable notices if you redistribute.
