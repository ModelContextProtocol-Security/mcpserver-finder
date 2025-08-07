---
title: MCP Server Evaluation Template
version: 0.3
date: 2025‑08‑06
tags: [template, MCP, evaluation, draft]
aliases: []
status: draft
---
# MCP Server Evaluation Template  
*Duplicate and fill for each server.*

> **Draft Template:** This evaluation framework is under active development and will be refined based on practical usage and community feedback. The criteria and structure may change significantly as we learn what works best for different types of MCP server assessments.

---

## 0 Identification
- [ ] **Server Name:** ____________________________________________ (O)  
- [ ] **Website / Docs URL:** _____________________________________ (O)  
- [ ] **Source Repository URL:** __________________________________ (O)  
- [ ] **Clone Path (local):** _____________________________________ (O)  
- [ ] **Latest Release Tag / Date:** ______________________________ (O)  
- [ ] **Primary Language / Runtime:** _____________________________ (O)  
- [ ] **Source Type:** Vendor‑provided ☐  Community ☐  Third‑party ☐ (O)

---

## 1 Repository Analysis Artifacts
| Artifact | Generated Y/N | File Path |
|----------|---------------|-----------|
| Full `git clone` archive | ☐ | `./repos/<server>/` |
| `git_log_last_12_months.txt` | ☐ |  |
| `commit_stats.json` | ☐ |  |
| Dependency SBOM (`sbom.spdx.json`) | ☐ |  |
| `initial_connect.json` | ☐ |  |
| Capability manifest / progressive‑disclosure | ☐ |  |

---

## 2 Project Activity & Maintenance
- [ ] **Commit Activity:** `git log --since="12 months ago"` → commits = _____ (O)  
- [ ] Contributors in last 12 mo = _____ (O)  
- [ ] Months with zero commits = _____ (O)  
- [ ] Maintainers ≥3 with merge rights ☐ (O)  
- [ ] Issue / PR response <30 days ☐ (O)  
- [ ] Roadmap or release plan published ☐ (O)  
- [ ] Meets required support SLA (________) ☐ (C SLA?)

---

## 3 Capabilities & Permissions
### 3.1 Supported Core Actions
| Action | Supported Y/N | Notes |
|--------|--------------|-------|
| Read | ☐ | |
| Write | ☐ | |
| Delete | ☐ | |
| Admin / Config | ☐ | |
| Other: __________ | ☐ | |

### 3.2 Fine‑Grained API Scopes
| Scope / Role | Description | Available Y/N |
|--------------|-------------|---------------|
| `read_only` |  | ☐ |
| `read_write` |  | ☐ |
| `delete_only` |  | ☐ |
| Custom: ______ |  | ☐ |

- [ ] Progressive disclosure on connect ☐ (O)  
- [ ] `initial_connect.json` captured ☐ (O)  
- [ ] Self‑updater present (can disable ☐) (O)  
- [ ] Remote prompt/config download ☐ (O)  
- [ ] Requires outbound internet ☐ (C Policy?)

---

## 4 External Services & Key Management
| Service | Min‑Scope Keys | Key Rotation | Fine Tokens | Policy OK (C) |
|---------|---------------|--------------|-------------|---------------|
| | ☐ | ☐ | ☐ | ☐ |

**Credential Storage Assessment**:
- [ ] Uses environment variables for secrets ☐ (Good Practice) (O)
- [ ] No hardcoded credentials in source ☐ (Critical) (O)  
- [ ] No secrets committed to version control ☐ (Critical) (O)
- [ ] Environment variables documented ☐ (O)
- [ ] Credential rotation process defined ☐ (O)

**Note**: Environment variables are the recommended approach for providing runtime secrets. The security concern is *how* those environment variables are populated and managed, not their use itself.

---

## 5 Security Posture
- [ ] TLS 1.3 / mTLS by default ☐ (O)  
- [ ] AuthN: OAuth2 ☐  OIDC ☐  mTLS ☐  API Key ☐  (O)  
- [ ] Signed releases / provenance ☐ (O)  
- [ ] Public vuln‑disclosure process ☐ (O)  
- [ ] SBOM critical CVEs unpatched? Y / N (O)  
- [ ] Crypto & data‑residency rules met ☐ (C)

---

## 6 Performance & Scalability
- [ ] Benchmarks published ☐ (O)  
- [ ] Required TPS = _____ / latency = _____ met ☐ (C)  
- [ ] Horizontally scalable ☐ (O)  
- [ ] Resource footprint within budget ☐ (C)

---

## 7 Standards Compliance
- [ ] MCP spec version v________ ☐ (O)  
- [ ] Passes interoperability tests ☐ (O)  
- [ ] SDK/examples for required languages ☐ (C)

---

## 8 License & Legal
- [ ] OSI license: ____________________ (O)  
- [ ] License fits deployment model ☐ (C)  
- [ ] Export / sanctions constraints ☐ (C)

---

## 9 Community & Ecosystem
- [ ] Active chat / forum ☐ (O)  
- [ ] External tutorials/blogs ☐ (O)  
- [ ] Public adopters ≥____ (O)  
- [ ] Language fits team skillset ☐ (C)

---

## 10 Documentation & UX
- [ ] Quick‑start works ☐ (O)  
- [ ] API reference complete ☐ (O)  
- [ ] Error messages actionable ☐ (O)  
- [ ] Localization needed/provided ☐ (C)

---

## 11 Deployment & Operations
- [ ] Container / package images ☐ (O)  
- [ ] Helm / Terraform modules ☐ (O)  
- [ ] Works on target platform (________) ☐ (C)  
- [ ] Metrics / logs / traces exported ☐ (O)  
- [ ] Backup / restore guide ☐ (O)

---

## 12 Cost & Support
- [ ] Free / OSS ☐ (O)  
- [ ] Paid support available ☐ (O)  
- [ ] TCO within budget cap ☐ (C)  
- [ ] Support SLA acceptable ☐ (C)

---

## 13 Extensibility & Customization
- [ ] Plugin / webhook framework ☐ (O)  
- [ ] Stable extension points ☐ (O)  
- [ ] Fork‑friendly code/license ☐ (O)  
- [ ] Customization within team capacity ☐ (C)

---

## 14 Observability & IR
- [ ] Prometheus metrics ☐ (O)  
- [ ] Structured JSON logs ☐ (O)  
- [ ] Alert thresholds documented ☐ (O)  
- [ ] IR runbook provided ☐ (O)  
- [ ] Fits monitoring toolchain ☐ (C)

---

## 15 Bundled Assets
| Asset | Version | Purpose | Conn. Msg / Config | Self‑update Y/N |
|-------|---------|---------|--------------------|-----------------|
| | | | | |

---

## 16 Green Flags
- [ ] Independent security audit ☐ (O)  
- [ ] Wide adoption (>____ stars/forks) ☐ (O)  
- [ ] Transparent governance ☐ (O)  
- [ ] Civil, active community ☐ (O)

## 17 Red Flags
- [ ] Unpatched critical CVEs >90 days ☐ (O)  
- [ ] Project inactivity >12 mo ☐ (O)  
- [ ] No / ambiguous license ☐ (O)  
- [ ] Anonymous maintainer ☐ (O)  
- [ ] Unsigned build dependencies ☐ (O)  
- [ ] Single‑commit dump ☐ (O)

---

## 18 Overall Fit Summary
**Verdict:** ____________________________________________  
**Strengths:** __________________________________________  
**Risks:** ______________________________________________  
**Next Steps / Mitigations:** ____________________________

---

