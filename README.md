# AEDT Ultimate Website Build

Production-ready static website package for **tetheraedt.io**.

## Included
- Premium responsive homepage with animated AEDT visual
- Live market dashboard: DexScreener first, GeckoTerminal fallback
- 72-hour GeckoTerminal OHLCV chart (when public API/CORS is available)
- Live TRON latest-block query through public TronGrid endpoint
- Token identity, transparency, ecosystem, individual, business, exchange, security, FAQ, contact, legal and web-whitepaper pages
- MetaOneClick integration roadmap + verified `contact@metaoneclick.com` handoff
- AEDT public X and Telegram links
- SEO metadata, OpenGraph card, sitemap, robots, PWA manifest, offline service worker
- GitHub Pages `CNAME` and `.nojekyll`
- Netlify-style `_headers` security template (ignored by GitHub Pages)

## Deploy to GitHub Pages
1. Back up the current repository.
2. Copy **the contents of this folder** into the repository root.
3. Commit and push to the branch used by GitHub Pages.
4. In GitHub → Settings → Pages, confirm deployment source.
5. Confirm custom domain `tetheraedt.io` and HTTPS enforcement.

## Important live-data behavior
The site performs **browser-side, read-only public API calls**. No API key is bundled. Public API providers may rate-limit, change response formats or block CORS in the future. The interface intentionally degrades to `—` and keeps independent source links available.

Current API routes are centralized in `assets/config.js` so they can be changed without editing every page.

## Project constants
- Contract: `TV714TT9aQftbkYBjWiVExCxNZm9nPJX6K`
- Public reference wallet: `TDqSquXBgUCLYvYC4XZgrprLK589dkhSCf`
- Primary pool reference: `TAGdFL8kbuKEWhjYhHCwGxFGKsLs3MzFym`
- Network: TRON / TRC-20

## Before publishing
- Test every external link.
- Have qualified counsel review `legal.html`, `transparency.html`, and marketing statements for jurisdictions where the project is marketed.
- If you later establish audited reserve/redemption mechanics, update only after the supporting documentation is public and current.
- Never add wallet connect / signing functionality unless there is a specific audited product need.

## Contact architecture
No unverified AEDT email address was invented. Public project channels are linked, while technical/business integration enquiries are routed to MetaOneClick's verified public contact.
