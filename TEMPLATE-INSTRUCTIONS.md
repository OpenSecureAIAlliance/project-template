# How to Use This Template

This repository is a **GitHub template** for creating new Open Secure AI Alliance (OSAIA) Working Group repositories. When the Steering Committee approves a new Working Group, the Steering Committee or WG lead creates a new repo using this template.

---

## Steps to create a new WG repo

1. Click **"Use this template"** → **"Create a new repository"** on GitHub
2. Name the repository `wg-<name>` (e.g. `wg-safe`)
3. Set it to **Public**
4. Clone the new repo and do a find-and-replace:

   | Placeholder | Replace with |
   |---|---|
   | `[WG Name]` | Full name of the WG (e.g. `SAFE`) |
   | `WGNAME` | Short slug (e.g. `safe`) |
   | `[DATE]` | Charter adoption date |
   | `[Name]` / `@[handle]` | Chair and Co-Chair details |
   | `[TODO: ...]` | Your actual content |

5. Update `LICENSE` — delete the licenses that don't apply (see the Intellectual Property section in `README.md`)
6. Delete this file (`TEMPLATE-INSTRUCTIONS.md`) before your first commit
7. Open a PR in [`OpenSecureAIAlliance/governance`](https://github.com/OpenSecureAIAlliance/governance) to add the new WG to the README table

---

## Files in this template

| File | Purpose |
|---|---|
| `README.md` | Main landing page for the WG |
| `CHARTER.md` | Technical charter: mission, scope, governance |
| `CONTRIBUTING.md` | How to contribute |
| `CODE_OF_CONDUCT.md` | Points to the central OSAIA CoC |
| `MEMBERS.md` | Tracks leadership and contributors |
| `SECURITY.md` | Security vulnerability reporting policy |
| `LICENSE` | Apache 2.0 (update if needed) |
| `meetings/README.md` | Placeholder for meeting notes |
| `.github/PULL_REQUEST_TEMPLATE.md` | PR checklist |
| `.github/ISSUE_TEMPLATE/proposal.md` | Issue template for proposals |
| `.github/ISSUE_TEMPLATE/expression-of-interest.md` | Issue template for new contributors to signal interest |
| `.github/ISSUE_TEMPLATE/bug.md` | Issue template for bugs/errors |
