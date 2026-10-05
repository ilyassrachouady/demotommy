# Tommy Trépanier — website

The complete website is in `dist/`. It is a standalone static website: no build step or package installation is required.

Included:

- Homepage with property listings, interactive map, real-estate tools and contact forms.
- Four individual property pages in `dist/properties/`.
- All website styles, JavaScript, property photographs and brand assets.

## Deploy on Vercel

Import this repository with the project Root Directory set to the repository root. `vercel.json` configures Vercel to publish `dist/` with no build step.

## Preview locally

```sh
python3 -m http.server 4176 --directory dist
```

Then open http://localhost:4176/.
