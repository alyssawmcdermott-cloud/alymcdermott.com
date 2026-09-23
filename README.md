# Alyssa McDermott — Reno Buyer's Agent website

Plain HTML/CSS. No build step. Works on GitHub Pages as-is.

## Put it online (GitHub Pages)
1. Create a new public repository on GitHub (e.g. `alyssa-website`).
2. Upload every file and the `images` folder (Add file → Upload files). Keep the folder structure.
3. Settings → Pages → Source: "Deploy from a branch" → branch `main`, folder `/ (root)` → Save.
4. Your site appears at `https://YOUR-USERNAME.github.io/alyssa-website/` within a few minutes.

## Use your own domain (recommended for search)
1. Settings → Pages → Custom domain → enter your domain → Save (this creates a CNAME file).
2. At your domain registrar, point DNS to GitHub Pages (GitHub shows the exact records).
3. Tick "Enforce HTTPS" once it's available.
4. Domain already set to alymcdermott.com in all files.

## Contact form
GitHub Pages can't process forms. Sign up free at formspree.io, create a form,
and replace `YOUR_FORM_ID` in index.html. Submissions go to your email.

## Fill in the placeholders
Everything highlighted in yellow on the page is a placeholder. Search the files for `[` to find them:
phone, email, CA DRE #, brokerage name/address/phone (required in Nevada advertising),
your story, deal numbers and photos. When a placeholder is filled in,
remove the `class="ph"` wrapper so the yellow highlight goes away.
Also fill in the schema block at the top of index.html (phone, email, address)
and add your profile URLs to "sameAs" (Zillow, Realtor.com, LinkedIn, brokerage page, Google Business Profile).

## After launch
- Add the site to Google Search Console and Bing Webmaster Tools; submit sitemap.xml.
- For each new case study, copy deal-case-study.html to a new file name, fill it in,
  link it from the "Deals I've found" section, and add it to sitemap.xml.
