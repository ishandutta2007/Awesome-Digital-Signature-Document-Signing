# Awesome-Digital-Signature-Document-Signing

## Top Digital Signature & Document Signing Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on E-Signature Workflows, PDF Cryptographic Sealing & Tamper-Evident Audit Trails*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Signature & Document Signing**. These tools help organizations send documents for legally binding electronic signatures—covering envelope creation, field placement, signer authentication, audit trails, and the cryptographic sealing of completed PDFs.

**Examples** include DocuSign, Adobe Acrobat Sign, Dropbox Sign, PandaDoc, Zoho Sign, SignNow, OneSpan Sign, DocuSeal, and Digitorus pdfsign (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted e-signature workflows, open-source PDF signing engines, and community-driven document packaging—ideal for developers embedding signing into their own products and organizations seeking data sovereignty over per-envelope SaaS pricing. The open-source landscape spans two distinct layers: **complete signing platforms** (DocuSeal, SignFuz) for turnkey envelope workflows, and **cryptographic signing libraries** (pdfsign, pyHanko) for embedding PAdES/CMS signatures into custom applications.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global digital signature market is valued at approximately **$12–$14 billion in 2025–2026** and is expanding at a ~25–35% CAGR driven by global eIDAS 2.0 regulations, remote workforce demands, and zero-trust security postures. The sector exhibits a **moderately fragmented** structure: while enterprise behemoths like Adobe and DocuSign dominate mainstream commercial contracts, the broader space remains diversified with specialized PKI trust service providers, regional sovereign compliance vendors, and developer-first API signing solutions.

## SaaS/Hosted Platforms

| Product | Description | Starting Pricing | Free Tier / Free Trial Limits | Company Size / Valuation |
|---|---|---|---|---|
| **[Adobe Acrobat Sign](https://www.adobe.com/sign.html)** | Enterprise e-signature bundled into Adobe Document Cloud and Acrobat suites with deep Microsoft 365, Salesforce, and Workday integrations. | **$16.99/user/month** (Acrobat Standard for teams, annual) | **7-day free trial** (Standard/Pro teams) + **Free permanent Developer Edition & sandbox** with full REST API access | ~$94.5 Billion market cap / ~$26.0 Billion annual revenue |
| **[DocuSign](https://www.docusign.com/)** | Global market share leader in electronic signature and Intelligent Agreement Management (IAM) with extensive compliance certifications. | **$10.00/month** (Personal plan, annual; 5 envelopes/mo) | **30-day free trial** (unlimited envelopes during trial, up to 3 users) + **Free permanent developer sandbox** | ~$15.0 Billion market cap / ~$3.36 Billion annual revenue |
| **[Zoho Sign](https://www.zoho.com/sign/)** | Cloud-based e-signature service tightly integrated with Zoho CRM, Desk, People, and third-party cloud productivity tools. | **$10.00/user/month** (Standard plan, annual; 25 envelopes/user/mo) | **Free-forever plan**: 1 user, 5 envelopes/month; **14-day free trial** for Professional/Enterprise tiers (no credit card required) | ~$12.5 Billion private valuation / ~$1.5 Billion annual revenue |
| **[Dropbox Sign](https://sign.dropbox.com/)** | Developer-friendly e-signature platform (formerly HelloSign) featuring clean embedded signing UI and turnkey cloud storage integration. | **$15.00/month** (Essentials plan, annual; 1 user, unlimited signatures) | **30-day free trial** (unlimited signature requests) + **Free developer test mode** (unlimited sandbox signature requests via API) | ~$7.5 Billion market cap / ~$2.52 Billion annual revenue |
| **[SignNow](https://www.signnow.com/)** | Cloud document signing and workflow automation platform by airSlate offering embedded signing, document generation, and AI/MCP integrations. | **$8.00/user/month** (Business plan, annual; 100 signature invites/user/year) | **7-day free trial** (full feature access, up to 10 invites/day; no credit card required); no permanent free tier | ~$1.25 Billion private valuation (parent airSlate) / ~$200 Million annual revenue |
| **[PandaDoc](https://www.pandadoc.com/)** | End-to-end document workflow platform combining proposals, quotes, CPQ, contract negotiation, and legally binding e-signatures. | **$19.00/seat/month** (Starter plan, annual; unlimited document sends) | **Free-forever plan**: 5 documents/month with payment processing; **14-day free trial** for Business tier + **Free API sandbox** | ~$1.0 Billion private valuation (Unicorn) / ~$100 Million ARR |
| **[OneSpan Sign](https://www.onespan.com/)** | Enterprise-grade digital agreement and authentication platform built for heavily regulated banking, finance, insurance, and government sectors. | **$22.00/user/month** (Professional plan, annual; up to 1,000 transactions/user/year) | **30-day free trial** (full enterprise feature evaluation); **Free non-expiring developer sandbox** | ~$800 Million market cap / ~$243 Million annual revenue |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[DocuSeal](https://github.com/docusealco/docuseal)** | [![Stars](https://img.shields.io/github/stars/docusealco/docuseal?style=social&color=white)](https://github.com/docusealco/docuseal/stargazers) | **The leading open-source DocuSign alternative for complete envelope workflows.** AGPLv3 with Section 7(b) additional terms [citation:13]. WYSIWYG PDF form builder with 12 field types (signature, date, file, checkbox, etc.), multiple submitters per document, automated email notifications, files stored on disk or S3/GCS/Azure, **automatic PDF eSignature and signature verification**, mobile-optimized signing in 14 languages, REST API and webhooks, and Docker deployment in minutes. Pro features add white-label branding, SSO/SAML, SMS verification, and embedded signing (React/Vue/Angular/JS) [citation:13]. **Best for teams wanting a turnkey self-hosted e-signature platform.** |
| **[Digitorus pdfsign](https://github.com/digitorus/pdfsign)** | [![Stars](https://img.shields.io/github/stars/digitorus/pdfsign?style=social&color=white)](https://github.com/digitorus/pdfsign/stargazers) | **The most capable open-source PDF signing library for developers embedding cryptographic signatures.** Go library and CLI (~172 stars) for digitally signing and verifying PDFs with **PAdES_B_T format**, supporting post-quantum ML-DSA signing [citation:4][citation:14]. Fluent API for signature placement and appearance customization with TTF fonts. **External signer integrations** for AWS KMS, GCP KMS, Azure Key Vault, PKCS#11/HSM, and CSC (Cloud Signature Consortium) [citation:4]. CLI: `pdfsign sign -name "John Doe" input.pdf output.pdf cert.crt key.key`. **Best for developers building signing into their own applications.** |
| **[SignFuz](https://wordpress.org/plugins/sign-fuz/)** | — | **Self-hosted e-signature engine for WordPress with zero mandatory SaaS fees.** GPLv2 licensed [citation:3]. Pixel-perfect PDF field placement (signature, name, date, text), **multi-party signing with parallel or sequential workflows**, Tailwind/React UI, **cryptographic evidence trail** (signer consent, timestamps, SHA-256 event chains), automated Certificate of Completion, and private storage vault. REST API endpoints for document and envelope management [citation:3]. **Best for WordPress sites needing native e-signature without external services.** |
| **[@hasna/signatures](https://www.npmjs.com/package/@hasna/signatures)** | — | **Developer-first e-signature platform with MCP, CLI, and REST API.** SQLite database, zero external dependencies at runtime [citation:10]. Sign PDFs with text signatures (Google Fonts rendering), image signatures, or AI-generated drawings. Detects existing signature fields in PDF forms. Full-text search, session tracking, and connector integration for external signing tools. Three interfaces: `open-signatures` CLI, `signatures-mcp` (MCP server), `signatures-serve` (REST API) [citation:10]. **Best for developers wanting a lightweight, scriptable signing tool with AI-agent integration.** |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[pyHanko](https://github.com/MatthiasValvekens/pyHanko)** | — | Python library for PDF signing with PAdES/CMS support, RFC-3161 timestamps, and LTV (long-term validation). Google KMS signer integration available [citation:7]. **Best for Python teams needing programmatic PDF signing.** |
| **[LibreSign](https://github.com/LibreSign/libresign)** | — | Nextcloud-integrated e-signature. AGPL-3.0, PHP/JavaScript. Sign documents directly within your Nextcloud instance [from prior research]. **Best for organizations already on Nextcloud.** |
| **[PassSign](https://github.com/topics/document-signing)** | — | Open protocol extending the **passkey ceremony into legally meaningful, cryptographically verifiable document signing**—sign a contract the way you sign into a website [citation:1]. **Early-stage; watch for maturity.** |

**Frameworks for building custom systems**: Choose **DocuSeal** for a complete self-hosted e-signature platform with visual field builder and mobile signing , **pdfsign** for embedding PAdES/CMS cryptographic signatures into Go applications with HSM/KMS integration , or **SignFuz** for WordPress-native signing with cryptographic audit trails . For Python, **pyHanko** provides programmatic PDF signing with timestamping and LTV support .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- E-signature platforms handle legally binding agreements and signer PII; ensure compliance with ESIGN, UETA, eIDAS, and applicable data protection regulations. **Audit trails and certificate integrity are legally critical**—do not deploy open-source signing without validating the tamper-evidence of completed PDFs.
- **Commercial pricing models vary and hidden costs are common.** DocuSign and Adobe charge **per-seat subscriptions**—predictable for small teams but expensive when signing is automated at volume because seats don't map to API calls [citation:2]. Dropbox Sign charges **per signature-request volume** (API Essentials: $75/month for 50 requests), which scales naturally with automation [citation:2]. PandaDoc uses **document quotas with overages (~$0.85/document)** [citation:2]. **Open-source licensing varies significantly**: DocuSeal is **AGPLv3 with Section 7(b) additional terms** —review the LICENSE and LICENSE_ADDITIONAL_TERMS before commercial use [citation:13]. SignFuz is **GPLv2** [citation:3]. pdfsign is a Go library (check repository license). **Always validate cryptographic signature compliance (eIDAS, ESIGN) and audit trail integrity before relying on any tool for legally binding agreements.**

---

**Made for developers, legal ops teams, and organizations building document signing infrastructure.**  
Let's make digital signature and document signing more open, verifiable, and accessible.
