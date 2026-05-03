<div align="center">

# MoleAPI

**One API endpoint for every major AI model.**

[![Website](https://img.shields.io/badge/Website-moleapi.com-blue?style=flat-square)](https://www.moleapi.com)
[![Docs](https://img.shields.io/badge/Docs-docs.moleapi.com-green?style=flat-square)](https://docs.moleapi.com)
[![OpenAI Compatible](https://img.shields.io/badge/OpenAI-Compatible-orange?style=flat-square)](https://www.moleapi.com/en/solutions/openai-compatible-gateway)

</div>

---

## What is MoleAPI?

[MoleAPI](https://www.moleapi.com) is an open-source AI API gateway that gives you a **single, unified OpenAI-compatible endpoint** to access all major large language model providers — OpenAI, Anthropic, Google, and more. Stop juggling multiple SDKs, keys, and billing dashboards: MoleAPI brings them all together.

> **Base URL:** `https://api.moleapi.com/v1`

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🔌 **Unified Endpoint** | One `base_url` for GPT, Claude, Gemini, Qwen, and more |
| 🔄 **OpenAI-Compatible** | Drop-in replacement — just change your `base_url` and `api_key` |
| 🔑 **Centralized Key Management** | Create, rotate, and share API keys from a single dashboard |
| 📊 **Usage & Spend Tracking** | Per-model analytics, logs, and spending limits |
| ⚡ **Rapid Model Updates** | New models added quickly after launch |
| 🛠️ **SDK & Tool Support** | Works with OpenAI SDK, Anthropic SDK, Cursor, Claude Code, and more |

---

## 🚀 Quick Start

Just swap the `base_url` and use your MoleAPI key — no other code changes needed.

**Python (OpenAI SDK)**

```python
from openai import OpenAI

client = OpenAI(
    api_key="YOUR_MOLEAPI_KEY",
    base_url="https://api.moleapi.com/v1"
)

response = client.chat.completions.create(
    model="gpt-4o",
    messages=[{"role": "user", "content": "Hello, MoleAPI!"}]
)

print(response.choices[0].message.content)
```

**Node.js (OpenAI SDK)**

```javascript
import OpenAI from "openai";

const client = new OpenAI({
  apiKey: "YOUR_MOLEAPI_KEY",
  baseURL: "https://api.moleapi.com/v1",
});

const response = await client.chat.completions.create({
  model: "claude-sonnet-4-5",
  messages: [{ role: "user", content: "Hello, MoleAPI!" }],
});

console.log(response.choices[0].message.content);
```

---

## 🤖 Supported Models

MoleAPI supports the latest models from all major providers:

| Provider | Models |
|---|---|
| **OpenAI** | GPT-4o, GPT-4o mini, o1, o3, and more |
| **Anthropic** | Claude Opus, Claude Sonnet, Claude Haiku |
| **Google** | Gemini 2.5 Pro, Gemini 2.5 Flash, and more |
| **Alibaba** | Qwen series |
| **And more** | New providers and models added regularly |

View the full model list at [moleapi.com/en/models](https://www.moleapi.com/en/models).

---

## 🧩 Compatible Tools & Integrations

MoleAPI works out of the box with popular AI tools and development environments:

- **IDEs & Coding Assistants**: Cursor, Claude Code, Continue.dev
- **Chat Clients**: NextChat, LobeChat, Cherry Studio, OpenCat
- **Frameworks**: LangChain, LlamaIndex, AutoGen, CrewAI
- **Official SDKs**: OpenAI Python/Node.js SDK, Anthropic SDK

See all integrations at [moleapi.com/en/integrations](https://www.moleapi.com/en/integrations).

---

## 📂 Repositories

| Repo | Description |
|---|---|
| [MoleAPI/moleapi](https://github.com/MoleAPI/moleapi) | Open-source AI API gateway (forked from new-api, maintained by MoleAPI) |

---

## 📚 Documentation & Links

- 🌐 **Website**: [moleapi.com](https://www.moleapi.com)
- 📖 **Documentation**: [docs.moleapi.com](https://docs.moleapi.com)
- ⚡ **Quick Start**: [docs.moleapi.com/en-US/docs/getting-started](https://docs.moleapi.com/en-US/docs/getting-started)
- 🔧 **API Reference**: [docs.moleapi.com/en-US/docs/api](https://docs.moleapi.com/en-US/docs/api)

---

<div align="center">

Built with ❤️ by the MoleAPI team &nbsp;|&nbsp; [moleapi.com](https://www.moleapi.com)

</div>