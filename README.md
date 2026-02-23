# hugo-nanx2026

[nanx2026](https://github.com/nanxstats/hugo-nanx2026) is a opinionated Hugo theme built on Tailwind CSS. It is loosely based on [hugo-nanx2023](https://github.com/nanxstats/hugo-nanx2023) and used for [my personal website](https://nanx.me).

## Build Tailwind CSS

The theme uses [Tailwind CSS](https://tailwindcss.com/) with a local build
via the Tailwind CLI. Install dependencies and build the CSS from the
theme directory:

```bash
cd themes/hugo-nanx2026
npm install
npm run build
```

During development, use watch mode to rebuild CSS automatically
when templates or the Tailwind config change:

```bash
cd themes/hugo-nanx2026
npm run dev
```

## Font policy

This theme does **not** include any proprietary font files.
It may reference font family names or example URLs for illustration only.
You must replace them with your own licensed/self-hosted fonts or use a
system font stack. You are responsible for licensing compliance,
and proprietary font binaries should not be committed to public repos.

## License

This theme is released under the MIT license.
