# 🔍 Dustin Braun  
## Data Validation Lead | Video Analytics & Platform Integrity
### Quality Engineering • Hardware-in-the-Loop Observability • AI Readiness

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat&logo=opensearch&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

### Data-driven quality engineering: validating what users see against what telemetry claims, powered by explainable heuristics and evidence-backed findings.

</div>

---

## 🔥 Welcome

I engineer **data validation systems**, not just test scripts.

My work spans:
- **Data Quality:** Correlating ground truth (video) with telemetry claims  
- **Observability:** Hardware-in-the-loop testing & alignment  
- **Automation:** Modern testing frameworks with high signal, low noise  
- **Integrity:** Explainable heuristics over opaque magic  
- **Evidence:** Screenshot-backed findings with timestamps & confidence  

Every repository in this portfolio reflects **real engineering standards**, not classroom demos.

---

## 📦 Portfolio Architecture (Overview)

```mermaid
flowchart TB
    A["Dustin Braun Portfolio<br/>(Data Validation & Quality)"]
    A --> B["Data Validation<br/>Screen-to-Events • Telemetry Integrity • Alignment"]
    A --> C["UI Testing<br/>WebdriverIO • Playwright • Cypress"]
    A --> D["API Testing<br/>Postman • Newman • Schema Validation"]
    A --> E["Performance & Security<br/>k6 • OWASP ZAP • CI Integration"]

    click B "https://github.com/jptrp/signal-noise-screen2events" "Data Validation"
    click C "https://github.com/jptrp/saucedemo-wdio-automation" "UI Automation (WDIO)"
    click D "https://github.com/jptrp/saucedemo-api-testing-postman" "API Testing (Postman)"
    click E "https://github.com/jptrp/k6-zap-perfsec-automation" "Performance (k6) + Security"
```

---

# 🧩 Portfolio Projects

## 📊 Project Matrix

| # | Project | Tech Stack | Key Capabilities | Links |
|---|---------|------------|------------------|-------|
| ⭐ | **Signal & Noise (Screen-to-Events)**<br/>*Hardware-in-the-loop observability* | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?logoColor=white) ![AWS_S3](https://img.shields.io/badge/AWS_S3-FF9900?logo=amazonaws&logoColor=white) ![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?logoColor=white) | • Video-derived state timeline<br/>• Telemetry correlation engine<br/>• Multi-device support (Roku/Apple TV)<br/>• Time alignment & drift estimation<br/>• Evidence-backed findings<br/>• S3/Athena/OpenSearch adapters | [Repo](https://github.com/jptrp/signal-noise-screen2events) |
| ⭐ | **ERP Test Automation**<br/>*Enterprise system showcase* | ![Cypress](https://img.shields.io/badge/Cypress-17202C?logo=cypress&logoColor=white) ![Node](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white) | • MVP ERP (4 modules)<br/>• 190 TestRail test cases<br/>• Feature flags (A/B testing)<br/>• Dual CI/CD (AWS + Azure)<br/>• 90% automation | [Repo](https://github.com/jptrp/cypress-erp-test-automation) |
| ⭐ | **Video Data Quality Lab**<br/>*ML/AI testing framework* | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white) ![ML](https://img.shields.io/badge/ML-FF6F00?logoColor=white) | • Computer vision testing<br/>• ML model validation<br/>• Video quality metrics<br/>• Automated analysis<br/>• Research-grade | [Repo](https://github.com/jptrp/video-data-quality-lab) |
| 4 | **WebdriverIO UI Automation**<br/>*Production framework* | ![WDIO](https://img.shields.io/badge/WDIO-EA5906?logo=webdriverio&logoColor=white) ![TS](https://img.shields.io/badge/TS-3178C6?logo=typescript&logoColor=white) ![Allure](https://img.shields.io/badge/Allure-FF45A0?logoColor=white) | • POM Architecture<br/>• 3 Test Suites (Smoke/Regression/E2E)<br/>• CI/CD + Allure Reports<br/>• ESLint/Prettier/Husky | [Repo](https://github.com/jptrp/saucedemo-wdio-automation) • [CI](https://github.com/jptrp/saucedemo-wdio-automation/actions) • [Reports](https://jptrp.github.io/saucedemo-wdio-automation/) |
| 5 | **API Testing**<br/>*Contract validation* | ![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white) ![Newman](https://img.shields.io/badge/Newman-FF6C37?logoColor=white) | • 11-endpoint suite<br/>• JSON schema validation<br/>• Negative testing<br/>• CI-ready | [Repo](https://github.com/jptrp/saucedemo-api-testing-postman) |
| 6 | **Playwright UI**<br/>*Modern automation* | ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white) ![TS](https://img.shields.io/badge/TS-3178C6?logo=typescript&logoColor=white) | • Cross-browser testing<br/>• Trace viewer<br/>• Deterministic selectors<br/>• Fast execution | [Repo](https://github.com/jptrp/saucedemo-playwright) |
| 7 | **Cypress UI**<br/>*Developer experience* | ![Cypress](https://img.shields.io/badge/Cypress-17202C?logo=cypress&logoColor=white) ![TS](https://img.shields.io/badge/TS-3178C6?logo=typescript&logoColor=white) | • Fast dev cycles<br/>• Custom commands<br/>• Strong debugging<br/>• Time-travel debugging | [Repo](https://github.com/jptrp/cypress-ui-saucedemo-automation) |
| 8 | **Performance + Security**<br/>*Non-functional testing* | ![k6](https://img.shields.io/badge/k6-7D64FF?logo=k6&logoColor=white) ![ZAP](https://img.shields.io/badge/OWASP_ZAP-0033A0?logoColor=white) | • Load testing with thresholds<br/>• ZAP baseline scanning<br/>• Combined perf + security<br/>• CI integration | [Repo](https://github.com/jptrp/k6-zap-perfsec-automation) |

### 🎯 What This Demonstrates

- **Data Validation & Observability** → Correlating ground truth (video) with telemetry claims, aligning timelines, detecting anomalies
- **Computer Vision & Video Analysis** → State detection, motion analysis, OCR-based signals, explainable heuristics
- **Telemetry Integrity** → Normalized adapters for S3, Athena, OpenSearch; session/device identity resolution
- **UI Automation Mastery** → 3 modern frameworks (WDIO, Playwright, Cypress) with POM architecture
- **API Testing Expertise** → Schema validation, contract testing, normalization pipelines
- **Non-Functional Testing** → Performance + Security (k6, OWASP ZAP) integrated with CI/CD
- **Production Standards** → Type-safe design (Pydantic, TypeScript), comprehensive docs, explainable heuristics

---

# 🧠 Engineering Philosophy

> **Data Validation & Automation are engineering disciplines.**

I operate by these principles:

- **Screen is Truth** → Video is ground truth, telemetry is claims to validate  
- **Explainability > Opaque Magic** → Deterministic heuristics over ML black boxes  
- **Evidence-Backed Findings** → Mismatches backed by screenshots, timestamps, confidence scores  
- **Stability > Speed**  
- **Clarity > Cleverness**  
- **Architecture > Accumulation**  
- **Real Coverage > Illusion of Tests**  

These tools aren't written to simulate production or automate clicks —  
they're written to **validate claims, detect anomalies, and improve decisions at scale**.

---

# 🛠️ Technical Skills

**Languages:** Python, TypeScript, JavaScript  
**Data Validation:** Pydantic, Video Processing, Computer Vision, State Machines, Correlation Engines  
**Telemetry Adapters:** S3, AWS Athena, OpenSearch, JSONL normalization  
**UI Automation:** WDIO, Playwright, Cypress, Selenium  
**API Testing:** Postman, Newman, Playwright API, schema validation  
**Performance & Security:** k6, OWASP ZAP  
**CI/CD:** GitHub Actions, Docker  
**Architecture:** POM, Adapters, Fixtures, Utilities, Data Strategies, Evidence Export  

---

# 📫 Contact

<div align="center">

**Dustin Braun**  
Data Validation Lead | Video Analytics & Platform Integrity  
📍 Castle Rock, CO  
🔍 Focus: Telemetry Integrity, Hardware-in-the-Loop Observability, AI Readiness  
📧 jptrp@icloud.com  
🔗 https://www.linkedin.com/in/dustinbrauntesting/  
🐙 https://github.com/jptrp  

</div>

---

<div align="center">

### *This portfolio represents how I think about quality, data integrity, reliability, and engineering — from validation systems to test automation.*

⭐ Star this repo if you'd like  
🔄 Updated: January 2026  

</div>
