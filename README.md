# Uwanggood GitHub Pages Sites

This repository is the public GitHub Pages hub for Uwanggood project sites.

Main hub:

```text
https://uwanggood.github.io/
```

## Sites

| Project | Public URL | Custom domain | Source folder | Notes |
| --- | --- | --- | --- | --- |
| Path Doctor | https://uwanggood.github.io/path-doctor/ | Not connected | `path-doctor/` | Windows network diagnostic tool SEO site |
| Bucket Studio | https://uwanggood.github.io/bucket-studio-downloads/ | Not connected | project Pages repo | S3-compatible storage browser public release site |

## Privacy Policies

Shared policy directory:

```text
https://uwanggood.github.io/privacy/
```

Current Microsoft Store privacy policy URL for local-first desktop apps:

```text
https://uwanggood.github.io/privacy/local-first/
```

This policy currently applies to Bucket Studio and Path Doctor. Future apps that add accounts, hosted cloud storage, advertising analytics, or server-side user profiles should get a separate policy category URL.

Machine-readable registry:

```text
https://uwanggood.github.io/sites.json
```

Human-readable registry:

```text
https://uwanggood.github.io/sites.html
```

## Naming rule for new sites

Use one clear slug per project:

```text
https://uwanggood.github.io/<project-slug>/
```

Examples:

```text
https://uwanggood.github.io/path-doctor/
https://uwanggood.github.io/another-tool/
https://uwanggood.github.io/example-game/
```

Keep slugs lowercase and use hyphens instead of spaces.

## When adding a site

Update these files together:

- `index.html`
- `sites.html`
- `sites.json`
- `sitemap.xml`
- this `README.md`

If a custom domain is connected later, record it in `sites.json` and in the table above.

## Current Path Doctor pages

- `path-doctor/index.html`
- `path-doctor/ping-normal-site-slow.html`
- `path-doctor/tracert-star-star-star.html`
- `path-doctor/vpn-site-slow.html`
- `path-doctor/dns-normal-site-not-opening.html`

Old root-level guide URLs are kept as redirects to the new `/path-doctor/` URLs.
