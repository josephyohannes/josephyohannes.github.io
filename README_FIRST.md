# Joseph Yohannes — Data Analytics Portfolio

The existing GitHub Pages site is a static HTML/CSS portfolio. There is no build step, JavaScript framework or tracking script.

## Files

- `index.html`: introduction, featured project, professional background and contact links.
- `projects/crm-sales-pipeline/index.html`: CRM case study, findings, methodology and supporting files.
- `assets/styles.css`: shared theme, responsive layouts and accessibility styles.
- `assets/CRM_Sales_Pipeline_Project_Notes.pdf`: the supplied final PDF, preserved without re-exporting it.
- `assets/images/crm-report-overview.png`: the supplied original Power BI screenshot, preserved unchanged for enlargement.
- `assets/images/crm-report-overview.webp`: a resized, losslessly encoded website preview derived from that screenshot.
- `assets/images/product-revenue.webp`: a crop of the corrected product chart from the same screenshot.
- `assets/images/portfolio-share.png` and `crm-sales-pipeline-share.png`: 1200 × 630 link-sharing images. The CRM image includes the actual supplied screenshot.
- Other images in `assets/images/`: supporting figures from the project notes.

## Preview and publish

Serve the repository root with a local static server, for example `python -m http.server 8000`, and open `http://localhost:8000/`.

The existing GitHub Pages workflow publishes the `main` branch. Check both pages, narrow-screen layouts, image links and the PDF before pushing changes. Confirm the Pages workflow succeeds and inspect the live pages afterwards.

`checks/responsive.html` is an unlinked, noindex development page for inspecting the actual pages in 390 px and 320 px iframe viewports. It has no extra dependencies and can also be used locally.

When replacing an existing asset, update its `v=` query value in the HTML so repeat visitors receive the new version. Keep the PDF's stable pathname.

## Add the CV when ready

The homepage contains `#cv-download` beside the main hero actions. It has no URL and is hidden. Once the approved CV is available:

1. Add the CV under `assets/` using a clear filename.
2. Add its relative URL as the anchor's `href`, add `download` if a download is preferred, and remove `hidden`.
3. Test the link and check the hero actions on mobile.

Do not expose the button before the real file is supplied.

## Add another project

Copy the current case study into a new `projects/<project-slug>/index.html`, retaining the shared header, footer and stylesheet. Use the same content pattern: business question, approach, evidence, findings, recommendations, limitations and supporting files. Replace every project-specific figure, caption, metric, source link, title, description, canonical URL and sharing image.

Add another `article.project-feature` inside the homepage Projects section. Use a short business question, the tools actually used, a useful preview image and a clear case-study link. Add cards only when their projects are ready.

## Content and asset checks

- Describe professional experience separately from independently developed skills.
- Use British English and support claims with the project evidence.
- Preserve original report images for enlargement; optimise only derived previews.
- Keep PDF contents unchanged when publishing an approved attachment.
- Check internal links, keyboard navigation, mobile overflow and text contrast.
- Keep the existing email and LinkedIn links; testing them does not require sending messages.
- Social previews may remain cached by individual platforms after an update.

## Approved source fingerprints

- Project notes PDF SHA-256: `296b48b8bdfae3dc0474f54466d657522ae51d04e419f941843d92839c0e402d`
- Original report screenshot SHA-256: `49398ec99f79ca0a5d33796698fe65dde963c456f0f1f3fcca38613506af8cf8`
