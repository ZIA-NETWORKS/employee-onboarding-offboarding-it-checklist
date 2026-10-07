# employee-onboarding-offboarding-it-checklist
A practical IT security checklist for onboarding and offboarding employees, maintained by ZIA Networks.
# Secure Employee Onboarding & Offboarding: The IT Checklist Most Businesses Skip

> A practical, copy-and-use IT security checklist maintained by **ZIA Networks**.

![Checklist](https://img.shields.io/badge/type-checklist-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)

## Table of Contents

- [Overview](#overview)
- [Why This Gets Skipped](#why-this-gets-skipped)
- [Onboarding Checklist](#onboarding-checklist)
- [Offboarding Checklist](#offboarding-checklist)
- [Common Mistakes](#common-mistakes)
- [Making It Stick](#making-it-stick)
- [Quarterly Audit](#quarterly-audit)
- [Contributing](#contributing)
- [About [Brand Name]](#about-brand-name)
- [License](#license)

## Overview

Every account you create, and every account you forget to close, is a potential doorway into your business. This repo gives you a simple checklist for both ends of the employee lifecycle, so you can answer one question confidently:

**Who still has access to what?**

> [!NOTE]
> Copy the checklists below into your ticketing system, HR workflow, or wiki. GitHub renders `- [ ]` items as interactive checkboxes in issues and pull requests.

## Why This Gets Skipped

| Problem | What happens |
|---|---|
| Nobody owns the process | HR assumes IT did it. IT assumes HR would say something. |
| It only feels urgent after an incident | Forgotten accounts are harmless until they aren't. |
| Memory is the system | "We'll remember to turn it off" fails when things get busy. |

## Onboarding Checklist

Complete **before the employee's first day**.

- [ ] **Least privilege:** grant only the access the role needs (don't copy a coworker's permissions)
- [ ] **MFA enabled** on email and all critical apps
- [ ] **Managed device issued:** encrypted, patched, endpoint protection installed, auto-updates on
- [ ] **Password manager** set up (never send credentials by email or chat)
- [ ] **Acceptable use policy** signed
- [ ] **Security briefing** completed (phishing, data handling, who to contact)
- [ ] **Assets documented:** accounts, licenses, and devices logged in one place

## Offboarding Checklist

Complete **on the day of departure** (or at the moment of exit for sensitive cases).

- [ ] **Disable accounts immediately** (suspend first, delete later)
- [ ] **Revoke access everywhere:** email, VPN, cloud storage, CRM, accounting, project tools
- [ ] **Remove shadow IT:** apps and tools the employee signed up for on their own
- [ ] **Rotate shared secrets:** shared passwords, Wi-Fi keys, API tokens
- [ ] **Recover company assets:** laptop, phone, badges, keys, security tokens
- [ ] **Wipe company data** from personal devices (work profile only)
- [ ] **Transfer data:** forward email, reassign files, calendars, and customer accounts
- [ ] **Remove admin roles,** vendor portal access, and mailing list memberships
- [ ] **Check for** auto-forwarding rules and personal cloud syncing
- [ ] **Review access logs** for unusual downloads or logins in the last few weeks
- [ ] **Sign-off recorded** with name and date

> [!IMPORTANT]
> Suspend accounts first and delete later. Deleting too early can destroy data you may need for legal, financial, or handover reasons.

## Common Mistakes

- Ignoring **shadow IT** (free tools and extensions adopted without approval)
- Leaving accounts active "just in case"
- Treating contractors and temps differently (they need the same process, ideally with a built-in end date)
- Having **no single owner** accountable for the checklist

## Making It Stick

1. Turn these lists into a **template** that HR and IT both sign off on.
2. **Trigger offboarding automatically** from HR's resignation or termination workflow.
3. **Automate** account creation and removal with identity tools where possible.
4. **Assign one owner** responsible for completion.
5. **Audit quarterly** (see below).

## Quarterly Audit

- [ ] Export the list of active user accounts from every major system
- [ ] Compare against the current employee and contractor roster
- [ ] Disable or investigate any account without a matching active person
- [ ] Review admin and privileged role assignments
- [ ] Confirm shared credentials were rotated after any departures

> [!TIP]
> If you do only one thing this week, compare your active accounts to your current staff list. If you find someone who left months ago, you've seen why this matters.

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a branch: `git checkout -b improve-offboarding-list`
3. Commit your changes: `git commit -m "Add item for SaaS license reclamation"`
4. Push the branch: `git push origin improve-offboarding-list`
5. Open a pull request

Please keep items practical, vendor-neutral, and easy for non-technical readers to follow.

## About ZIA Networks

**ZIA Networks** provides managed IT and cybersecurity support for businesses in Santa Fe, Albuquerque, and across New Mexico. We can build and automate your onboarding and offboarding workflow so nothing slips through the cracks.

- 🌐 Website:https://www.zianetworks.net/
- ✉️ Email: info@zianetworks.com
- 📞 Phone: (505) 428-6544

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, adapt, and share this checklist.

---

*Maintained by [Brand Name]. Last updated: October 2026.*
