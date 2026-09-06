# App legal & support pages

Static pages served by GitHub Pages for the iOS apps I publish.

```
index.html          landing page listing the apps
apprep/             A&P Mechanic Exam Prep
  privacy.html
  support.html
```

## Adding an app

Make a folder named after the app, drop `privacy.html` and `support.html` in it,
add a section to `index.html`, commit and push. Pages redeploys in about a minute.

## URLs

`https://<username>.github.io/<repo>/apprep/privacy.html`

Those URLs go in App Store Connect: privacy in App Information, support on the
version page. Check both in a private browser window before submitting — an
unreachable URL is the most common metadata rejection.
