# Interactive Enterprise Website Cost Calculator Widget (2026) 🧮

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-28a745?style=for-the-badge&logo=github)](https://mahmoudthabetmohamed-lgtm.github.io/website-cost-calculator/)
[![Official Calculator](https://img.shields.io/badge/Official_Engine-mtm4web.com-0052cc?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.mtm4web.com/website-cost-calculator)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

A lightweight, responsive, and framework-agnostic client-side **Website Cost Estimation Engine** built for corporate web developers, agencies, and enterprise clients across Saudi Arabia and Egypt. 

Engineered and maintained by the software architecture team at **[MTM4WEB Enterprise Solutions](https://www.mtm4web.com/)**.

---

## 🚀 Live Demo & Official Platform

- **GitHub Pages Demo:** [https://mahmoudthabetmohamed-lgtm.github.io/website-cost-calculator/](https://mahmoudthabetmohamed-lgtm.github.io/website-cost-calculator/)
- **Production Enterprise Implementation:** [https://www.mtm4web.com/website-cost-calculator](https://www.mtm4web.com/website-cost-calculator)

---

## 🌟 Key Features

1. **Multi-Currency Dynamic Conversion:** Real-time budget switching between **Saudi Riyal (SAR)**, **Egyptian Pound (EGP)**, and **US Dollar (USD)**.
2. **Tiered Scope Modeling:** Instant estimation for:
   - Corporate Portals & Brand Showcase.
   - **[Industrial Factory Platforms](https://www.mtm4web.com/industrial-websites)** with dynamic TDS specifications and B2B catalogs.
   - **[Contracting & Construction Websites](https://www.mtm4web.com/contracting-websites)** with automated RFP/RFQ and tender pipelines.
3. **Enterprise Compliance Add-ons:** Granular computation for **ZATCA Phase 2 E-Invoicing**, Saudi national payment gateways (Mada, Apple Pay, Tabby), and bi-directional bilingual architectures (RTL Arabic / LTR English).
4. **Performance Optimized:** Built with zero runtime dependencies. Sub-millisecond computation with full Core Web Vitals compliance.

---

## 🛠️ Usage & Integration

Embed the estimation widget into any HTML/Laravel/WordPress project:

```html
<iframe 
  src="https://mahmoudthabetmohamed-lgtm.github.io/website-cost-calculator/" 
  width="100%" 
  height="750px" 
  style="border:none; border-radius: 24px;" 
  title="MTM4WEB Cost Calculator">
</iframe>
```

Or utilize the calculation engine programmatically:

```javascript
import { QuotationEngine } from './calculator.js';

const engine = new QuotationEngine({
  baseRates: { SAR: 1.0, EGP: 12.8, USD: 0.266 }
});

const quote = engine.compute({
  tier: 'industrial', // or 'contracting', 'corporate', 'saas'
  addons: ['zatca_phase2', 'payment_gateways', 'seo_audit'],
  currency: 'SAR'
});

console.log(quote);
```

---

## 🏢 Related Enterprise Architectures by MTM4WEB

- 🏭 **[Industrial & Manufacturing Web Design](https://www.mtm4web.com/industrial-websites):** High-speed catalog architectures engineered for Saudi and Egyptian manufacturing facilities.
- 🏗️ **[General Contracting & Construction Portals](https://www.mtm4web.com/contracting-websites):** Tender management and portfolio delivery for contracting conglomerates.
- 🇸🇦 **[Corporate Web Design in Riyadh](https://www.mtm4web.com/web-design-riyadh):** Enterprise web engineering tailored to Vision 2030 and local compliance frameworks.
- 🔍 **[Free Instant SEO & Speed Audit](https://www.mtm4web.com/free-seo-audit):** Automated Core Web Vitals diagnostic tool for corporate websites.
- 📑 **[Download Official Company Profile (PDF)](https://www.mtm4web.com/mtm4web-profile.pdf):** Institutional capabilities statement and verified portfolio.

---

## 📄 License

This open source widget is released under the **MIT License**. Maintained with ❤️ by [MTM4WEB](https://www.mtm4web.com).
