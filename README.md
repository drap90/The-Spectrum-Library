# AP Learning Lab website

A simple website for AP Learning Lab LLC, ready to publish for free on GitHub Pages.

```
index.html                         Home page with the full series
about.html                         Your story and contact info
404.html                           Shown when a page isn't found
guides/getting-to-a-diagnosis.html Product page for Stage 1
guides/getting-to-yes.html         Product page for Stage 4 (set to "coming soon")
assets/css/styles.css              Colors, fonts and layout for every page
assets/img/                        Your logo files and site icons
```

## Before you go live

Search the files for these placeholders and replace them:

- [ ] `[YOUR PRICE]` in `guides/getting-to-a-diagnosis.html`
- [ ] `YOUR-CHECKOUT-LINK` in `guides/getting-to-a-diagnosis.html` (see step 4)
- [ ] `[Your story: ...]` in `about.html`

**Never upload your paid PDFs to GitHub.** Your repository is public, so anyone could download them for free. Your PDFs go to your checkout platform (Payhip, Gumroad or Lemon Squeezy) instead.

## 1. Create the repository

1. Sign in to GitHub and click **New repository**.
2. Name it exactly `The-Spectrum-Library.github.io`. This makes your site's address `https://the-spectrum-library.github.io` (GitHub shows web addresses in lowercase).
3. Set it to **Public** and click **Create repository**.

## 2. Upload the files

1. On the new repository page, click **uploading an existing file**.
2. Drag in everything from this folder: the HTML files plus the `assets` and `guides` folders. Keep the folder structure exactly as it is.
3. Click **Commit changes**.

## 3. Turn on GitHub Pages

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Pick the `main` branch and the `/ (root)` folder, then click **Save**.
4. Wait a minute or two, then visit `https://the-spectrum-library.github.io`.

## 4. Add your buy button

1. Create an account on Payhip, Gumroad or Lemon Squeezy.
2. Add "Getting to a Diagnosis" as a digital product and upload the PDF there.
3. Copy your product's link.
4. In `guides/getting-to-a-diagnosis.html`, replace `YOUR-CHECKOUT-LINK` with that link.

Each platform also offers embed code for a pop-up checkout. To use it, paste the code where the `BUY BUTTON` comment is, following the platform's instructions.

## 5. Connect your own domain (optional)

1. Buy a domain such as `aplearninglab.com` from a registrar.
2. In GitHub, go to **Settings → Pages → Custom domain**, enter your domain and click **Save**.
3. At your registrar, add the DNS records GitHub shows you.
4. Back in GitHub, tick **Enforce HTTPS** once it becomes available.

## Updating the site

**When "Getting to Yes" is ready:**
- In `guides/getting-to-yes.html`, replace the "Email me when it's ready" block with a price and buy button. Copy them from the Stage 1 page.
- In `index.html`, find the Stage 4 row in the series list and make it match the Stage 1 row:
  - add `is-ready` to its `class="stage-row"`
  - change "Coming soon" to an "Available now" link
- Update or remove the "Open enrollment is here" section on the home page.

**When you add a new guide:**
1. Copy `guides/getting-to-a-diagnosis.html` and rename the copy.
2. Change its text.
3. Mark its stage as ready on the home page.
4. Add a link to it in the footer list on each page.

**To edit a file on GitHub:** open it, click the pencil icon, make your change and click **Commit changes**. The site updates within a minute or two.

## Ideas for later

- **Email signup:** a free tool like MailerLite or Kit gives you a signup form to paste in. It would replace the "Email me" links.
- **A free download:** offer something like the Behavior Log worksheet to build your email list.
- **The 50-state directory:** add an early intervention page with a section for each state.
