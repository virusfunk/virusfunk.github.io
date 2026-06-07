# virusfunk.github.io

Personal portfolio site for [virusfunk](https://github.com/virusfunk).
Built with Jekyll and deployed via GitHub Pages → **https://virusfunk.github.io**

## Editing the content

You can change most things by editing just the files below — no coding required.

| What to change | File |
| --- | --- |
| Name, intro, contact, social links | `_config.yml` |
| Hero text / About / section copy | `index.html` |
| Skill stack | `_data/skills.yml` |
| Project cards | `_data/projects.yml` |
| Colors, fonts, design | `assets/css/style.css` |

## Local preview (pixi)

[pixi](https://pixi.sh) manages the Ruby environment automatically.

```bash
pixi run install   # first time only — installs gems
pixi run serve     # preview at http://localhost:4000 (auto-reloads on save)
```

Other commands:

```bash
pixi run build     # static build into _site/
pixi run clean     # clear build caches
```

## Deployment

Pushing to the `main` branch triggers an automatic build and deploy by GitHub Pages.
No extra setup is needed. (Settings → Pages → Source: `Deploy from a branch`, `main` / `root`)
