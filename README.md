# Carlos Projects

Building open-source security infrastructure for AI agents, MCP servers, RAG pipelines, and model supply chains.

## Focus

- **MCP / A2A red-team testing** — Active exploitation before attackers
- **Prompt injection detection** — Static + LLM-assisted scanning of any URL
- **Agent firewalling and honeypots** — Policy-based perimeter for websites
- **RAG and fine-tuning security** — Adversarial data detection in pipelines
- **AI model provenance and integrity** — SBOM, manifests, supply chain auditing
- **Agent incident forensics** — Post-incident reconstruction and replay

## Flagship Projects

### [MCPwn](https://github.com/Carlos-Projects/mcpwn)
Active offensive security testing framework for MCP servers. Sends real attack payloads, confirms command injection, SSRF, blind RCE, tool poisoning, and path traversal. Includes a deliberately vulnerable lab server for safe practice.

### [Palisade Scanner](https://github.com/Carlos-Projects/palisade-scanner)
Scan URLs, HTML, and documents for hidden prompt injection, invisible instructions, metadata attacks, zero-width characters, and adversarial content targeting AI agents. [Try it live](https://huggingface.co/spaces/Syntho/palisade-scanner).

### [AgentGate](https://github.com/Carlos-Projects/agentgate)
Policy-based firewall and honeypot middleware for AI agents accessing websites. Detects automated traffic, scores risk, enforces graduated responses (allow → challenge → sandbox → block), and provides real-time observability.

---

## Ecosystem

```
Carlos-Projects
│
├── mcpwn               Attack MCP servers before attackers do.
├── palisade-scanner    Scan web content before agents consume it.
├── agentgate           Control how agents access your website.
├── mcpscope            Centralize scanner results and security posture.
├── mcpguard            Runtime security proxy for MCP/A2A protocols.
│
├── RAGuard             Test retrieval pipelines for adversarial data.
├── AIShield            Secure fine-tuning datasets, LoRA adapters, weights.
├── modelchain          Generate SBOM/provenance for AI model supply chains.
│
├── mcp-taxonomy        Canonical classification taxonomy for MCP security.
├── agentforensics      Post-incident forensics for AI agent behavior.
└── threatlens          Threat intelligence aggregation and correlation.
```

## Maturity

| Tier | Projects | Description |
|------|----------|-------------|
| **Production-ready** | mcpwn, palisade-scanner, agentgate | CLI-installable, CI/CD, tested, documented |
| **Experimental** | RAGuard, AIShield, modelchain, agentforensics | Working but evolving — APIs may change |
| **Research / Taxonomy** | mcp-taxonomy, threatlens | Foundational standards and detection data |

## Thesis

As AI agents gain tools, memory, browsers, and payment capabilities, the attack surface shifts from prompts to operational environments. This account builds security primitives for that transition — from red-teaming MCP tool servers to scanning web content for adversarial instructions to auditing model supply chains.

---

### Public Sector

[**veeduria**](https://github.com/Carlos-Projects/veeduria) — Platform for algorithmic auditing of public procurement across Latin America (Colombia, Mexico, Argentina, Peru). NLP-based contract classification, anomaly detection, ML risk scoring.

---

`carlos@aiagentobservatory.org`
