<!-- CourierX README -->

<p align="center">
  <img src="https://courierx.dev/assets/logo.png" width="120" alt="CourierX Logo"/>
</p>

<h1 align="center">CourierX</h1>

<p align="center">
  <strong>The universal email router.</strong><br/>
  Open-source infrastructure to connect, route, and orchestrate email across providers.
</p>

<p align="center">
  <a href="https://docs.courierx.dev">Docs</a> •
  <a href="https://courierx.dev">Website</a> •
  <a href="https://www.npmjs.com/org/courierx">NPM</a> •
  <a href="https://twitter.com/courierx">Twitter</a> •
  <a href="mailto:support@courierx.dev">Contact</a>
</p>

<p align="center">
  <a href="https://github.com/courierx"><img src="https://img.shields.io/github/stars/courierx?style=social" alt="GitHub Stars"/></a>
  <a href="https://github.com/courierx/courierx-backend/blob/main/LICENSE"><img src="https://img.shields.io/github/license/courierx/courierx-backend" alt="License"/></a>
  <a href="https://github.com/courierx/courierx-backend/graphs/contributors"><img src="https://img.shields.io/github/contributors/courierx/courierx-backend" alt="Contributors"/></a>
  <a href="https://www.npmjs.com/package/@courierx/client"><img src="https://img.shields.io/npm/v/@courierx/client?color=blue&label=npm" alt="NPM Version"/></a>
  <a href="https://www.npmjs.com/package/@courierx/client"><img src="https://img.shields.io/npm/dm/@courierx/client.svg?color=blue" alt="NPM Downloads"/></a>
</p>

---

> 🚨 **We’re looking for OSS Maintainers & Contributors!**  
> Help shape the future of email infrastructure.  
> → [Get involved](https://github.com/courierx-dev)

---

## ✨ What is CourierX?

CourierX is a **pluggable email router** for teams that want freedom from vendor lock-in.  
Instead of building around a single provider, you get a **unified API** that works across many.

- 🔌 **Multi-provider support** → SendGrid, SES, Postmark, Mailgun, Gmail, and more  
- 🎛 **Smart routing engine** → Cost-aware, deliverability-aware, rule-based  
- 📊 **Unified observability** → Logs, suppressions, analytics in one place  
- 🏗 **Multi-tenant ready** → Workspaces, isolation, security built-in  
- 👐 **OSS & extensible** → Add new providers, swap logic, or self-host  

Think of it as **nginx for your outbound email.**

---

## 🏗 Ecosystem

This GitHub org contains all official CourierX projects:

- **`courierx-backend`** → Core API + routing engine  
- **`courierx-packages`** → TypeScript SDKs & utilities  
- **`courierx-docs`** → Documentation site ([docs.courierx.dev](https://docs.courierx.dev))  
- **`courierx-examples`** → Integration demos & starter kits  

Future growth:  
- **`courierx-dashboard`** → Service dashboard hosted at [courierx.dev](https://courierx.dev)  
- **`courierx-integrations`** → More provider & third-party connectors  

---

## 🚀 Get Started

📖 The fastest way to start is with the docs → [docs.courierx.dev](https://docs.courierx.dev)

Or install the client directly:

```bash
npm install @courierx/client
```

```typescript
import { CourierX } from "@courierx/client";

const cx = new CourierX({ apiKey: process.env.COURIERX_KEY });

await cx.send({
  to: "hello@example.com",
  subject: "Welcome to CourierX",
  body: "Your email router is live 🚀"
});
```
---
## 💡 For Developers

We’re building CourierX in the open, and we’re always looking for collaborators:

- 🛠 **Contribute code** → PRs, new provider adapters, bug fixes  
- 🧪 **Test & validate** → Help battle-test across providers and edge cases  
- 📢 **Spread the word** → Share CourierX with your team or community  

👉 See our [Contributing Guide](./CONTRIBUTING.md) to get started.

---
## 📚 Documentation

- 📖 **Docs site** → [doc.courierx.dev](https://doc.courierx.dev)  
- 🌐 **Main site** → [courierx.dev](https://courierx.dev) (future service dashboard)  

Docs include:  
- Getting Started  
- Provider Integrations  
- API Reference  
- Self-hosting Guide  
- Roadmap  

---

## 📬 Community

- 💡 **Issues** → Use GitHub Issues per repo  
- 🗣 **Discussions** → Coming soon  
- 📧 **Email** → [support@courierx.dev](mailto:support@courierx.dev)  
- 🐦 **Twitter** → [@Usecourierx](https://twitter.com/Usecourierx)  

---

## ⚖️ License

CourierX is licensed under the [MIT License](./LICENSE).

---

<p align="center">
  Built with ❤️ by the CourierX community · <a href="https://docs.courierx.dev">Join us</a>
</p>
