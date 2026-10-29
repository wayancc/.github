<div align="center">

# WAYAN.CC.

**Open-source tools for people who ship websites.**
Self-hosted. Runs on cheap PHP hosting. Zero external requests.

[wayan.cc](https://wayan.cc) · [Start a project](https://wayan.cc)

</div>

---

## THE TOOLS.

| Project | What it does | License |
|---|---|---|
| **[Inkdocs](https://github.com/wayancc/inkdocs)** | Flat-file docs engine. Write Markdown, ship docs: cached static HTML on shared hosting, or a full static export for GitHub Pages. Versioning, search, Mermaid and `llms.txt` built in. | MIT |
| **[Vigil](https://github.com/wayancc/vigil)** | Uptime monitor and public status page. HTTP, keyword, TCP, heartbeat and SSL checks, with alerts to email, Telegram, Slack, Discord, ntfy and signed webhooks. | AGPL-3.0 |
| **[Wyn Forms](https://github.com/wayancc/wyn-forms)** | Form backend for static sites. Point any HTML form at `/f/{key}` and get spam filtering, an inbox, file uploads and notifications. | AGPL-3.0 (embed script MIT) |

First public releases: **v0.1.0**.

## BETTER TOGETHER.

Build your docs or static site with **Inkdocs** → collect contact and feedback forms with **Wyn Forms** → watch both with **Vigil** and give users a public status page.

## HOW WE BUILD.

- **Runs anywhere PHP runs.** PHP 8.2+, SQLite and vanilla JS. No build step and no Composer dependencies where avoidable. Upload, point the document root at `public/`, done. Docker works too.
- **Private by default.** Fonts are bundled, with no CDNs and no trackers. Every release is tested for zero external requests.
- **Designed, not defaulted.** One design system across every project: Inter, black on white, square corners, and status colors used only for status. Bold and Neutral themes, light and dark.
- **Accessible.** WCAG AA contrast in every theme and mode, full keyboard navigation, status shown by text as well as color, and respect for reduced motion.
- **Tested.** Dependency-free test suites run in CI on every push.

## LICENSES.

Developer tools are **MIT**. Self-hosted server apps are **AGPL-3.0**: free to self-host and modify, and if you run a modified version as a network service, you share its source with your users. Scripts you embed on your own sites are **MIT**.

## CONTRIBUTING.

Issues, bug reports and ideas are welcome on each repo. Pull requests need a signed Contributor License Agreement; you'll be asked on your first PR.

---

<div align="center">

Designed and built by **Wayan Suantika**, website designer in Denpasar, Bali.
[wayan.cc](https://wayan.cc)

</div>
