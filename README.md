# John Reynolds — Author Website Concept

A responsive, static author-website concept prepared by Astra Productions for Dr John Reynolds, to demonstrate improvements to his online book presentation.

**Status:** Unapproved draft for review. The site is not the author's official website. This repository and the eventual `pages.dev` preview may be publicly accessible; do not represent this draft as launched or author-approved.

## Preview locally

Open `public/index.html` in a browser. No install or build step is needed. Google Fonts require a network connection, but fallback fonts are included.

## Deploy to Cloudflare Pages (Git integration)

1. In the Cloudflare dashboard, choose **Workers & Pages → Create application → Pages → Import an existing Git repository**.
2. Connect GitHub and select `WindzJC/John-Reynolds-Draft`.
3. Set **Production branch** to `main`.
4. Set **Framework preset** to `None` (or no framework).
5. Set **Build command** to `exit 0`.
6. Set **Build output directory** to `public`.
7. Save and deploy. Cloudflare will show a `*.pages.dev` preview address.

Cloudflare Pages will then redeploy updates pushed to `main`. The page includes `noindex` metadata and a `_headers` rule to discourage search engine indexing, but **these do not make the site private**.

## Site contents

- `public/index.html`: author homepage and content
- `public/styles.css`: responsive styles
- `public/script.js`: mobile navigation
- `public/assets/`: cover artwork and author portrait
- `public/_headers`: crawler-indexing discouragement for the public preview

The design provides a featured memoir, credited NZ Booklovers review, additional book titles, biographical introduction, Amazon button, signed-copy enquiry and social links.

## Important fact checks and approvals before any official launch

1. **Subtitle conflict**: John's official site calls *In With Both Feet* `A Passport Full of Memories`; current cover art and NZ Booklovers call it `A Passport Full of Stories`. The landing page refers to the book by its main title. Confirm the final subtitle and cover with John.
2. **Purchase link**: verify the Amazon AU listing (`B0GDS2ZLRC`) is the right edition and available in intended countries.
3. **Signed copies**: contact link uses the email John publishes on his existing author homepage; confirm he wants it shown on a redesigned site.
4. **Other books**: these point back to his existing Books page, not dedicated checkout pages. Replace with approved individual purchase links.
5. **Imagery and text**: obtain John's approval and the necessary rights for production use of photos, covers and quotation.
6. **Hosting and commercial terms**: agree on the fee, scope, domain, maintenance and publishing before substituting this for his existing site.

## Source references

- Official author website: https://drjohnreynolds.wixsite.com/dr-john-reynolds
- Book cover / portrait: https://indiebooks.co.nz/john-reynolds/
- Karen McMillan review: https://www.nzbooklovers.co.nz/post/in-with-both-feet-a-passport-full-of-stories-by-john-reynolds
- Author interview: https://www.nzbooklovers.co.nz/post/interview-john-reynolds-talks-about-in-with-both-feet

Designed for review by Astra Productions. Source imagery and quotations remain the property of their respective rights holders.
