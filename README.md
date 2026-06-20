# StewardDesk

> **Give your counting team their own independent record.** A free reconciliation tool for church volunteer helpers and assistant treasurers — built by a church treasurer, for the helpers who make it all work.

[StewardDesk.com](https://stewarddesk.com) · Free · Open to all churches

---

## What is StewardDesk?

StewardDesk gives church counting volunteers a way to count, reconcile, and sign off on Sunday's offering — independently from the treasurer's books. Cash, checks, and digital giving are all matched and verified, and every count ends in a printable, signed report that stands on its own as a record.

It is **not** an accounting system and it doesn't replace your treasurer's books. It's the independent check that should exist alongside them — the same kind of internal control most small churches know they should have, but rarely have the tools to actually do.

As a volunteer church treasurer myself, I built StewardDesk because I know firsthand the challenges helpers face. Manual counting, cross-referencing digital giving platforms, and producing a clean, defensible record takes time — time that volunteers don't always have. StewardDesk is here to help.

---

## Who Is It For?

- **Treasurers & lead helpers**, who set up the church's categories and integrations once, then get an independent check on every count going forward — without doing the counting themselves
- **Counting volunteers**, who count, sync, reconcile, and sign each week — no setup to manage, no accounting background required
- **Churches under 250 members**, that rely on rotating volunteers rather than a paid finance team, and want something free, simple, and trustworthy

---

## The Report

Every count produces a printable record:

- **Physical count** — coins and bills by denomination, checks logged by number
- **Digital giving** — Zeffy and bank-synced transfers (Zelle, Venmo, direct deposit), matched to members
- **Validation** — cash + checks + digital, checked against data entry automatically, with a clear match/mismatch indicator before anyone signs
- **Two signatures** — Counted by, Verified by, both dated — a real record for your files, your board, or your auditor

This report is the core of StewardDesk. Everything else exists to make producing it fast and accurate.

---

## Features

### Guided Offering Count
A structured, step-by-step counting workflow — coins, bills, and checks — so every helper counts the same way, every week.

### Automatic Reconciliation
Physical count and data entry are validated against each other the moment the count is finished. Mismatches surface immediately, before the report is signed.

### Digital Giving, Reconciled Alongside Cash
Digital gifts aren't a separate spreadsheet — they're staged, matched to members, and folded into the same reconciliation as cash and checks.

### Zeffy Integration
Transactions from [Zeffy](https://www.zeffy.com), the free online giving platform, are pulled in line by line and auto-matched to members (by email, then by name). Helpers review and confirm the match before it's processed into a contribution record.

### Bank Transaction Review (Plaid)
Connect your church bank account via [Plaid](https://plaid.com) to pull in individual member-initiated transfers — Zelle, Venmo, direct deposit — filtered down to likely contributions, not every transaction in the account. Helpers review, match to a member, and process or disregard each line.

### Staging, Not Blind Import
Both Zeffy and bank-synced transactions land in a staging area first — never written directly into contribution records. A helper reviews, corrects the member match, assigns the right category, and only then processes it through. Anything that isn't a real contribution can be disregarded.

### Contribution Tracking
Record and manage member contributions by fund and giving category, with full history — cash, check, or digital, all in one place.

### Giving Categories
Organize contributions by fund, with support for parent and child category structures, matching how your church already manages its finances.

### Member Management
A simple member directory tied to contribution records, with quick add/lookup during the counting process.

### CSV / Excel Member Import
First-time setup for a new church doesn't mean typing in your member list by hand — admins can bulk-import members from a spreadsheet to get started quickly.

### Printable Reports
Generate a clean, signed, dated reconciliation report for any service — ready for your files, your treasurer, or your board.

### Role-Based Access
Counting volunteers run the weekly count and sync. Setup, integrations, and admin tools stay with the treasurer or lead helper.

### Secure by Design
Every account is protected with mandatory two-factor authentication (2FA), account lockout policies, and secure session management.

---

## Multi-Church Support

StewardDesk supports **multiple churches on a single platform**. Each church gets a completely isolated workspace — members, contributions, counts, and giving records are never shared between organizations. Any church can sign up for free at [StewardDesk.com](https://stewarddesk.com).

---

## Giving Platform Integrations

StewardDesk connects with the digital giving platforms your church already uses, so helpers can reconcile online giving without manual data entry.

**Currently supported:**
- [Zeffy](https://www.zeffy.com) — free online giving platform

**Coming soon:**
- Planning Center Giving
- Pushpay
- Tithe.ly
- And more based on community demand

> **Note:** Giving platform integrations and bank sync are set up once by the church admin (treasurer or lead helper) — including any API key or bank connection. Once that's done, counting volunteers can run syncs and review transactions themselves each week. StewardDesk provides step-by-step setup guides — no advanced technical knowledge required.

**Don't see your giving platform?**
Open a request on our [GitHub Issues](https://github.com/joshmoua864/stewarddesk/issues) page and we'll consider adding it. Community feedback drives our integration roadmap.

---

## Built With

| Layer | Technology |
|-------|-----------|
| Frontend | [Blazor Server](https://dotnet.microsoft.com/apps/aspnet) + [MudBlazor](https://mudblazor.com) |
| Backend | ASP.NET Core 8 |
| ORM | [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core/) |
| Database | [Azure SQL](https://azure.microsoft.com/en-us/products/azure-sql) |
| Hosting | [Azure App Service](https://azure.microsoft.com/en-us/products/app-service) |
| Email | [Azure Communication Services](https://azure.microsoft.com/en-us/products/communication-services) |
| Bank Integration | [Plaid](https://plaid.com) |
| Giving Integration | [Zeffy](https://www.zeffy.com) |
| CI/CD | GitHub Actions |

---

## Keep StewardDesk Free

StewardDesk is and always will be free for churches — no subscriptions, no paid tiers. If it helps your volunteers save time and gives your church a real independent record each week, consider supporting the project with a donation.

👉 [Support StewardDesk](https://stewarddesk.com/donate)

---

## Getting Started

Visit [StewardDesk.com](https://stewarddesk.com) to register your church and get started for free. No credit card. No subscription. No catch.

---

*Built with care by a volunteer church treasurer who knows the work you do matters.*
