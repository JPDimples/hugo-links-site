# Hugo's Links

Hugo's home on the internet — a single-page links site hosted free on
Cloudflare Pages at https://hugo-links.pages.dev

- Watch: YouTube @MrJparnham and the Men's Health in 30 Seconds playlist
- Shop: CoffinCutieCo on Gumroad, Benable picks
- Stremio addons: Hugo's Take only (the two family addons are private and stay off the public site)
- Follow: Instagram, Threads, Pinterest

## Deploy

```text
python3 ~/workspace/custom-connectors/custom.cloudflare/bin/cloudflare.py pages-deploy --dir . --project hugo-links
```

The Cloudflare API token lives in the Secure Vault (connector
`custom.cloudflare`); the helper deploys with it, so no token is pasted.
