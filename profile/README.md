<p align="center">
  <a href="https://vigyanbytes.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://www.vigyanbytes.com/brand/logo-primary-ivory.svg">
      <img src="https://www.vigyanbytes.com/brand/logo-primary-deep.svg" alt="VigyanBytes" width="320">
    </picture>
  </a>
</p>

<h3 align="center">Deep tech. Built to be trusted.</h3>
<p align="center"><em>Engineering what's next.</em></p>

---

**VigyanBytes Solutions Private Limited** is a deep-tech company from Bengaluru, building for the world.
We make AI that companies can actually let near their data: it runs on hardware they own, works with any model,
and keeps a record of everything it does.

**Deep science. Real systems. Trust built in.**

## The problem we work on

Every team now wants AI agents and chatbots in their daily work. Each of those tools can read customer data,
run commands and change production systems. Usually nobody can answer three questions about them:

1. **What did the AI see?** Personal data such as ID numbers, cards and phone numbers often reaches a third-party model.
2. **What was it allowed to do?** Agents can delete, deploy and read credential files, often with no hard stop.
3. **Who decided, and why?** Six months later there is no evidence an auditor or customer would accept.

We build the layer that answers those questions, then the AI products that run on top of it.

## Niyantrak: governance for AI agents and bots

> नियंत्रक, *controller*. **Open source (Apache-2.0) · alpha v0.1.0**

Niyantrak sits between your people, your agents and any AI model, on machines you own. It needs no cloud account.

| | What it does |
|---|---|
| 🔍 **Finds personal data first** | Detects identifiers for India, the EU, the UK, the US and global formats before a model sees them, and swaps in placeholders. It checks real checksums (Verhoeff, Luhn, mod-97, GSTIN), so order numbers and invoice IDs are left alone. |
| 🛑 **Stops dangerous actions** | Hard gates for Claude Code, Codex, Gemini CLI and OpenCode block destructive commands, credential files and unapproved production changes. |
| 🧾 **Records every decision** | 5W activity records (who · whom · what · where · why) in a tamper-evident store, plus an append-only decision log. Records hold counts, never the sensitive values. |
| 🪪 **Uses the identity you already have** | People are identified from the operating system's login (local users, LDAP/AD via SSSD, Entra/authd, Kanidm), never typed in by hand. |
| 🖥️ **Joins machines securely** | Single-use join tokens and signed node cards, with each join approved by an operator. As-built docs and a network map are generated from what actually exists. |
| ✅ **Shows its own proof** | Every commit publishes its tests, coverage and a leak scan alongside the panel screenshots. |

```bash
git clone https://github.com/vigyanbytes/niyantrak && cd niyantrak
python3 -m venv .venv && .venv/bin/pip install .
.venv/bin/niyantrak scan "My PAN is ABCPE1234F, card 4111 1111 1111 1111"
.venv/bin/niyantrak panel        # open http://127.0.0.1:8770
```

👉 **[Get started with Niyantrak](https://github.com/vigyanbytes/niyantrak)**

The free edition is open source. Pro, Enterprise and Government/on-prem editions add fleet-wide policy,
directory integration and support.

## What else we build

| Area | What it means for you |
|---|---|
| **Agentic AI upgrades** | Add governed AI agents to the software you already run, without a rewrite. |
| **Voice and conversation** | Voice bots, transcription, and WhatsApp and video assistants, including Indian languages. |
| **Private AI platforms** | Local GPU and on-prem AI with RAG, used alongside multiple cloud LLMs: your data stays where you decide. |
| **Legacy modernisation** | Move old systems onto data platforms that can run on any cloud or on-prem. |

## Principles

- **Your hardware, your data.** Everything we ship runs on machines you control. Cloud is optional.
- **Any model.** We don't tie you to one vendor; the governance layer works with all of them.
- **Evidence over promises.** Tests, records and proof ship with the code.
- **Global first.** Built in India for the world, with each region's data laws handled as rules rather than forks.

## Get in touch

🌐 [vigyanbytes.com](https://vigyanbytes.com) · ✉️ [info@vigyanbytes.com](mailto:info@vigyanbytes.com) · 📍 Bengaluru, India

<sub>VigyanBytes Solutions Private Limited · CIN U62011KA2026PTC222749</sub>
