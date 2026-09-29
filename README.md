# GAMEverse SMP – Website

Quellcode für gameversesmp.net, deployed über Cloudflare Workers (Static Assets) mit automatischem Git-Deploy.

- `public/` – alle Website-Dateien (HTML, robots.txt, sitemap.xml)
- `wrangler.jsonc` – Cloudflare Workers Konfiguration

Jeder Push auf `main` löst automatisch ein neues Deployment aus.
