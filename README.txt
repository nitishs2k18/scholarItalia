SCHOLARITALIA - WEBSITE FILES
=============================
Plain HTML. No build step, no server code. Upload the whole folder to any web host.

FILES
  index.html         Home page (open this first)
  guides.html        Life in Italy guides
  universities.html  Full university directory (search and filters)
  privacy.html       Privacy notice
  favicon.png        Browser tab icon

HOW TO PUT IT ONLINE (easiest first)
  1. Netlify or Cloudflare Pages: drag and drop this folder, then add your domain in the dashboard.
  2. Any hosting (cPanel, Hostinger, GoDaddy): upload all files into public_html. Keep index.html in the top folder.
  3. Turn on HTTPS (free on all of the above).
  Test locally first: double-click index.html.

BEFORE YOU LAUNCH - REPLACE THESE PLACEHOLDERS (use Find and Replace in a text editor, all 4 files)
  hello@example.com         your real email
  910000000000              your WhatsApp number, digits only with country code (wa.me link)
  +91 00000 00000           WhatsApp number shown in the footer
  [your full name or business name], [city], [12]   in privacy.html
  "Replies within 24 hours (edit)" in the footer: keep or delete

THINGS TO KNOW
  - Enquiry form: it opens the visitor's email app with the answers filled in. It does NOT save or send data by itself.
    For a real form, create a free Formspree or Web3Forms form and post the answers to it (ask a developer to change the submit step in index.html, search for "mailto:").
  - Chat assistant: it works with built-in scripted answers. The AI-written replies only work inside Claude, so on your own domain it uses the scripted ones.
  - Logos: the university logos came from your spreadsheet. They are trademarks, so check you may display them.
  - Privacy notice: have a lawyer check it. Add a cookie banner only if you add analytics or ads later.
  - Page speed: index.html and universities.html are about 650-700 KB because the logos are embedded. This is fine, but compress further if needed.

HOW TO UPDATE CONTENT (no coding)
  Search each page for these blocks and edit the text inside. Keep the quote marks and commas.
    id="news-data"      scholarship news items (needs region, date, headline, link)
    id="deadline-data"  deadline popup (university, programme, deadline YYYY-MM-DD, official link)
    id="map-data"       map and winners table
    id="growth-data"    student growth graph
    id="featured-data"  five featured universities and rankings
  Items missing a source link or date are skipped automatically.
  Check every number against its official source before you publish a change.
