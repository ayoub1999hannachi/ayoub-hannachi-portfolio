# Ayoub Hannachi — Portfolio

A static, multilingual portfolio site. It is ready to deploy to Vercel without a build step.

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, import that repository.
3. Select **Other** as the framework preset. Leave the build command, output directory, and install command empty, then deploy.

The site entry point is `index.html`; `images/` contains the website's image assets, and `documents/CV_Ayoub_Hannachi.pdf` is the downloadable CV.

## Updating the site

After the first deployment, keep the GitHub repository connected to the Vercel project. Commit and push each update to the configured production branch; Vercel will build and publish it automatically. Pushes to other branches create preview deployments.

## Deployment notes

- The canonical URL, social preview metadata, sitemap, and `robots.txt` use `https://ayoub-hannachi-portfolio.vercel.app/`.
- If you later add a custom domain, update those URLs and the EmailJS allowed origin to match it.
