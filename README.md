# openai-sentinelsdk-client-analysis-EN-

Independent client-side security audit of OpenAI's SentinelSDK in ChatGPT. This repository documents a global scope memory leakage anomaly (__sentinel_token_pending) and maps telemetry architecture (sdk.js/iframe), including architectural mitigation proposals and official response from the OpenAI security team.

---

## 📄 Relatório Técnico / Technical Report

O write-up detalhado com a metodologia, análises de segurança, propostas de mitigação e o retorno oficial da equipe de segurança da OpenAI foi compilado em formato PDF.

The detailed write-up covering methodology, security findings, mitigation proposals, and OpenAI's official triage feedback has been compiled into a PDF document.

### 🔗 [Clique aqui para ler em Português (PDF)](./relatorio_sentinel.pdf)
### 🔗 [Click here to read in English (PDF)](./report_sentinel_en.pdf)

---

### 🛠️ Escopo / Scope
* **Vulnerabilidade / Vulnerability:** Vazamento de Escopo Global (Global Scope Leakage) via objeto `window`.
* **Componente / Component:** SentinelSDK (`sdk.js` / `frame.html`).
* **Status:** Divulgação Responsável (*Responsible Disclosure*) enviada e encaminhada para a engenharia da OpenAI / Sent to OpenAI security engineering.
* 
