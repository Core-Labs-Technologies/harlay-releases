# Harlay releases

Downloads of the Harlay macOS app. The source is private; this repo only hosts the built app for each version.

Install or update:

```sh
curl -fsSL https://harlay.si/install.sh | sh
```

Each release has `Harlay-arm64.zip` (Apple silicon), `Harlay-x64.zip` (Intel) and `SHA256SUMS`. The installer checks the
download against `SHA256SUMS`, puts Harlay in /Applications and opens it.

The optional `harlay` CLI is on npm: `npm i -g harlay`.
