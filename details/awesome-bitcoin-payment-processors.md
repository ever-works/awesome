# Awesome Bitcoin Payment Processors

A curated, open-source directory of Bitcoin payment processors and related services for merchants, businesses, nonprofits, and developers who want to accept Bitcoin payments.

**URL:** https://github.com/alexk111/awesome-bitcoin-payment-processors#readme  
**Category:** Themed Directories  
**Topics/Tags:** Bitcoin, payments, blockchain

---

## Overview

Awesome Bitcoin Payment Processors is a community-maintained list that catalogs different types of Bitcoin payment processors. It focuses on tools that help you accept Bitcoin (and in some cases Lightning) payments, either via self-hosted software or third‑party services.

The repository is structured as an "awesome list" and links out to individual projects, rather than providing its own processing service.

---

## Features

### 1. Curated Directory
- Organized list of Bitcoin payment processors and related services.
- Emphasis on merchant and business use cases (online stores, nonprofits, services).
- Includes both on-chain Bitcoin and Lightning Network support where applicable.
- Each processor entry typically includes: fees, Lightning support, payout model, fiat conversion options, and basic requirements.

### 2. Self-Hosted Bitcoin Payment Processors Section
Self-hosted processors give you full control over infrastructure and funds, with no third‑party custody. The list includes, among others:

- **BTCPay Server**  
  - Fees: No fees charged by the software.  
  - Lightning: Supported.  
  - Payouts: Directly to your own wallet.  
  - Fiat conversion: Possible via Strike plugin or exchange integrations (e.g., Kraken).  
  - Requirements: ~2 GB RAM, 80 GB storage, Docker.

- **One Time Address**  
  - Fees: No fees.  
  - Lightning: Not supported (on-chain only).  
  - Payouts: Directly to your wallet.  
  - Fiat conversion: Not provided.  
  - Requirements: Node.js.

- **CryptoWoo** (WordPress/WooCommerce plugin)  
  - Fees: Paid plugin, $34–$99 per year.  
  - Lightning: Not supported (Bitcoin-focused).  
  - Payouts: Directly to your wallet.  
  - Fiat conversion: Not provided.  
  - Requirements: PHP 5.6+, WordPress 4.3+, WooCommerce 3.0+.

- **BitcartCC**  
  - Fees: No fees.  
  - Lightning: Supported.  
  - Payouts: Directly to your wallet.  
  - Fiat conversion: Not provided.  
  - Requirements: ~1 GB RAM, 10 GB storage, Docker.

- **LnMe**  
  - Fees: No fees.  
  - Lightning: Supported.  
  - Payouts: Directly to your Lightning node wallet.  
  - Fiat conversion: Not provided.  
  - Requirements: Existing LND node.

- **SatSale**  
  - Fees: No fees.  
  - Lightning: Supported.  
  - Payouts: Directly to your wallet.  
  - Fiat conversion: Optional swap to USDT on Liquid (no‑KYC) for those who want to reduce BTC price exposure.  
  - Requirements: Python; Bitcoin node; Lightning node (for Lightning payments).

> Note: The repository includes additional processors and categories beyond what appears in the excerpt (e.g., third‑party processors, donation tools, e‑commerce plugins). Those are discoverable directly in the README.

### 3. Technical & Operational Details
- Highlights infrastructure needs for each self-hosted processor (RAM, storage, software stack, Docker, node requirements, etc.).
- Indicates which solutions route funds directly to your own wallet vs. mediated by other tools.
- Notes availability (or absence) of automatic fiat conversion.

### 4. Open Source & Community
- Hosted on GitHub as an open list.
- Contributions are accepted via standard GitHub workflow (pull requests, issues).
- Licensed (license file present in repo). 

---

## Pricing

The list itself is free to use. It documents pricing for some processors when applicable. From the visible content:

- **CryptoWoo**: Paid plugin, **$34–$99 per year** depending on license/plan.
- Other highlighted processors (BTCPay Server, One Time Address, BitcartCC, LnMe, SatSale): **no software fees** indicated in the list (infrastructure and hosting costs still apply).

For full, up-to-date pricing of each processor, the list links directly to each project’s official website or documentation.

---

## Use Cases

- Adding Bitcoin and/or Lightning payments to an online shop.
- Integrating Bitcoin payments into custom applications or services.
- Running a fully self-hosted payment stack with direct wallet control.
- Comparing processors based on fees, technical stack, Lightning support, and fiat conversion options.

---

## License

- The repository includes a `LICENSE` file; terms apply to the list’s content, not to the individual processors it references.

For full details and the complete catalog, visit the GitHub repository README.