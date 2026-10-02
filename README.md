# Swapan Mallick — Personal Research Website

A responsive single-page portfolio for research in data assimilation, numerical weather prediction, satellite remote sensing and AI.

## 1. Preview locally

Open `index.html` directly in your browser, or run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## 2. Replace the placeholders

Open `index.html` and replace:

- `YOUR_EMAIL@smhi.se`
- `YOUR_GOOGLE_SCHOLAR_URL`
Already configured:
- GitHub: `https://github.com/swapanmallicksmhi`
- ORCID: `https://orcid.org/0000-0002-6851-5022`
- LinkedIn: `https://www.linkedin.com/in/dr-swapan-mallick-90865784/`

## 3. CV

Your CV is already included as `assets/Swapan_Mallick_CV.pdf`, and the **Download CV** button is active.

## 4. Publish with GitHub + Netlify

Create a GitHub repository, for example:

`swapan-mallick.github.io` or `swapan-research-portfolio`

From this folder run:

```bash
git init
git add .
git commit -m "Initial personal website"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

Then:

1. Sign in to Netlify.
2. Choose **Add new project → Import an existing project**.
3. Select GitHub and this repository.
4. Build command: leave empty.
5. Publish directory: `.`
6. Deploy.

Netlify will provide an address similar to:

`https://your-site-name.netlify.app`

You can change the site name in **Site configuration → Domain management**.

## 5. Recommended updates

- Add your full publication list and DOI links.
- ORCID, GitHub and LinkedIn URLs are already configured.
- Add project links or GitHub repositories where appropriate.
- Add a professional CV PDF.
- Optionally connect a custom domain such as `swapanmallick.com`.

## Structure

```text
swapan-mallick-portfolio/
├── index.html
├── styles.css
├── script.js
├── netlify.toml
├── README.md
└── assets/
    ├── favicon.svg
    └── Swapan_Mallick_CV.pdf   # add this file
```

## Privacy note

The public website intentionally omits your mobile number, private residential addresses, nationality, and personal Gmail address from the CV. The site uses only your professional SMHI email by default.
