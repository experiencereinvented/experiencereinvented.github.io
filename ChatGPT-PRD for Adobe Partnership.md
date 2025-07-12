# PRD for Adobe Partnership

**User:** Jack Jin (jackzhaojin@gmail.com)  
**Created:** 6/29/2025 22:45  
**Updated:** 6/29/2025 22:53  
**Exported:** 7/12/2025 16:26  
**Link:** [https://chatgpt.com/g/g-p-68586ad1bfc081919759f2ab36292603-ai-pivot/c/6861fa3f-67ec-8013-ae10-d824d1734f9b](https://chatgpt.com/g/g-p-68586ad1bfc081919759f2ab36292603-ai-pivot/c/6861fa3f-67ec-8013-ae10-d824d1734f9b)  

## Prompt:
I need a website, i'm currently still employed by my current company and this website's sole purpose right now is to convey that it's for adobe partnership research and is not actively competing with anyone right now.

Please build a PRD for me so I can feed into another agent. 

High level requirement
1. One landing page is sufficient
2. Mention AI exploration
3. Mention AEM (I need to be able to downlaod partnership SDK)
4. Mention AI Agents and Adobe agents (site optmizer espeically) and we want to look into it.
5. need tto mention that we're not actively looking for customer at the moment, however if you have any questions please email jack.jin@experiencereinvented.com
6. Want to build open source with adobe's product

## Response:
Here’s a **Product Requirements Document (PRD)** tailored for your needs — a simple, professional landing page that makes your intentions clear: this is a **non-commercial research initiative exploring Adobe partnerships, AI, and open source**. You can feed this into an agent or a web dev assistant for implementation.

* * *

📝 Product Requirements Document (PRD)
--------------------------------------

### 📌 Project Title:

**Experience Reinvented – Adobe Partnership Research Portal**

* * *

### 🎯 Purpose / Goal

To create a **single-page informational website** that communicates the purpose of a new Adobe-focused research initiative. This site will clarify that the project is **not a commercial venture**, but rather an **AI + Adobe open source exploration**, specifically looking into **AEM**, **AI Agents**, and **Adobe Site Optimizer**. The site also serves as a reference point for accessing Adobe’s **Partner SDKs** and tools for development purposes.

* * *

### 🔍 Target Audience

*   Adobe Partner and Developer Relations teams
*   Adobe product engineering (Site Optimizer, AEM, Firefly/GenAI teams)
*   Open source contributors or collaborators in the Adobe ecosystem
*   Legal/compliance teams performing due diligence

* * *

### 📄 Key Requirements

#### 1\. **Landing Page Structure (Single Page)**

A clean, professional landing page with these sections:

| Section | Purpose |
| --- | --- |
| **Hero** | Communicate project name and positioning as a research-driven AI + Adobe exploration. |
| **About This Project** | Explain that this is a non-commercial, exploratory initiative. Clarify that the site is for partnership research purposes only. |
| **Exploration Areas** | Brief bullets or visual callouts:  
• Adobe Experience Manager (AEM)  
• Adobe Site Optimizer  
• AI Agents and autonomous workflows  
• Generative AI integrations |
| **Open Source Mission** | State intent to build transparent, open-source projects that integrate with Adobe's products where licensing allows. |
| **Adobe Partner SDK Access** | Mention that access to Adobe SDKs is being requested or utilized under the research partnership track. |
| **Contact** | Simple message: “We are not actively seeking clients. For any inquiries, please contact jack.jin@experiencereinvented.com” |

* * *

### 🧠 Functional Requirements

| ID | Feature | Description |
| --- | --- | --- |
| F1 | Responsive Layout | Desktop and mobile responsive, minimal JS |
| F2 | Email Contact | A contact section or mailto link (no contact form needed) |
| F3 | Clean Branding | Light branding to match “Experience Reinvented” (can be styled later) |
| F4 | SEO Tags | Basic metadata for SEO and credibility |
| F5 | Open Source Attribution | Mention or link to GitHub repo if/when available |
| F6 | AI + Adobe Language | Language around Adobe + AI agentic workflows, SDK exploration, and generative experiences |

* * *

### 🚫 Out of Scope (For Now)

*   No customer lead forms or service offerings
*   No blog, CMS, or marketing automation
*   No analytics or tracking unless required for SDK use validation

* * *

### 🛠️ Tech Stack Recommendations

(Minimalistic, fast, and open source)

*   **Static Site Generator**: Next.js or Astro (can be hosted via Vercel or GitHub Pages)
*   **Styling**: TailwindCSS or plain CSS for speed and simplicity
*   **Hosting**: GitHub Pages, Vercel (free tier is fine)
*   **Domain**: `www.experiencereinvented.com` or a subdomain like `research.experiencereinvented.com`

* * *

### 📌 Call to Action

Place near footer:

> “This project is not currently offering commercial services. For questions about research goals or partnership discussions, please contact:  
> 📧 **jack.jin@experiencereinvented.com**”

* * *

Would you like me to generate:

*   A basic wireframe or HTML/CSS starter template?
*   AI-generated text copy for each section?
*   A matching GitHub `README.md`?

Let me know what you want next.

## Prompt:
The PRD I'll need AI to program. Please put this in canvas and put it in markdown.

Also pelase add in a section that I like this gradiant, it doesn't have to go all over the page. The page should be clean, however if there are specific background for a a section we should use it. Please put it in the PRD (the gradient).

Sample code:

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

## Response:
**Adobe Research Site Prd**

# 📘️ Product Requirements Document (PRD)

## 🏷️ Project Title
**Experience Reinvented – Adobe Partnership Research Portal**

---

## 🌟 Purpose / Goal
To create a **single-page informational website** that communicates the purpose of a new Adobe-focused research initiative. This site will clarify that the project is **not a commercial venture**, but rather an **AI + Adobe open source exploration**, specifically looking into **AEM**, **AI Agents**, and **Adobe Site Optimizer**. The site also serves as a reference point for accessing Adobe’s **Partner SDKs** and tools for development purposes.

This site **does not intend to compete with any existing Adobe partners**, and is not pursuing clients or commercial engagements. The only objective is **research and partnership licensing** for Adobe SDKs, especially AEMaaCS.

---

## 👥 Target Audience
- Adobe Partner and Developer Relations teams  
- Adobe product engineering (Site Optimizer, AEM, Firefly/GenAI teams)  
- Open source contributors or collaborators in the Adobe ecosystem  
- Legal/compliance teams performing due diligence

---

## 📄 Key Requirements

### 1. Landing Page Structure (Single Page)
A clean, modern landing page (startup/innovation tone) with these sections:

| Section | Purpose |
|--------|--------|
| **Hero** | Communicate project name and positioning as a research-driven AI + Adobe exploration. |
| **About This Project** | Explain that this is a non-commercial, exploratory initiative. Clarify that the site is for partnership research purposes only. Emphasize that there are no services or customer acquisition plans. |
| **Exploration Areas** | Brief bullets or visual callouts:  
• Adobe Experience Manager (AEM)  
• Adobe Site Optimizer  
• AI Agents and autonomous workflows  
• Generative AI integrations |
| **Open Source Mission** | State intent to build transparent, open-source projects that integrate with Adobe's products where licensing allows. |
| **Adobe Partner SDK Access** | Mention that access to Adobe SDKs (especially AEMaaCS) is being requested or utilized under the research partnership track. |
| **Contact** | Simple message: “We are not actively seeking clients. For any inquiries, please contact jack.jin@experiencereinvented.com” |

---

## 🧠 Functional Requirements

| ID | Feature | Description |
|----|---------|-------------|
| F1 | Responsive Layout | Desktop and mobile responsive, minimal JS |
| F2 | Email Contact | A contact section or mailto link (no contact form needed) |
| F3 | Clean Branding | Modern, startup-style design with no logo, personal photo, or heavy branding. Use a web-safe sans-serif font or Adobe.com-like aesthetic. |
| F4 | SEO Tags | Basic metadata for SEO and credibility |
| F5 | Open Source Attribution | Mention or link to GitHub repo if/when available |
| F6 | AI + Adobe Language | Language around Adobe + AI agentic workflows, SDK exploration, and generative experiences (kept high level) |
| F7 | Section Background Gradient | Specific sections may use the following gradient for visual emphasis (do not overuse):  

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
- No customer lead forms or service offerings  
- No blog, CMS, or marketing automation  
- No analytics or tracking unless required for SDK use validation  
- No "coming soon" sections or future roadmap

---

## 🛠️ Tech Stack Recommendations
(Minimalistic, fast, and open source)

- **Static Site Generator**: Next.js or Astro (can be hosted via Vercel or GitHub Pages)
- **Styling**: TailwindCSS or plain CSS for speed and simplicity
- **Hosting**: GitHub Pages, Vercel (free tier is fine)
- **Domain**: Root domain `www.experiencereinvented.com` (not subdomain)

---

## 📌 Call to Action
Place near footer:

> “This project is not currently offering commercial services. For questions about research goals or partnership discussions, please contact:  
📧 **jack.jin@experiencereinvented.com**”

---

## ⚠️ Legal / Branding Notes
- This site is **not affiliated with or endorsed by Adobe Inc.**
- All references to Adobe products are for research and exploration purposes only
- This project **does not seek to compete with any existing Adobe Solution Partners**

Done. The PRD is now in Canvas as **“Adobe Research Site Prd”** and ready for use by another agent or developer. Let me know if you want:

*   Sample text copy for the landing page
*   A wireframe mockup (HTML or image)
*   A Next.js or Astro starter project
*   GitHub `README.md` or license boilerplate

Happy to continue iterating!

## Prompt:
Looks good, any questions you have for me that could make this PRD better?

## Response:
Great — the PRD is strong for a v1. That said, here are a few thoughtful questions that, if answered, could improve clarity, make handoff easier for developers/agents, and future-proof the project a bit:

* * *

### 🧩 Clarification & Expansion Questions

#### 1\. **Tone and Visual Style**

*   Do you want the tone to be more corporate (Accenture-style) or more innovative/startup (e.g., Notion-style, clean and modern)?
*   Should we include your personal photo or branding anywhere (e.g., a founder blurb or logo)?

#### 2\. **Logo, Icons, and Fonts**

*   Do you already have a logo or a specific font family (e.g., Adobe Clean, Inter, etc.) you’d like to use?
*   Should the site use Adobe’s visual branding elements (e.g., subtle nods to their red, gradients, iconography)?

#### 3\. **Future-Proofing**

*   Would you like a hidden or commented-out “Coming Soon” section for potential future blog posts, portfolio, or contact form?
*   Do you want any kind of GitHub badge or CTA to contribute to the open source repo (even if the repo is private for now)?

#### 4\. **Domain Setup**

*   Will this live on `experiencereinvented.com` root or a subdomain (e.g., `research.experiencereinvented.com`)? Knowing this helps set up canonical URLs and SEO tags correctly.

#### 5\. **Adobe Relations**

*   Do you want to name-drop any specific Adobe programs (e.g., “Partner Exchange,” “Adobe Developer Console,” “Adobe I/O”) to build credibility?
*   Should we explicitly state that the site is requesting access to partner SDKs, or keep that more implicit?

#### 6\. **Licensing / Legal**

*   Should we display a disclaimer that this site is not affiliated with Adobe Inc., for legal clarity?
*   Do you want a footer note about how you’re respecting all licensing terms of Adobe’s SDKs and APIs?

#### 7\. **AI Stack / Tech Interests**

*   Do you want to call out specific AI technologies you’re exploring (e.g., GPT-4o, Claude, Vertex AI, etc.) or keep that general?
*   Should we mention your AI design agent or MCP setup as part of what you’re testing?

* * *

Let me know which of these you'd like to include and I can update the Canvas PRD accordingly.

## Prompt:
1. Innovation / Start up, clean and modern, no logo or branding or personal
2. Nope, maybe whatefver font adobe.com uses. We should add in some adobe (as with the grandiant it has the adobe red, however we shouldn't use it directly)
3. No coming soon yet, just need to not get in trouble with work and have a partnership site for a license, stress on no plan to acquire customers or do any work yet. Nope, not yet
4. root domain and www, not research, mainly www
5. Nope not yet, keep anon, yes to requesting AEMaaCS SDK to do research
6. Yes mention adobe, and also mention it does not seek to compete against any existing Adobe Partners at this time
7. Keep it high level

## Response:
**Adobe Research Site Prd**

# 📘️ Product Requirements Document (PRD)

## 🏷️ Project Title
**Experience Reinvented – Adobe Partnership Research Portal**

---

## 🌟 Purpose / Goal
To create a **single-page informational website** that communicates the purpose of a new Adobe-focused research initiative. This site will clarify that the project is **not a commercial venture**, but rather an **AI + Adobe open source exploration**, specifically looking into **AEM**, **AI Agents**, and **Adobe Site Optimizer**. The site also serves as a reference point for accessing Adobe’s **Partner SDKs** and tools for development purposes.

This site **does not intend to compete with any existing Adobe partners**, and is not pursuing clients or commercial engagements. The only objective is **research and partnership licensing** for Adobe SDKs, especially AEMaaCS.

---

## 👥 Target Audience
- Adobe Partner and Developer Relations teams  
- Adobe product engineering (Site Optimizer, AEM, Firefly/GenAI teams)  
- Open source contributors or collaborators in the Adobe ecosystem  
- Legal/compliance teams performing due diligence

---

## 📄 Key Requirements

### 1. Landing Page Structure (Single Page)
A clean, modern landing page (startup/innovation tone) with these sections:

| Section | Purpose |
|--------|--------|
| **Hero** | Communicate project name and positioning as a research-driven AI + Adobe exploration. |
| **About This Project** | Explain that this is a non-commercial, exploratory initiative. Clarify that the site is for partnership research purposes only. Emphasize that there are no services or customer acquisition plans. |
| **Exploration Areas** | Brief bullets or visual callouts:  
• Adobe Experience Manager (AEM)  
• Adobe Site Optimizer  
• AI Agents and autonomous workflows  
• Generative AI integrations |
| **Open Source Mission** | State intent to build transparent, open-source projects that integrate with Adobe's products where licensing allows. |
| **Adobe Partner SDK Access** | Mention that access to Adobe SDKs (especially AEMaaCS) is being requested or utilized under the research partnership track. |
| **Contact** | Simple message: “We are not actively seeking clients. For any inquiries, please contact jack.jin@experiencereinvented.com” |

---

## 🧠 Functional Requirements

| ID | Feature | Description |
|----|---------|-------------|
| F1 | Responsive Layout | Desktop and mobile responsive, minimal JS |
| F2 | Email Contact | A contact section or mailto link (no contact form needed) |
| F3 | Clean Branding | Modern, startup-style design with no logo, personal photo, or heavy branding. Use a web-safe sans-serif font or Adobe.com-like aesthetic. |
| F4 | SEO Tags | Basic metadata for SEO and credibility |
| F5 | Open Source Attribution | Mention or link to GitHub repo if/when available |
| F6 | AI + Adobe Language | Language around Adobe + AI agentic workflows, SDK exploration, and generative experiences (kept high level) |
| F7 | Section Background Gradient | Specific sections may use the following gradient for visual emphasis (do not overuse):  

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
- No customer lead forms or service offerings  
- No blog, CMS, or marketing automation  
- No analytics or tracking unless required for SDK use validation  
- No "coming soon" sections or future roadmap

---

## 🛠️ Tech Stack Recommendations
(Minimalistic, fast, and open source)

- **Static Site Generator**: Next.js or Astro (can be hosted via Vercel or GitHub Pages)
- **Styling**: TailwindCSS or plain CSS for speed and simplicity
- **Hosting**: GitHub Pages, Vercel (free tier is fine)
- **Domain**: Root domain `www.experiencereinvented.com` (not subdomain)

---

## 📌 Call to Action
Place near footer:

> “This project is not currently offering commercial services. For questions about research goals or partnership discussions, please contact:  
📧 **jack.jin@experiencereinvented.com**”

---

## ⚠️ Legal / Branding Notes
- This site is **not affiliated with or endorsed by Adobe Inc.**
- All references to Adobe products are for research and exploration purposes only
- This project **does not seek to compete with any existing Adobe Solution Partners**

Edited

Answer in chat instead

The PRD has been updated to reflect all your input — including tone, branding, legal clarifications, domain preference, and the specific note about AEMaaCS SDK access for research. You're all set for AI agent implementation or developer handoff.

Let me know if you’d like:

*   A wireframe mockup or layout sketch
*   A `README.md` for the GitHub repo
*   Sample HTML or Next.js scaffold

Ready when you are.



---
Powered by [ChatGPT Exporter](https://www.chatgptexporter.com)