# Hi, I'm Courtlandt Harris (@knowthankyew) 👋

> *"Knowledge belongs to life."*

I build **open-source reality engines and platform tooling** engineered to eliminate the information asymmetry between individual consumers and institutional bureaucracies. 

Whether reviewing a residential lease, auditing an itemized hospital bill, verifying overtime on a paystub, evaluating higher-ed ROI, or canceling a predatory subscription, consumers are routinely outgunned by legal boilerplate and dark patterns. The tools below give individuals an uncompromised, local-first legal and technical defense.

---

## 🏛️ The 5 Architectural Invariants

Across the entire consumer reality suite:

1. **Zero Document Egress**: Evaluation runs 100% client-side on local silicon. User documents, form inputs, and PII never touch a network socket.
2. **Amnesiac State Purge (Hard Burn)**: Single-click volatile memory flushing. No persistent tracking or residual forensic trace.
3. **Dynamic Claim Integrity**: UI claims ("Zero Egress", "Enterprise Connected") are programmatically derived from runtime telemetry state—never hardcoded marketing copy.
4. **Dual-Path Observability**: Client privacy is the inviolable default. Enterprise OpenTelemetry (OTLP) collectors attach as an explicit, build-time overlay without source modifications.
5. **Strict License & Process Boundaries**: Permissive **MIT** by default, with isolated container/process boundaries for copyleft engines (GPL-2.0 / AGPL-3.0) to prevent upstream legal contagion.

---

## 🛡️ The KnowThankYew Portfolio

### 🌟 The Ambient Shield (Point-of-Sale Advocate)
* **[knowthankyew-extension](https://github.com/knowthankyew/knowthankyew-extension)** — **Zero-Egress Browser Reality Engine**  
  *Manifest V3 (Chrome, Firefox, Safari) point-of-sale advocate. Evaluates terms of service, auto-renewal traps, forced arbitration clauses, and checkout dark patterns live on local DOM mutations with instant Hard Burn amnesia.*

---

### 🔍 Client-Side Consumer Reality Engines (100% Zero Egress)
* **[lease-audit](https://github.com/knowthankyew/lease-audit)** — **Residential Lease Analyzer**  
  *Flags unlawful lease clauses, security deposit traps, and habitability violations against state tenant protection statutes.*
* **[care-check](https://github.com/knowthankyew/care-check)** — **Medical Bill & Charity Care Engine**  
  *Cross-references itemized hospital charges against federal price transparency mandates and Section 501(r) non-profit charity care thresholds.*
* **[paystub-check](https://github.com/knowthankyew/paystub-check)** — **Wage Statement & FLSA Auditor**  
  *Detects wage theft, overtime miscalculations, and illegal payroll deductions under the Fair Labor Standards Act and state labor codes.*
* **[bill-of-rights-bot](https://github.com/knowthankyew/bill-of-rights-bot)** — **Subscription Agreement Analyzer**  
  *Enforces ROSCA, FTC negative option rules, and state automatic renewal laws (ARL) to generate legally anchored cancellation demand letters.*
* **[warranty-watch](https://github.com/knowthankyew/warranty-watch)** — **Warranty & Lemon Law Analyzer**  
  *Audits product warranties to expose hidden exclusions, arbitration traps, and statutory rights under the Magnuson-Moss Warranty Act and UCC § 2-314.*

---

### 🧠 Platform Services & Machine Learning
* **[event-driven-ftaas](https://github.com/knowthankyew/event-driven-ftaas)** — **Fine-Tuning as a Service (FTaaS)**  
  *Asynchronous, event-driven domain adapter training platform. Tri-model architecture featuring Gemma 2 2B IT production default, SmolLM2-135M edge ONNX export, BitNet 1.58-bit CPU engine, .NET 10 control plane, RabbitMQ broker, PyTorch LoRA worker, and information-theoretic dataset ablation & attribution via the MIT surprisal-service arbiter.*
* **[gradcast](https://github.com/knowthankyew/gradcast)** — **Higher Education ROI Simulator**  
  *Civic open-data engine connecting U.S. Dept of Education College Scorecard metrics with post-graduation HUD fair market rent, local tax brackets, and student debt amortizations (.NET 10 + Vue 3 + Delta Lake).*
* **[mail-stripper](https://github.com/knowthankyew/mail-stripper)** — **Email Privacy Sanitizer**  
  *Strips surveillance tracking pixels, URL redirect wrappers, and spy headers from RFC 822 email payloads with automated headless Playwright unsubscription.*

---

### 🧩 Shared Foundations & Enterprise Deployment
* **[privacy-telemetry](https://github.com/knowthankyew/privacy-telemetry)** — **Core Invariants & Telemetry Monorepo**  
  *Dual-ecosystem runtime powering [`@knowthankyew/privacy-telemetry`](https://www.npmjs.com/package/@knowthankyew/privacy-telemetry) (npm) and [`KnowThankYew.Privacy.Telemetry`](https://www.nuget.org/packages/KnowThankYew.Privacy.Telemetry) (NuGet). Enforces circular memory buffering, allowlists, and dynamic claim validation.*
* **[policy-packs](https://github.com/knowthankyew/policy-packs)** — **Centralized Statutory Intelligence**  
  *Declarative, versioned regulatory rule packs across tenancy, healthcare, wage, and warranty domains with automated daily gazette monitors.*
* **[enterprise-self-host](https://github.com/knowthankyew/enterprise-self-host)** — **Turnkey Private Cloud Harness**  
  *Ready-to-deploy Docker Compose and Helm 3 charts with an air-gapped OpenTelemetry Collector, Prometheus, and Grafana stack for self-hosting reality engines.*

---

### 🖥️ Native Desktop, Systems & Forensic Storage Engines
* **[mac-screen-record](https://github.com/knowthankyew/mac-screen-record)** — **Native macOS Screen & Evidence Studio**  
  *Pure native Swift/ScreenCaptureKit video and audio capture studio. Zero external dependencies, hardware-accelerated ProRes/HEVC encoding, Apple Silicon Neural Engine presenter cutouts, and zero network egress.*
* **[kty-ntfs](https://github.com/knowthankyew/kty-ntfs)** — **User-Space NTFS & Forensic Engine**  
  *Forensic-grade, zero-KEXT NTFS read/write engine for macOS Sonoma & Sequoia built on Apple FSKit. Features in-RAM metadata suppression and streaming cryptographic SHA-256/BLAKE3 alternate data streams.*
* **[genesis](https://github.com/knowthankyew/genesis)** — **High-Performance In-Memory Log & Telemetry Engine**  
  *Single-binary, zero-dependency in-memory telemetry engine in 100% Go standard library. Sustains 277k+ lines/sec over live TCP sockets across 5s time-partitioned doubly-linked SkipLists with $O(1)$ partition eviction, dual-channel QoS priority routing, an embedded zero-CDN Web UI, and `<5ms` Amnesiac Burn.*

---

## 🛠️ Technology Stack Overview

* **Languages:** TypeScript, C# (.NET 10), Python 3.12, Go (1.22 Stdlib), Swift, C / Objective-C
* **Frontend / Web:** React 19, React 18, Vue 3, Vite, Manifest V3, WebGPU/WASM, TailwindCSS
* **Backend / Systems:** ASP.NET Core, FastAPI, RabbitMQ, Apple FSKit, PyTorch, PEFT/LoRA, ONNX
* **Observability:** OpenTelemetry (OTel/OTLP), W3C Distributed Tracing, Prometheus, Grafana, MLflow
* **Supply Chain & Integrity:** Sigstore Cosign, CycloneDX SBOM, SLSA Provenance, ReDoS-Free Verification

---

<div align="center">
  <sub>All client reality engines are strictly open source and dedicated to consumer privacy by design.</sub>
</div>
