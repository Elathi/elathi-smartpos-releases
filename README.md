<!-- SMARTPOS_LANDING_START -->
# Elathi SmartPOS

## Offline-first retail intelligence for everyday stores

Elathi SmartPOS is a Windows point-of-sale workspace for billing, inventory,
GST invoices, purchasing, customer credit, supplier balances, reports, notes,
and reminders. It is designed for dependable store operations even when the
internet is unavailable.

**[Download the latest signed Windows release](https://github.com/Elathi/elathi-smartpos-releases/releases/latest)** · **[View release history](https://github.com/Elathi/elathi-smartpos-releases/releases)** · **[Visit elathi.xyz](https://elathi.xyz/)**

> This repository publishes signed SmartPOS installers and updater manifests.
> A stable download is shown below only after the release owner publishes one.

## Why stores use SmartPOS

| POS billing | Inventory control | Retail visibility |
| --- | --- | --- |
| Fast barcode and catalog billing, multiple payments, returns, discounts, and receipts | Product pricing, batches, expiry, FEFO, stock movements, repacking, and labels | Supplier/customer balances, purchase bills, sales profit, GST reports, and operational reminders |

## Feature highlights

- **POS billing and payments** — barcode scanning, product search, batch-aware selling, cash/UPI/card/wallet payments, credit bills, returns, and customer display support.
- **Inventory and batch tracking** — product pricing, stock types, batches/lots, expiry management, FEFO, stock counts, repacking, barcode labels, and price history.
- **GST invoicing and receipts** — configurable GST, invoice templates, thermal/page previews, PDF/print paths, e-invoice support, and localized receipt text.
- **Suppliers and purchase bills** — purchase orders, receiving, supplier ledgers, payment allocation, batch identities, and outstanding-liability reporting.
- **Customers, credit, and loyalty** — customer history, account due, payments, loyalty tiers, rewards, and customer-facing receipts.
- **Reports and analytics** — sales/profit, tax, purchasing, inventory, cash reconciliation, dashboard KPIs, and actionable low-stock signals.
- **Calendar, notes, and reminders** — scheduled notes, quick calendar notes, supplier visits, follow-ups, and reminder notifications.
- **Signed updates and data safety** — signed Windows updates, safe-idle installation, in-place upgrades, backups, privacy blur, and offline-first storage.

## Product tour

The gallery uses fictional, read-only browser showcase data. It contains no
customer credentials, personal phone numbers, or production business data.

| Dashboard | POS billing |
| --- | --- |
| ![SmartPOS dashboard overview](showcase/dashboard.webp) | ![SmartPOS POS billing with a demo cart](showcase/pos-billing.webp) |

| Products and inventory | Customers and suppliers |
| --- | --- |
| ![SmartPOS compact products table](showcase/products.webp) | ![SmartPOS customer and supplier workspace](showcase/customers-suppliers.webp) |

| Saved bills and analytics | Reports |
| --- | --- |
| ![SmartPOS saved bills and profit analytics](showcase/saved-bills.webp) | ![SmartPOS reports workspace](showcase/reports.webp) |

| Calendar and notes |
| --- |
| ![SmartPOS calendar with notes and reminders](showcase/calendar-notes.webp) |

## Detailed feature list

<details>
<summary>Billing, checkout, and customer display</summary>

- Barcode, SKU, name, alternate-barcode, and typo-tolerant product search.
- Comfortable cashier cart tables with quantity, UOM, discount, tax, MRP, and sale controls.
- Batch/variant selection when the same barcode has multiple sellable identities.
- Split payment, held bills, credit, returns, gift packing, and bill-level charges.
- Customer display presentation with cart, payment, offers, and promotional media.
</details>

<details>
<summary>Catalog, stock, purchasing, and suppliers</summary>

- General, batch/lot, packing, size/color, and serial/IMEI stock workflows.
- Purchase orders, receiving, bill linking, supplier payment history, and purchase analytics.
- Expiry/FEFO workflows, cycle counts, stock adjustments, repacks, and label printing.
- Compact back-office tables with all-column detail grids at narrow desktop widths.
</details>

<details>
<summary>Invoices, tax, and reporting</summary>

- GST-inclusive and GST-exclusive calculations with CGST/SGST/IGST presentation.
- Invoice Designer settings shared across previews, saved bills, PDF, page, and thermal output.
- Sales, profit, inventory, procurement, tax, cash, and operational reports.
- Export and Tally-oriented workflows where available in the installed app.
</details>

<details>
<summary>Offline-first operations and safety</summary>

- Local business database and typed native bridge for the installed application.
- Signed release artifacts with signature verification before installation.
- Existing store data is preserved during in-place upgrades; back up before major changes.
- Browser `?showcase=1` is a read-only visual preview only and is never a business database.
</details>

## Installation and upgrades

1. Open the latest release and download the signed Windows installer.
2. Install SmartPOS on the store workstation. Windows may ask for confirmation because the installer is downloaded from GitHub.
3. On an existing installation, close active sales and take a backup before upgrading.
4. SmartPOS verifies the updater signature and preserves the local database during an in-place upgrade.
5. After installation, use **Settings → Updates** or the top-bar update control to check the signed manifest.

Never replace an installer or signature with a file from an unofficial mirror.
The updater waits for a safe idle state and does not restart over an active sale.

## Browser showcase

Run the browser preview with `?showcase=1` to explore deterministic fictional
records for screenshots and product review. The banner reads **Demo mode · Read
only**. Reloading resets the fixture; mutating actions are intentionally
blocked. The installed Tauri application ignores this flag and always uses the
native store bridge.

## Support and product links

- **Release history and signed downloads:** [GitHub Releases](https://github.com/Elathi/elathi-smartpos-releases/releases)
- **Stable updater manifest:** [`latest.json`](https://github.com/Elathi/elathi-smartpos-releases/releases/latest/download/latest.json)
- **Product website:** [elathi.xyz](https://elathi.xyz/)
- **Operator help:** use the in-app Guide and contextual help in SmartPOS.

<!-- SMARTPOS_RELEASES_MANAGED_START -->
## Signed releases

The latest stable release is **v3.40.8** (overview refreshed
23 September 2026 UTC).

- [Download the latest signed Windows release](https://github.com/Elathi/elathi-smartpos-releases/releases/latest)
- [Stable update manifest](https://github.com/Elathi/elathi-smartpos-releases/releases/latest/download/latest.json)
- [Read the current release notes](https://github.com/Elathi/elathi-smartpos-releases/releases/tag/v3.40.8)
- Existing installations can use **Settings → Updates** or the global update control.
- SmartPOS verifies the signed updater and preserves the local database during in-place upgrades.

Release-specific compatibility and migration notes are maintained in the
matching GitHub release body. If this repository has no published release yet,
the release owner should leave this managed section at its pre-release state
until the first signed publication completes.

<!-- SMARTPOS_RELEASES_MANAGED_END -->

<!-- SMARTPOS_LANDING_END -->

<!-- SMARTPOS_RELEASES_MANAGED_START -->
## Signed releases

No stable release has been published to this repository yet. This section will be updated automatically when the next signed SmartPOS release is published.

- [Release history](https://github.com/Elathi/elathi-smartpos-releases/releases)
- [Updater manifest](https://github.com/Elathi/elathi-smartpos-releases/releases/latest/download/latest.json) (available after the first stable release)

Published installers, signatures, and manifests remain immutable. SmartPOS verifies signatures before installation and preserves the local store database during upgrades.
<!-- SMARTPOS_RELEASES_MANAGED_END -->
