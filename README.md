# openai-sentinelsdk-client-analysis-EN-

An independent, voluntary client-side security infrastructure audit focused on memory isolation analysis and telemetry mapping of OpenAI's SentinelSDK component within the ChatGPT web application.

---

## 📄 Technical Report

The comprehensive write-up detailing the core methodology, structural security findings, architectural mitigation proposals, and the official triage response from OpenAI has been compiled into a standalone document.

### 🔗 [Click here to read the Technical Report (PDF)](./report_sentinel_en.pdf)

---

## 📸 Visual Evidence

To inspect full-resolution technical verification screenshots, including browser console behavior, network telemetry logs (`/m` and `/ping` endpoints), and source tree component mappings, check the attachment below:

### 🖼️ [View all Technical Audit Evidence (PDF)](./printforevidence.pdf)

---

## 🛠️ Audit Scope
* **Vulnerability Target:** Global Scope State Leakage via the `window` object (`__sentinel_token_pending`).
* **Analyzed Components:** SentinelSDK infrastructure (`sdk.js` / `frame.html`).
* **Disclosure Status:** Responsible Disclosure completed. Findings acknowledged and routed by OpenAI Security to their core engineering teams.

---
*Note: For the Brazilian Portuguese documentation and analysis, please refer to the dedicated localized repository.*
