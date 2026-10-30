# dtwinuz/.github

`dtwinuz` org'ining umumiy fayllari. Ular o'z faylini qo'ymagan barcha repolarga avtomatik qo'llanadi.

| Fayl | Vazifa |
|---|---|
| `profile/README.md` | Org sahifasidagi ochiq profil |
| `CONTRIBUTING.md` | Hissa qo'shish qoidalari |
| `SECURITY.md` | Zaiflik haqida xabar berish |
| `CODE_OF_CONDUCT.md` | Xulq-atvor qoidalari |
| `SUPPORT.md` | Yordam kanallari |
| `.github/ISSUE_TEMPLATE/` | Bug va feature shablonlari |
| `.github/pull_request_template.md` | PR shabloni |
| `workflow-templates/` | Org workflow template'lari: **Actions → New workflow** ostida chiqadi |

## ⚙️ Workflow template'lar

| Template | Vazifa |
|---|---|
| dtwin CI (.NET) | build (`-warnaserror`), test, zaif NuGet paketlar |
| dtwin CI (web, pnpm) | `pnpm install`, audit, lint, Vite build |
| dtwin Release → GHCR | `v*` tegida image → `ghcr.io/dtwinuz/<repo>/<nom>` + GitHub Release |

Yangi mahsulot uchun to'liq tayyor repo: [`dtwinuz/dtwin-app-template`](https://github.com/dtwinuz/dtwin-app-template) → **Use this template**.
