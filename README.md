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
|---|---|---|
| **[DocuSeal](https://github.com/docusealco/docuseal)** | [![Stars](https://img.shields.io/github/stars/docusealco/docuseal?style=social&color=white)](https://github.com/docusealco/docuseal/stargazers) | **The leading open-source DocuSign alternative for complete envelope workflows.** AGPLv3 with Section 7(b) terms. WYSIWYG PDF form builder with 12 field types, multiple submitters, automated email notifications, S3/Azure/GCS storage, automatic PDF cryptographic eSignature, mobile signing in 14 languages, REST API, webhooks, and 1-click Docker deployment. Pro adds white-label branding, SSO/SAML, SMS OTP, and embedded React/Vue/JS components. |
| **[Documenso](https://github.com/documenso/documenso)** | [![Stars](https://img.shields.io/github/stars/documenso/documenso?style=social&color=white)](https://github.com/documenso/documenso/stargazers) | **The modern open-source document signing infrastructure built on Next.js, Prisma, and TypeScript.** Designed for transparency and auditability. Features multi-recipient envelope workflows, template management, cryptographic signature verification, self-hosting via Docker Compose, and developer-first REST/tRPC APIs. |
| **[OpenSign](https://github.com/OpenSignLabs/OpenSign)** | [![Stars](https://img.shields.io/github/stars/OpenSignLabs/OpenSign?style=social&color=white)](https://github.com/OpenSignLabs/OpenSign/stargazers) | **Free & open-source alternative to DocuSign, PandaDoc, and Adobe Sign.** Built on Node.js, Next.js, and MongoDB/PostgreSQL. Supports PDF document signing, customizable templates, multi-party sequential/parallel signing, audit trails with IP/timestamp logging, email notifications, and self-hosted Docker deployment. |
| **[open-pdf-sign](https://github.com/open-pdf-sign/open-pdf-sign)** | [![Stars](https://img.shields.io/github/stars/open-pdf-sign/open-pdf-sign?style=social&color=white)](https://github.com/open-pdf-sign/open-pdf-sign/stargazers) | **Open-source, self-hosted CLI and REST service for digitally signing PDF files.** Supports PAdES baseline signatures (PAdES-B-B, PAdES-B-T, PAdES-B-LT, PAdES-B-LTA), RFC-3161 trusted timestamps, visual signature profiles, HSM/PKCS#11 keys, and smartcard signing. |
| **[node-signpdf](https://github.com/vbuch/node-signpdf)** | [![Stars](https://img.shields.io/github/stars/vbuch/node-signpdf?style=social&color=white)](https://github.com/vbuch/node-signpdf/stargazers) | **Simple, zero-dependency Node.js library for cryptographic PDF signing.** Injects digital signatures conforming to PDF specifications using PKCS#7 / CMS signatures into existing byte buffers without rewriting the whole document. |
| **[LibreSign](https://github.com/LibreSign/libresign)** | [![Stars](https://img.shields.io/github/stars/LibreSign/libresign?style=social&color=white)](https://github.com/LibreSign/libresign/stargazers) | **Nextcloud-integrated digital signature and document signing application.** AGPL-3.0. Enables organizations already running self-hosted Nextcloud to request and perform legally binding digital signatures with full audit logging, OTP signer verification, and local file sovereignty. |
| **[pyHanko](https://github.com/MatthiasValvekens/pyHanko)** | [![Stars](https://img.shields.io/github/stars/MatthiasValvekens/pyHanko?style=social&color=white)](https://github.com/MatthiasValvekens/pyHanko/stargazers) | **Comprehensive Python library for digitally signing and validating PDF documents.** Strict support for PAdES, CMS/PKCS#7, cryptographic timestamps (RFC 3161), revocation checking (CRL/OCSP), Long-Term Validation (LTV), PKCS#11/HSMs, and AWS/GCP KMS cloud signer integrations. |
| **[SignServer CE](https://github.com/Keyfactor/signserver-ce)** | [![Stars](https://img.shields.io/github/stars/Keyfactor/signserver-ce?style=social&color=white)](https://github.com/Keyfactor/signserver-ce/stargazers) | **Enterprise-grade, server-side digital signature and timestamping system.** Developed by Keyfactor/PrimeKey (LGPL-2.1). Centralizes cryptographic PDF document signing, code signing, and validation with HSM key protection and high-throughput clustering. |
| **[letsseal](https://github.com/letsseal/letsseal)** | [![Stars](https://img.shields.io/github/stars/letsseal/letsseal?style=social&color=white)](https://github.com/letsseal/letsseal/stargazers) | **Open standard and engine for cryptographically sealing files and documents.** Provides tamper-evident verification, Sigstore keyless OIDC signer identity integration, and X.509 PAdES compliance to prove documents are authentic and unmodified. |
| **[Digitorus pdfsign](https://github.com/digitorus/pdfsign)** | [![Stars](https://img.shields.io/github/stars/digitorus/pdfsign?style=social&color=white)](https://github.com/digitorus/pdfsign/stargazers) | **Pure Go library and CLI for digitally signing and verifying PDFs with PAdES_B_T format.** Supports post-quantum ML-DSA signatures, fluent visual appearance configuration, TTF font embedding, and external signing backends including AWS KMS, GCP KMS, Azure Key Vault, and PKCS#11/HSMs. |
| **[signed-page/pdf](https://github.com/signed-page/pdf)** | [![Stars](https://img.shields.io/github/stars/signed-page/pdf?style=social&color=white)](https://github.com/signed-page/pdf/stargazers) | **Rust utility for cryptographically signing PDFs using GPG and Sigstore keyless identity.** Enables multi-party contract signing backed by public OIDC accounts (Google/GitHub/Microsoft) with immutable cryptographic transparency logs without complex PKI infrastructure. |

### Additional Specialized Tools

| Project | Star Badge | Description |
|---|---|---|
| **[signature_pad](https://github.com/szimek/signature_pad)** | [![Stars](https://img.shields.io/github/stars/szimek/signature_pad?style=social&color=white)](https://github.com/szimek/signature_pad/stargazers) | **HTML5 canvas-based smooth signature drawing library.** Smooth Bezier-curve stroke interpolation for capturing responsive handwritten signatures across mobile and desktop touchscreens/styluses. |
| **[react-signature-canvas](https://github.com/agilgur5/react-signature-canvas)** | [![Stars](https://img.shields.io/github/stars/agilgur5/react-signature-canvas?style=social&color=white)](https://github.com/agilgur5/react-signature-canvas/stargazers) | **React component wrapper around `signature_pad`.** Provides trimming, canvas resizing, ref handles, and export utilities for React web applications. |
| **[SignFuz](https://wordpress.org/plugins/sign-fuz/)** | — | **Self-hosted e-signature plugin for WordPress.** GPLv2 licensed. PDF field placement, multi-party sequential/parallel signing, and cryptographic audit evidence trail without external SaaS dependencies. |
| **[@hasna/signatures](https://www.npmjs.com/package/@hasna/signatures)** | — | **Developer-first e-signature engine with MCP server, CLI, and REST API.** Zero external runtime dependencies, SQLite storage, font/image drawing signature generator, and AI-agent compatibility. |

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
