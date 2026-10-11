<p align="center">
  <img src=".github/assets/logo.png" alt="IPL English content logo" width="112" height="112">
</p>

<h1 align="center">Internet Public Library — English content</h1>

<p align="center">
  The English pages of the <a href="https://ipl.better-web.org/en-US/">Internet Public Library</a>:
  home, library sections and the institutional pages (about, help, contribute, policies…).
</p>

---

This repository is included in [IPLibrary-website](https://github.com/InternetPublicLibrary/IPLibrary-website) as the
`en-US/` git submodule. The site builds category, subcategory, section and wiki pages from the menu and data in
the website repository; the files here are the hand-written pages and topic introductions.

## What lives here

| Path | Content |
| --- | --- |
| `index.md` | English home (layout `language_index`) |
| `academics/`, `business/`, `computing/`, … | Topic pages and introductions for the eight categories |
| `about.html`, `help.html`, `contribute.html`, … | Institutional pages (layout `info`) |
| `submit-resource.html`, `report-issues.html`, `contact.html` | Forms that open prefilled GitHub issues |

## How to contribute

- **Fix or improve a page:** use the **Edit** tab on any page of the site — it opens the source file here — or open
  a pull request directly. A code owner reviews every change (`.github/CODEOWNERS`).
- **Suggest a resource:** [Suggest a resource](https://ipl.better-web.org/en-US/submit-resource/) on the site.
- **Report a problem:** [Report issues](https://ipl.better-web.org/en-US/report-issues/).
- Discussions about pages happen in this repository's GitHub Discussions.

Front matter conventions: `layout`, `title`, `lang: en-US`, `description` and `permalink` (keep URLs stable;
the Portuguese edition mirrors the same structure in [pt-BR](https://github.com/InternetPublicLibrary/pt-BR)).

## License

See [LICENSE](LICENSE).
