# Messo Status

[![Uptime CI](https://github.com/auroracapital/messo-status/workflows/Uptime%20CI/badge.svg)](https://github.com/auroracapital/messo-status/actions?query=workflow%3A%22Uptime+CI%22)
[![Response Time CI](https://github.com/auroracapital/messo-status/workflows/Response%20Time%20CI/badge.svg)](https://github.com/auroracapital/messo-status/actions?query=workflow%3A%22Response+Time+CI%22)
[![Graphs CI](https://github.com/auroracapital/messo-status/workflows/Graphs%20CI/badge.svg)](https://github.com/auroracapital/messo-status/actions?query=workflow%3A%22Graphs+CI%22)
[![Static Site CI](https://github.com/auroracapital/messo-status/workflows/Static%20Site%20CI/badge.svg)](https://github.com/auroracapital/messo-status/actions?query=workflow%3A%22Static+Site+CI%22)
[![Summary CI](https://github.com/auroracapital/messo-status/workflows/Summary%20CI/badge.svg)](https://github.com/auroracapital/messo-status/actions?query=workflow%3A%22Summary+CI%22)

Live uptime monitor and status page for [Messo](https://messo.cc) — the AI manager for WhatsApp inboxes.

**Status page:** [status.messo.cc](https://status.messo.cc)

Powered by [Upptime](https://upptime.js.org), running entirely on GitHub Actions and GitHub Pages.

<!--start: status pages-->
| URL | Status | History | Response Time | Uptime |
| --- | ------ | ------- | ------------- | ------ |
| [Marketing site (messo.cc)](https://messo.cc) | 🟩 Up | [marketing-site-messo-cc.yml](https://github.com/auroracapital/messo-status/commits/HEAD/history/marketing-site-messo-cc.yml) | — | — |
| [API (api.messo.cc)](https://api.messo.cc/healthz) | 🟩 Up | [api-api-messo-cc.yml](https://github.com/auroracapital/messo-status/commits/HEAD/history/api-api-messo-cc.yml) | — | — |
| [Dev marketing site (dev.messo.cc)](https://dev.messo.cc) | 🟩 Up | [dev-marketing-site-dev-messo-cc.yml](https://github.com/auroracapital/messo-status/commits/HEAD/history/dev-marketing-site-dev-messo-cc.yml) | — | — |
| [Dev API (api-dev.messo.cc)](https://api-dev.messo.cc/healthz) | 🟩 Up | [dev-api-api-dev-messo-cc.yml](https://github.com/auroracapital/messo-status/commits/HEAD/history/dev-api-api-dev-messo-cc.yml) | — | — |
<!--end: status pages-->

## How it works

- GitHub Actions checks each endpoint every 5 minutes
- Response time is recorded every 6 hours and committed to git
- Graphs of response time are generated daily
- GitHub Issues are opened automatically when an endpoint goes down and closed when it recovers
- Incident reports are posted as issue comments

## Monitored endpoints

| Endpoint | URL |
|----------|-----|
| Marketing site | https://messo.cc |
| API health | https://api.messo.cc/healthz |
| Dev marketing site | https://dev.messo.cc |
| Dev API health | https://api-dev.messo.cc/healthz |

## License

- Code: [MIT](LICENSE)
- Data in the `./history` directory: [Open Database License](https://opendatacommons.org/licenses/odbl/1-0/)
