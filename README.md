# AionScript™ — The Language of Intelligent Data

> **Version:** v1.0 LTF (Long-Term Foundation)  
> **Spec:** [aionscript.com](https://aionscript.com) · [Docs](https://aionscript.com/docs) · [License](#license) · [Patent Pending](#patent)

AionScript™ is a human-readable data language (.aion) that compiles to canonical, verifiable JSON (.sJson). It brings **meaning**, **trust**, and **governance** directly into the data layer — enabling AI-native systems that are more reliable, explainable, and future-proof.

---

## ✨ Key Concepts

- **.aion**: Human-readable authoring format with symbols, roles, and intent.
- **.sJson**: Structured JSON output with embedded semantics, evidence, and governance.
- **Trust by Design**: Every object can include @hash, @sig, @provenanceChain, and @policy.
- **Open Source SDKs**: Canonicalize, sign, validate, and emit .sJson from .aion.

```aion
{A}
title: "Q1 Plan"
owner @role: "PM"
goals: +["Launch alpha", "Measure retention"]
@directive(generate): executive summary
{/A}
```

---

## 🚀 What You Can Do with AionScript

- 🔒 **Embed Trust**: Use @hash and @sig for verifiable artifacts.
- 📊 **Model-Aware Data**: Use @confidence, @coverage, @embedding, and @evidence.
- ⚖️ **Built-In Governance**: Set @classification, @consent, @retention directly in data.
- 🔁 **Interoperable**: Transforms to JSON, integrates with APIs, DBs, pipelines.
- 🔎 **Auditable**: Record provenance with @provenanceChain.

---

## 📦 Packages

| Tool        | Description                                      | Status        |
|-------------|--------------------------------------------------|---------------|
| `aionc`     | CLI: Parse, validate, and emit .sJson            | ✅ Stable      |
| `@aionscript/sdk` | TypeScript SDK for authoring/validation      | ✅ Stable      |
| `aion-signer` | Add signatures to .sJson using Ed25519         | 🔜 Coming soon |
| `aion-vscode` | VSCode syntax + preview plugin                 | 🔜 Planned     |

---

## 🧠 Smart Semantics

All `.sJson` objects can include:

- `@type`, `@context` — Semantic clarity
- `@confidence`, `@evidence` — Model grounding
- `@timestamp`, `@source` — Provenance
- `@classification`, `@license` — Governance
- `@hash`, `@sig` — Verifiability

Example:
```json
{
  "@type": "Task",
  "title": "Write launch blog",
  "@confidence": 0.97,
  "@evidence": ["doc:product-spec"],
  "@classification": "public",
  "@timestamp": "2025-10-19T12:00:00Z",
  "@hash": "sha256:abc123…"
}
```

---

## 📚 Learn More

- [📖 Aion Language (.aion)](https://aionscript.com/aion)
- [📘 Structured JSON (.sJson)](https://aionscript.com/sjson)
- [📄 Docs Overview](https://aionscript.com/docs)
- [📍 Why AionScript?](https://aionscript.com/#why-aionscript)

---

## 🔐 License

- **Spec**: [AOSL-1.0](https://aionscript.com/license) — Aion Open Specification License
- **SDK/CLI**: MIT — [LICENSE](./LICENSE)
- **Engine**: Proprietary — Core policy/provenance/canonicalization not public

## ™ Trademark

- **AionScript™**, **AionScript DB™**, **AionScript Cloud™**, **AionScript World™** are trademarks of AionScript Inc.

## 📜 Patent

AionScript core features (canonicalization, trust layers, execution model) are **patent pending**.

---

## 📣 Join Us

- [🌐 Website](https://aionscript.com)
- [💻 GitHub](https://github.com/aionscript)
- [🧪 Early Access](https://aionscript.com/early)
- [📰 Press & Media](https://aionscript.com/press)
- [📬 Contact](https://aionscript.com/#contact)

> “Express meaning, not just structure.” — AionScript™
