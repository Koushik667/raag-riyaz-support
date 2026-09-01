# Raag Riyaz public site

Static, dependency-free product, support and privacy pages for Raag Riyaz.

- Product and support: `https://koushik667.github.io/raag-riyaz-support/`
- Privacy policy: `https://koushik667.github.io/raag-riyaz-support/privacy.html`
- App Store: `https://apps.apple.com/app/id6798105423`

The site intentionally contains no analytics, cookies, forms, SDKs, JavaScript bundles or remote fonts. Product imagery is limited to the reviewed, fictional-data screenshots in `assets/`.

## Local preview

Run a static web server from this directory and open the root page:

```sh
python3 -m http.server 8080
```

## Deployment

GitHub Pages publishes this repository using its existing repository configuration. Keep the privacy URL stable because it is referenced by the app and store listings.
