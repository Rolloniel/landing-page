# Landing Page

Personal portfolio/landing page at kliuiev.com.

## Architecture

- **Framework:** Astro 5 with MDX support, Tailwind CSS
- **Build:** Static site → nginx container
- **Source directory:** `site/` (Dockerfile, package.json, and all source are inside `site/`)

## Deployment (Coolify)

| Component | UUID | Domain |
|-----------|------|--------|
| Site | `dwg08g8ws0g0ssk08o4skwow` | `www.kliuiev.com`, `kliuiev.com` |

- Coolify base directory: `/site`
- Direction: Redirect to www (bare domain → www.kliuiev.com)
- No health endpoint (static nginx)

## Environment Variables

None required.

## Local Development

```bash
cd site && npm install && npm run dev
```
