# Joseph Yohannes — Data Analytics Portfolio

A simple, responsive two-page portfolio website built with plain HTML and CSS. No account, paid hosting, build tools, plugin, template engine or other framework is required.

## What is included

- `index.html`: homepage, project feature and About section.
- `projects/crm-sales-pipeline/index.html`: full CRM Sales Pipeline case study.
- `assets/styles.css`: one shared stylesheet for both pages.
- `assets/images/`: 10 screenshots extracted from your own uploaded Power BI project notes, including data model, sales performance, product comparisons and a sector scatter chart.
- `assets/CRM_Sales_Pipeline_Project_Notes.pdf`: the full written project notes, linked from the case study.
- `.nojekyll`: helps GitHub Pages serve a plain HTML/CSS site as-is.

## Check locally

Open `index.html` in Chrome, Edge or Firefox. Follow “Explore my first project” to view the case study. In most browsers, all the pages and images work directly from the downloaded folder.

## Publish on GitHub Pages

1. Create or sign in to a GitHub account at https://github.com/.
2. Create a new **public** repository named exactly `<your-github-username>.github.io` (replace the placeholder with your actual username; lowercase in the repository name).
3. Extract this ZIP. Upload **all of the contents** (not the ZIP itself) to the root of that repository, preserving `assets/` and `projects/` folders. Include the `index.html` file in the root. Use **Add file → Upload files**, drag the extracted items in, and **Commit changes**.
4. Open the repository → **Settings → Pages**. Under Build and deployment, set **Source = Deploy from a branch**, select **main** and **/(root)**, then Save.
5. Your site will appear at `https://<your-github-username>.github.io/`. It may take a few minutes after the first commit.

GitHub's up-to-date instructions: https://docs.github.com/en/pages/quickstart

## Before making the site public

- **Add your actual LinkedIn profile or a professional contact email.** I deliberately did not invent a contact address or link; once provided, we can add a polished contact block and working header/footer link.
- Check that the background statements (including 5+ years of professional experience and the data analytics skills listed) are how you want to present yourself.
- Review the four charts and case-study text. They are based on your uploaded CRM Sales Pipeline notes.
- Optionally update screenshots with larger direct-from-Power-BI exports for sharpness on large screens.
- Optionally buy/connect a custom domain later without changing site content.

## How to add more projects later

For now, no complicated project templating: create another project page in `projects/`, add a card/link to your homepage, and upload the changed files to GitHub. We can add a reusable template later if you need it.

## Website technology

Static HTML and CSS only. All content and data stay in your own repository. No analytics/tracking, cookies, or forms have been added.
