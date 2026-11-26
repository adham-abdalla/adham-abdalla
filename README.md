## Hi, I'm Adham 👋

**Software developer: systems programming, test automation, data and business applications.**

I build software that is tested, measured and documented: low-level C emulators and kernels, Python services and automation, React front ends, and Dynamics 365-style business solutions. Every project here has CI, automated tests and a write-up of the design decisions.

### 🔧 What I work on

- **Systems and performance:** C/C++, RISC-V, SIMD (AVX2), int8 quantization, memory-safe data structures
- **Test and validation:** regression suites, requirement traceability, co-simulation, fuzzing, mutation testing, sanitizers
- **Infrastructure and DevOps:** Linux, Docker, Kubernetes, Ansible, GitHub Actions, Prometheus metrics
- **Data and analytics:** Python, SQL star schemas, Power BI (DAX), Excel models, data migration and quality rules
- **Web and AI apps:** React, Node/Express, Flask, retrieval-augmented generation with grounded, cited answers
- **Business applications:** Dynamics 365 / Power Platform CRM and ERP processes, fit-gap analysis, test plans

### ⭐ Featured projects

**Systems and embedded**

| Project | What it is |
|---|---|
| [rv32i-emulator](https://github.com/adham-abdalla/rv32i-emulator) | RISC-V RV32I emulator in C with an ELF loader, checked against an independent reference model by random co-simulation |
| [int8-matmul-kernels](https://github.com/adham-abdalla/int8-matmul-kernels) | Tiled and AVX2 register-blocked matrix-multiply kernels, packed int8 GEMM and a quantization accuracy study with PyTorch parity tests |
| [c-data-structures](https://github.com/adham-abdalla/c-data-structures) | Vector, ring buffer, heap, Robin Hood hash map and LRU cache in C11, with fuzzing, mutation testing and 100% coverage |
| [repeater-qa-automation](https://github.com/adham-abdalla/repeater-qa-automation) | Radio-repeater channel access logic in C with a Python regression suite and requirement traceability, on Linux and Windows CI |

**Platforms, data and AI**

| Project | What it is | Demo |
|---|---|---|
| [kitchen-telemetry-platform](https://github.com/adham-abdalla/kitchen-telemetry-platform) | Machine telemetry: C++ edge aggregation, Flask ingest API, PostgreSQL + MongoDB + S3, drift alerts, React dashboard | [Live](https://adham-abdalla.github.io/kitchen-telemetry-platform/) |
| [cluster-ops-toolkit](https://github.com/adham-abdalla/cluster-ops-toolkit) | Health checks and safe drain automation for accelerator servers: Python agent, Ansible, Docker, Kubernetes DaemonSet | |
| [benefits-assistant-rag](https://github.com/adham-abdalla/benefits-assistant-rag) | RAG assistant with cited JSON answers, a grounding gate and an evaluation suite with a held-out set | [Live](https://adham-abdalla.github.io/benefits-assistant-rag/) |
| [lifeplan-react](https://github.com/adham-abdalla/lifeplan-react) | React financial wellness planner: retirement projection, gap solver and budget check | [Live](https://adham-abdalla.github.io/lifeplan-react/) |
| [it-capacity-planner](https://github.com/adham-abdalla/it-capacity-planner) | IT capacity planning: SQL star schema, data validation, Excel workbook with live formulas, Power BI DAX model | [Live](https://adham-abdalla.github.io/it-capacity-planner/) |

**Business applications**

| Project | What it is | Demo |
|---|---|---|
| [harbourline-crm](https://github.com/adham-abdalla/harbourline-crm) | Dynamics 365-style CRM implementation: requirements, fit-gap, solution design and a full test plan | [Live](https://adham-abdalla.github.io/harbourline-crm/) |
| [northfield-erp](https://github.com/adham-abdalla/northfield-erp) | Business Central-style order-to-cash: orders, stock reservation, invoicing, payments and AR aging | [Live](https://adham-abdalla.github.io/northfield-erp/) |
| [crm-data-migration-toolkit](https://github.com/adham-abdalla/crm-data-migration-toolkit) | Legacy data migration to Dynamics 365: mapping, data quality rules, duplicate merge and reconciliation | [Live](https://adham-abdalla.github.io/crm-data-migration-toolkit/) |

### 🧰 Tech stack

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Dynamics 365](https://img.shields.io/badge/Dynamics_365-0B53CE?style=flat&logo=dynamics365&logoColor=white)

### ✅ How I ship

- Tests before claims: every repo runs its test suite in GitHub Actions on each push
- Design notes, test plans and defect logs live next to the code in `docs/`
- Live demos are deployed automatically to GitHub Pages
