# Delivery Toolkit

Three lightweight, single-file web tools for project delivery and business analysis.

| Tool | What it does |
|---|---|
| [Delivery Desk](delivery-desk.html) | Portfolio dashboard: explained RAG health, RAID logs, intake scoring, one-click weekly report |
| [Project Desk](project-desk.html) | One project in depth: plan and timeline, RAID, budget, change requests, stakeholders, benefits, improvement, automation rules |
| [BA Desk](ba-desk.html) | Requirements, user stories, process gaps, test cases, traceability matrix and specification export |

## How data is stored

Each tool opens with fictional sample data. Changes are saved in the visitor's own browser (localStorage) and never leave their computer. Use **Back up** to download a JSON copy and **Restore** to load it on another computer or browser.

## Publish with GitHub Pages

1. Create a public repository and upload these files to the root (keep `.nojekyll`).
2. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
3. After a minute or two the site is live at `https://<your-username>.github.io/<repo-name>/`.

No build step, server or database is needed. Each `.html` file is self-contained apart from Google Fonts.
