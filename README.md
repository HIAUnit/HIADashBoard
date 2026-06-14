# HIA Project Review Dashboard

![Application UI Version](https://img.shields.io/badge/version-1.1.0-teal)
![License](https://img.shields.io/badge/license-Internal%20Use%20Only-red)
![Platform](https://img.shields.io/badge/platform-Cross%20Browser-blue)

A secure, client-side single-page application (SPA) built for the **Department of Health (DOH) — Health Promotion Bureau**. This system serves as an operational tracking matrix to monitor, manage, and audit the lifecycle evaluation pipeline of development projects and strategic multi-sector programs undergoing Health Impact Assessments (HIA).

> 🔒 **Security Notice:** This repository is **Strictly Private** and intended exclusively for internal team collaboration. Distribution or unauthorized exposure of source files is prohibited.

---

## 🚀 Core Functionalities

*   **Pipeline Evaluation Lifecycle Matrix:** A Kanban-inspired tracking interface mapping applications across critical legal and procedural stages (*Screening*, *Scoping*, *HIA Report/PHMMP*, and *Monitoring & Evaluation*).
*   **Geospatial Tracking Engine:** Built-in OpenStreetMap (OSM) layout mapping via Leaflet.js, projecting real-time coordinate references (`lat`/`lng`) for physical project footprints across the regions.
*   **Granular Workflow Auditing:** Support for multi-tiered event logging including native submission timelines, committee forwarding tracking, and custom milestone timestamp generation.
*   **Internal Desk Agenda Calendar:** A reactive calendar subsystem that allows internal reviewers to pin desk reviews, issue deadlines, and manage localized operational milestones.
*   **Dynamic Program Segmentation:** Integrated data separation that automatically groups and isolates massive multi-sector "Development Programs" from localized project profiles.

---

## 🛠️ Architecture & Tech Stack

This platform relies on a zero-dependency, serverless, client-first architecture ensuring maximum portability and instantaneous local runtimes.

*   **Markup & Layout:** HTML5 with semantic nodes.
*   **Styling Engine:** Vanilla CSS3 utilizing localized Custom Properties (`:root` design tokens) for unified brand theme enforcement.
*   **Reactive Scripting:** Vanilla JavaScript (ES6+) utilizing an in-memory JSON state array to drive UI state synchronization without the build overhead of external SPA frameworks.
*   **Geospatial Layers:** Leaflet.js (v1.9.4 OpenStreetMap tile provider integration).

---

## ⚙️ Local Development & Quick Start

Because this project utilizes a serverless, zero-build compilation model, you do not need to install node packages or initialize local compilers.

### Prerequisites
* Any modern desktop browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Apple Safari).

### Launching the Dashboard
1. **Clone the repository securely:**
```bash
   git clone [https://github.com/YOUR_ORGANIZATION/hia-review-dashboard.git](https://github.com/YOUR_ORGANIZATION/hia-review-dashboard.git)
