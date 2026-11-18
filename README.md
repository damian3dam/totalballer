# Total Baller website (totalballer.com)

A single-file static site: `index.html` (no build step, no dependencies). Preview images: `preview-desktop.png`, `preview-mobile.png`.

## Content sources
Real details come from Stuart's Instagram (@totalballertraining), his Tenpo booking page (tenpo.com/o/the-total-baller) and his Linktree (totalballertraining): prices, coaches, reviews, Off SZN LA forms, the TB jersey link and socials.

## Still placeholder (search the file for `TODO`)
- The real TB logo file (currently a drawn "TB" circle)
- A photo of Stuart for the About section (`stuart.jpg`)
- Contact email (`CONTACT_EMAIL` in the script and the Contact section) - hello@totalballer.com is a guess

## Going live (free, about 15 minutes)
1. Create a free account on Netlify (or Cloudflare Pages / Vercel).
2. Drag the `totalballer-site` folder onto Netlify's "Deploy manually" area. You get a temporary `*.netlify.app` link.
3. In Netlify: Domain management → Add a domain → `totalballer.com`.
4. At the registrar where totalballer.com is held, either switch the nameservers to Netlify's, or add the DNS records Netlify shows (an A/ALIAS record for the root and a CNAME for `www`).
5. HTTPS is issued automatically once DNS resolves (minutes to a few hours).

## Forms
Both forms (enquiry and merch waitlist) are set up for Netlify Forms: once deployed on Netlify, submissions appear under Site → Forms, and you can turn on email notifications there. Hosted anywhere else, they fall back to opening the visitor's email app.

## Also included
`og.jpg` (link preview image), `robots.txt`, `sitemap.xml`.
