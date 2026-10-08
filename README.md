# Kevin Githinji Portfolio

Static portfolio for full-stack development roles, freelance projects, and IT support opportunities. Open `index.html`, or serve this directory with `python -m http.server 8000`.

## Updating content

The page, styles, and interactions are in `index.html`. Project images and the downloadable CV are under `assets/projects/`.

Keep project descriptions short: general purpose, personal contribution, technology stack, and verified status. Company projects must not expose internal business logic, operational rules, source code, private URLs, customer data, or internal screenshots. Never copy environment files or credentials into this repository.

The October 2026 refresh checked local project READMEs, source structure, and package manifests. Local code demonstrates project existence and technology choices; it does not prove live deployment or independently verify every personal contribution. Worktree folders are not separate projects.

Before publishing, confirm education and certification status, employment title/dates, existing achievement figures, public project links, and the downloadable CV. The CV PDF was retained without changes; its current accuracy has not been verified.

Check desktop/mobile layouts, both themes, navigation, project filters, reduced-motion behavior, and CV download after editing.

## Project screenshots

The new portfolio images are actual captures of the local application frontends. Darasa, School Management, and Accommodation use fictional browser-only API responses; no database was seeded or changed. Learning Studio and the websites show their public pages. Attendance, Asset Tracker, and Policy Management show sign-in screens; the policy demo credential hint is hidden. Feedback shows its public entry page with a sample event.

The intranet prototype remains text-only because it has no public sign-in screen and its dashboard exposes internal application structure. No generated concept images are included in the portfolio.

Click a screenshot to open its full-size image. Screenshot assets are stored under `assets/projects/` with `-real` or `-sample` filenames.

## Layout and project coverage

Projects are grouped into featured platforms, business/operational platforms, and websites. Each card includes its status, department focus, three broad module highlights, and stack. Department focus describes relevant use cases, rather than an exact company department structure. Company module labels must remain broad and must not explain internal rules or workflows. The intranet is explicitly a frontend prototype.

The page order is projects, services, skills, experience, About, education, and contact. Filters cover all projects, platforms, websites, and company work; empty groups disappear when filtered.

## Hosting

GitHub Pages publishes this repository. The intended custom hostname is https://portfolio.kevorahub.com/. The root CNAME, canonical metadata, robots.txt, and sitemap.xml use that hostname. In Cloudflare, create a DNS-only CNAME named portfolio targeting kevin-githinji.github.io. Configure the same hostname in GitHub Pages and enable HTTPS once its certificate is ready. Changes in a pull request become public after merging to the publishing branch.

The portrait in assets/profile/kevin-githinji.jpg was supplied by Kevin for this portfolio.
