# Apply the v0.3.0 homepage update

Copy the `src` folder from this package over the repository's existing `src` folder, allowing the three included files to be added or replaced.

Then run:

```bash
npm run build
git add -A
git commit -m "v0.3.0 - Improve homepage layout and reusable components"
git push origin develop
```

Files included:

- `src/components/Card.astro` (new)
- `src/components/QuickLinks.astro` (new)
- `src/pages/index.astro` (replace)
- `src/styles/site.css` (replace)
