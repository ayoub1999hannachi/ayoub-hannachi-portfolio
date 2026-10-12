# Ayoub Hannachi — Portfolio

A static, multilingual portfolio site. It is ready to deploy to Vercel without a build step.

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, import that repository.
3. Select **Other** as the framework preset. Leave the build command, output directory, and install command empty, then deploy.

The site entry point is `index.html`; `images/` contains the website's image assets, and `documents/CV_Ayoub_Hannachi.pdf` is the downloadable CV.

## Updating the site

After the first deployment, keep the GitHub repository connected to the Vercel project. Commit and push each update to the configured production branch; Vercel will build and publish it automatically. Pushes to other branches create preview deployments.

## Before going live

- The canonical URL, social preview metadata, and sitemap currently use `https://ayoubhannachi.com/`. Update them if deploying to a different domain.
- Once Vercel assigns the final site URL, confirm the canonical URL, social metadata, sitemap, and EmailJS allowed origin match that domain.
