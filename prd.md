# 📘️ Product Requirements Document (PRD)

## 🏷️ Project Title

**Experience Reinvented – Adobe Partnership Research Portal**

---

## 🌟 Purpose / Goal

To create a **single-page informational website** that communicates the purpose of a new Adobe-focused research initiative. This site will clarify that the project is **not a commercial venture**, but rather an **AI + Adobe open source exploration**, specifically looking into **AEM**, **AI Agents**, and **Adobe Site Optimizer**. The site also serves as a reference point for accessing Adobe’s **Partner SDKs** and tools for development purposes.

This site **does not intend to compete with any existing Adobe partners**, and is not pursuing clients or commercial engagements. The only objective is **research and partnership licensing** for Adobe SDKs, especially AEMaaCS.

---

## 👥 Target Audience

* Adobe Partner and Developer Relations teams
* Adobe product engineering (Site Optimizer, AEM, Firefly/GenAI teams)
* Open source contributors or collaborators in the Adobe ecosystem
* Legal/compliance teams performing due diligence

---

## 📄 Key Requirements

### 1. Landing Page Structure (Single Page)

A clean, modern landing page (startup/innovation tone) with these sections:

| Section                              | Purpose                                                                                                                                                                                             |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Hero**                             | Communicate project name and positioning as a research-driven AI + Adobe exploration.                                                                                                               |
| **About This Project**               | Explain that this is a non-commercial, exploratory initiative. Clarify that the site is for partnership research purposes only. Emphasize that there are no services or customer acquisition plans. |
| **Exploration Areas**                | Brief bullets or visual callouts:                                                                                                                                                                   |
| • Adobe Experience Manager (AEM)     |                                                                                                                                                                                                     |
| • Adobe Site Optimizer               |                                                                                                                                                                                                     |
| • AI Agents and autonomous workflows |                                                                                                                                                                                                     |
| • Generative AI integrations         |                                                                                                                                                                                                     |
| **Open Source Mission**              | State intent to build transparent, open-source projects that integrate with Adobe's products where licensing allows.                                                                                |
| **Adobe Partner SDK Access**         | Mention that access to Adobe SDKs (especially AEMaaCS) is being requested or utilized under the research partnership track.                                                                         |
| **Contact**                          | Simple message: “We are not actively seeking clients. For any inquiries, please contact [jack.jin@experiencereinvented.com](mailto:jack.jin@experiencereinvented.com)”                              |

---

## 🧠 Functional Requirements

| ID | Feature                     | Description                                                                                                                               |
| -- | --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| F1 | Responsive Layout           | Desktop and mobile responsive, minimal JS                                                                                                 |
| F2 | Email Contact               | A contact section or mailto link (no contact form needed)                                                                                 |
| F3 | Clean Branding              | Modern, startup-style design with no logo, personal photo, or heavy branding. Use a web-safe sans-serif font or Adobe.com-like aesthetic. |
| F4 | SEO Tags                    | Basic metadata for SEO and credibility                                                                                                    |
| F5 | Open Source Attribution     | Mention or link to GitHub repo if/when available                                                                                          |
| F6 | AI + Adobe Language         | Language around Adobe + AI agentic workflows, SDK exploration, and generative experiences (kept high level)                               |
| F7 | Section Background Gradient | Specific sections may use the following gradient for visual emphasis (do not overuse):                                                    |

```html
<div class="gradient-background">
  <!-- You can place your image or content here -->
</div>
<style>
.gradient-background {
  width: 100%;
  height: 100vh; /* Change to your desired size */
  background: linear-gradient(to right, #FFB199, #E1251B, #8000FF);
}
</style>
```

Use sparingly in hero or featured sections. The overall page should remain clean and minimal.

---

## ❌ Out of Scope (For Now)

* No customer lead forms or service offerings
* No blog, CMS, or marketing automation
* No analytics or tracking unless required for SDK use validation
* No "coming soon" sections or future roadmap

---

## 🛠️ Tech Stack Recommendations

(Minimalistic, fast, and open source)

* **Frontend**: Flat HTML file (single `index.html`)
* **Styling**: Plain CSS for speed and simplicity
* **JavaScript**: Minimal vanilla JS if needed (no frameworks)
* **Hosting**: GitHub Pages (experiencereinvented organization)
* **Repository**: https://github.com/experiencereinvented/experiencereinvented.github.io
* **Domain**: Root domain `www.experiencereinvented.com` (not subdomain)

---

## 📌 Call to Action

Place near footer:

> “This project is not currently offering commercial services. For questions about research goals or partnership discussions, please contact:
> 📧 **[jack.jin@experiencereinvented.com](mailto:jack.jin@experiencereinvented.com)**”

---

## ⚠️ Legal / Branding Notes

* This site is **not affiliated with or endorsed by Adobe Inc.**
* All references to Adobe products are for research and exploration purposes only
* This project **does not seek to compete with any existing Adobe Solution Partners**
