# Karanja Law & Co. Advocates — Production Website

Static website based on the established Were / Wakili wa Tech law-firm design pattern, with pages and assets customised for Karanja Law & Co. Advocates.

## Pages
Home, About Us, Practice Areas (9 categories), Our Advocate, Insights, Contact, Privacy, Terms, 404.

## Confirmed supplied information
- Name in uploaded logo: KARANJA LAW AND CO. ADVOCATES
- Marketing display name: Karanja Law & Co. Advocates
- Managing Partner: Faith Wambui Karanja (from supplied Lawzana screen and public company profile)
- Email: info@karanjalaw.co.ke
- Telephone/WhatsApp: +254 712 345 678 (as provided by user; please verify before live publication)
- Location: Westlands, Nairobi, Kenya (from supplied profile screenshot; no building or suite invented)

## Source notes
- Original firm logo: user-uploaded `karanja_law_advocates_logo.jpeg`
- Advocate portrait: user-uploaded `1778230898446.png`; appears once on homepage and once on advocate profile.
- Firm profile/practices: publicly published Karanja Law Advocates LinkedIn and user-supplied Lawzana screenshots.
- Pexels editorial images are remote (not bundled) and sourced distinctly per section. See `PHOTO-SOURCES.md`.

## Critical setup
- Site is static; no build commands, `vercel.json` included. Vercel Output Directory: `.` (repo root).
- Vercel deployment: run `npx vercel --prod` in this folder and select Create a new project.
- Use your GitHub CLI to create a new remote or push to your existing remote. See `DEPLOY.md`.
- The enquiry form opens a prefilled message in the visitor's configured email program; it does NOT store or transmit directly to a backend.
- Privacy/terms are site-information templates. Confirm final wording before live launch.
- Canonical URLs, OG URLs and sitemap currently point at `https://karanja-law-advocates.vercel.app`. Update all if your final Vercel domain differs.
- Google Search Console verification / indexing is a post-deployment manual step. SEO metadata alone does not guarantee rankings.
- 4K logo PNGs were processed from a 200x200 JPEG source; increased pixel dimensions cannot recover missing fine details. Original artwork should be supplied if pixel-perfect print quality is needed.
- The site's stock images are generic illustrations, **not** images of the firm's staff.
