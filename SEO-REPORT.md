# GMI Tech SEO Report

## Scope and initial baseline audit

The project contains these eight HTML pages: `index.html`, `services.html`, `portfolio.html`, `contact.html`, `career.html`, `privacy.html`, `tandc.html`, and `cp.html`. The homepage is now `index.html`; the suggested `projects.html`, `about.html`, `careers.html`, `terms.html`, and `software-company-ballari.html` routes are not present, so no duplicate pages were created.

| Page | H1s | Images missing `alt` | Audit notes |
|---|---:|---:|---|
| `index.html` | 1 | 0 | Title was generic; description and canonical were missing. |
| `services.html` | 1 | 0 | Description and canonical were missing. A template link targeted absent `service.html`. |
| `portfolio.html` | 1 | 0 | Description existed; canonical was missing. |
| `contact.html` | 1 | 0 | Description existed; canonical was missing. |
| `career.html` | 1 | 0 | Description existed; canonical was missing. |
| `privacy.html` | 1 | 0 | Description and canonical were missing. |
| `tandc.html` | 1 | 0 | Description and canonical were missing. |
| `cp.html` | 1 | 0 | Description and canonical were missing. |

All pages have a single H1. Template heading levels are not consistently sequential in some page sections; those headings were left unchanged because changing their elements could affect visible styling. No images were missing `alt` text. Existing internal links to nonexistent `service.html`, `privacy-policy.html`, `terms-conditions.html`, and `cookie-policy.html` were corrected to routes that exist in this project.

## Current titles and descriptions

| Page | Title | Meta description |
|---|---|---|
| Home | GMI Tech \| Software Company & AI Developer in Ballari | GMI Tech is a software company in Ballari building custom software, mobile apps, websites, and practical AI systems for local businesses across Karnataka. |
| Services | Software Development Services in Ballari \| GMI Tech | GMI Tech provides software development in Ballari, including websites, mobile apps, custom software, ERP, AI integration, cloud, DevOps and automation. |
| Projects | Software Projects & Case Studies in Ballari \| GMI Tech | Explore GMI Tech projects in Ballari: HRMS portals, college management and live result systems, plus AI chatbots, business software and mobile apps. |
| Contact | Contact GMI Tech \| Start Your Software Project in Ballari | Contact GMI Tech in Ballari to discuss a website, mobile app, custom software or AI project. Call, WhatsApp or send our team a message about your requirements. |
| Careers | Careers at GMI Tech \| Software Jobs in Ballari, India | Explore software and technology careers at GMI Tech in Ballari. Review current openings and apply to join a team building web, AI, and business software. |
| Privacy | Privacy Policy \| GMI Tech Software Company Ballari | Read GMI Tech's privacy policy to understand how information is collected, used, retained and protected when you visit our website or contact our Ballari team. |
| Terms | Terms & Conditions \| GMI Tech Software Company Ballari | Review GMI Tech's terms for its website and software services, including client responsibilities, payments, intellectual property, and liability in India. |
| Cookies | Cookie Policy for GMI Tech Software Company in Ballari | Learn how GMI Tech uses cookies on its website, which cookie types support site functionality, and how you can manage your browser cookie preferences. |

## Implemented

- Follow-up Ballari local SEO updates are documented in [SEO-KEYWORDS-REPORT.md](./SEO-KEYWORDS-REPORT.md): mapped keyword tags, geo and hreflang metadata, richer service/local business schema, social image tags, and navigation/footer link titles.
- The earlier `img/faces/image.png` reference did not exist in the workspace. Open Graph, Twitter, and organization image references now use generated favicon artwork derived from the existing G-mark asset.
- The existing sitemap already lists all eight real pages with `lastmod` set to `2026-10-21`; `robots.txt` already allows crawling and references the sitemap.
- Added `en-IN`, robots, keywords, author, geo, theme-color, canonical, Open Graph, and Twitter metadata to every actual HTML page.
- Added `Organization`/`ProfessionalService`/`LocalBusiness`, `WebSite`, and `WebPage` JSON-LD to the homepage.
- Added service catalog structured data, project `ItemList`, contact page/contact points, and page-specific `BreadcrumbList` structured data.
- Added `robots.txt` and `sitemap.xml` for the eight existing public pages.
- No review or aggregate-rating markup was added.
- No external domains are used for fonts, scripts, or stylesheets in the page heads, so no preconnect hints were added.

## Outstanding issues and decisions

- Favicon variants, an Apple touch icon, and a web manifest now exist at the site root. Google may continue to show a cached favicon until it recrawls the site.
- The missing homepage image now points to `img/photo/2.jpg`; the unavailable RAG portfolio card has been removed; and unused Fancybox stylesheet and script references have been removed.
- Internal home links point to `index.html`; canonical, Open Graph, structured-data, and sitemap URLs use `https://gmitech.in/`. No GitHub Pages branch/folder configuration or `CNAME` file is present in this workspace, so live publishing and DNS cannot be confirmed here. True host redirects require hosting/DNS configuration.
- The actual page filenames differ from several requested in the brief. No duplicate “About” or Ballari landing page was created because no matching content/page exists locally.
- The verified primary contact number is now consistent across visible phone/WhatsApp links and the homepage organization schema; secondary support details remain as previously listed.
- No local Git repository is available in this workspace, so a Git diff/stat could not be produced. The later website remediation changed HTML, CSS, JavaScript, metadata, and favicon assets.
- Search rankings, rich results, and Google sitelinks cannot be guaranteed by metadata or schema and need post-deployment verification.

## Post-deploy checklist

1. Verify `https://gmitech.in` as a Domain property in Google Search Console.
2. Submit `https://gmitech.in/sitemap.xml`.
3. Use URL Inspection to request indexing for the homepage and each main page.
4. Validate structured data with Google's Rich Results Test and Schema Markup Validator.
5. Create/verify a Google Business Profile for GMI Tech, Ballari, using accurate, consistent business details.
6. Add accurate business citations on relevant platforms and keep business name, address, and phone consistent.
7. Check indexing and search results again in one to four weeks.
