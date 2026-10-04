# ldev-project.github.io

The public website for LDev apps, served by GitHub Pages from the `main` branch.

| File | URL | Used by |
|---|---|---|
| `mati-hachofesh/privacy-policy.html` | https://ldev-project.github.io/mati-hachofesh/privacy-policy.html | Google Play listing |
| `mati-hachofesh/breaks.json` | https://ldev-project.github.io/mati-hachofesh/breaks.json | the app downloads it on launch (`BREAKS_URL`) |

## Changing break dates without an app update

1. Edit `mati-hachofesh/breaks.json`.
2. **Increase `version`.** The app ignores the file unless `version` is higher than the one it already has.
3. Commit and push. The change is live within a few minutes.

Copy the same change into `assets/breaks.json` in the app repo, so new installs and offline users get it too.
