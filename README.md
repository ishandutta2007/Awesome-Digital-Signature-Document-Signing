# Awesome-Digital-Signature-Document-Signing

# Top Digital Signature & Document Signing Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on E-Signature Workflows, PDF Cryptographic Sealing & Tamper-Evident Audit Trails*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Signature & Document Signing**. These tools help organizations send documents for legally binding electronic signatures—covering envelope creation, field placement, signer authentication, audit trails, and the cryptographic sealing of completed PDFs.

**Examples** include DocuSign, Adobe Acrobat Sign, Dropbox Sign, PandaDoc, Zoho Sign, SignNow, OneSpan Sign, DocuSeal, and Digitorus pdfsign (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted e-signature workflows, open-source PDF signing engines, and community-driven document packaging—ideal for developers embedding signing into their own products and organizations seeking data sovereignty over per-envelope SaaS pricing. The open-source landscape spans two distinct layers: **complete signing platforms** (DocuSeal, SignFuz) for turnkey envelope workflows, and **cryptographic signing libraries** (pdfsign, pyHanko) for embedding PAdES/CMS signatures into custom applications.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[DocuSign](https://www.docusign.com/)** | Industry-standard e-signature platform with envelopes, templates, and certificate of completion. **Per-user seat pricing with envelope caps** on lower tiers (Standard: 100 envelopes/user/year). API access on commercial plans; free developer sandbox available for testing [citation:2][citation:12]. | Personal: **$11/month** (5 envelopes/month); Standard: **$30/user/month** (annual, 100 envelopes/user/year) [citation:12] | **Free developer sandbox** (no credit card) for API testing; no permanent free tier for production [citation:2] |
| **[Adobe Acrobat Sign](https://www.adobe.com/sign.html)** | E-signature bundled into Acrobat plans. **Per-license billing** with seat subscriptions; free Developer Edition with full REST API access and sandbox for testing [citation:2]. | Acrobat Standard for teams: **$16.99/user/month** (annual); Pro: **$23.99/user/month** [citation:12] | **Free Developer Edition + sandbox** for API development; production requires paid Acrobat plan [citation:2] |
| **[Dropbox Sign](https://sign.dropbox.com/)** | E-signature platform (formerly HelloSign) with **unlimited signature requests on paid plans**—no envelope caps. Official SDKs for Python, Node, Java, C#, PHP, Ruby, Go [citation:2]. | Essentials: **$15/month** (annual, 1 user, unlimited requests); Standard: **$25/user/month** (2-user minimum) [citation:12] | **Developer test mode** available via developer portal; production is volume-priced [citation:2] |
| **[PandaDoc](https://www.pandadoc.com/)** | Document workflow platform combining e-signature, proposals, and CPQ. Free sandbox with API key for testing; production requires plan with API access [citation:2]. | Free: **$0** (5 documents/month); Starter: **$19/seat/month** (annual) [citation:12] | **Free**: 5 documents/month; **free sandbox** with API key for development [citation:2] |
| **[SignNow](https://www.signnow.com/)** | E-signature platform with embedded signing and templates. Official MCP server available for AI agents to access e-signature workflows [citation:1]. | Quote-only (tiered by users/volume) | Free trial available; no permanent free tier |
| **[OneSpan Sign](https://www.onespan.com/)** | Enterprise e-signature with transaction-based or user-based pricing. Developer sandbox available. | Quote-only (enterprise contract) | Free developer sandbox; trial via sales |
| **[Zoho Sign](https://www.zoho.com/sign/)** | E-signature within the Zoho ecosystem. Integrated with Zoho CRM, Desk, and Writer. | Quote-only (bundled with Zoho plans) | Free trial via Zoho signup |

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
