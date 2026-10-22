# isidd.dev — portfolio

One-page portfolio. Split layout, black on white, same fonts and eagle icon as isidd.com.

## Edit your content (no code needed)
Everything lives in the `_data` folder:

| File | What it holds |
|---|---|
| `_data/profile.yml` | Name, headline, About, email, social links |
| `_data/updates.yml` | Everything you are working on (Projects, Playbook, Architecture, Bitslyf, Blogs). Home shows the newest 3; `/updates/` is the full archive |
| `_data/projects.yml` | Selected projects: title, summary, result, tools, Live / How I built it / Code links |
| `_data/playbook.yml` | Best Engineering Playbook write-ups |
| `_data/architecture.yml` | Best Project Architecture write-ups (3 shown) |
| `_data/blogs.yml` | Latest 3 posts from isidd.com |
| `_data/bitslyf.yml` | Latest posts from bitslyf.com with their category (Analysis, Research, Prediction, Thesis); top 3 shown |

Edit a file on GitHub (pencil icon), commit, and the site rebuilds in about a minute.

## Deploy
1. Upload everything (including the hidden `.github` folder) to a GitHub repo.
2. Settings → Pages → Source: **GitHub Actions**.
3. Custom domain: `isidd.dev`. Verify the domain first in your account Settings → Pages.
4. DNS for isidd.dev: four A records `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.

Fonts: EB Garamond (SIL OFL, self-hosted), upright only, no italics. Icons: Font Awesome Free (CC BY 4.0).
