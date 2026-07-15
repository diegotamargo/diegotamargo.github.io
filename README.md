# diegotamargo.github.io

My personal portfolio. It's a single HTML page, so there's nothing to build or compile.

## Putting it online with GitHub Pages

The repo has to be named `diegotamargo.github.io` exactly, or Pages won't serve it at the root of the domain.

1. Create the repo with that name and make it public.
2. Put `index.html` and `CV_Diego_Tamargo.pdf` in the root, on the `main` branch.
3. Under **Settings > Pages**, set the source to `main` / `root`.
4. Give it a couple of minutes and it'll be live at `https://diegotamargo.github.io`.

If you'd rather push from your machine:

```bash
git init
git add index.html README.md CV_Diego_Tamargo.pdf
git commit -m "Publica sitio de portfolio con CV descargable"
git branch -M main
git remote add origin https://github.com/diegotamargo/diegotamargo.github.io.git
git push -u origin main
```

## A few things to remember

The "Download CV" button points to `CV_Diego_Tamargo.pdf` in the root, so that file needs to sit next to `index.html`. To swap in a new CV later, drop in the replacement under the same name and push again. Once the site is up, add its URL to the Featured section of your LinkedIn profile.
