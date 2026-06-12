# FRC 6045 Team Website

Sabre Robotics website, built with Jekyll on GitHub Pages and edited through [Pages CMS](https://app.pagescms.org).

## ✏️ Editing the site (no code needed)

1. Go to **app.pagescms.org** → sign in with GitHub
2. Open **frc-6045 / Team-Website**
3. Use the sidebar: **How-To Guides · Autos · Documented Problems · App Downloads · Repos · Site Settings**
4. Make your change → **Save** → live in ~1 minute

To add a screenshot, just drag it into the editor — it uploads to `assets/images/` automatically.

## 🔧 One-time setup (already done if the site is live)

1. Upload these files to the repo root
2. Repo **Settings → Pages → Source: Deploy from a branch → main / (root)**
3. Site appears at `https://frc-6045.github.io/Team-Website/`

## 🏗️ How it's structured

| Path | What it is |
|---|---|
| `.pages.yml` | Defines the CMS editing forms |
| `_config.yml` | Jekyll site settings |
| `_layouts/` | Page design (header/nav/footer wrap every page) |
| `_guides/`, `_autos/`, `_problems/` | One Markdown file per page/entry |
| `_data/` | Homepage cards, repos, settings — edited as forms in the CMS |
| `assets/` | Stylesheet, logo, screenshots |

## 🚀 Expanding to the full team site

Add a new collection (e.g. News, Robots, Sponsors): create a folder like `_news/`, add a matching entry in `.pages.yml` and `_config.yml`, and loop it somewhere in a layout. The CMS sidebar picks it up automatically.

Maintained by the 6045 programming subteam · sabrerobotics6045@gmail.com
