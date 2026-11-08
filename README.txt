# High Mark Associates — Digital Business Card

A responsive, dark luxury digital business card built with plain HTML, CSS and JavaScript.

## 1. Add your real links
Open `index.html` in a text editor and find `const CARD = {` near the bottom.

Replace:
- `923XXXXXXXXX` with your WhatsApp number in international format, digits only. For Pakistan, start with `92` and omit the leading `0`.
- `https://www.instagram.com/YOUR_USERNAME/` with the office Instagram profile URL.
- `https://www.facebook.com/YOUR_PAGE/` with the office Facebook page URL.

The office address is already filled in. Check it before publishing.

## 2. Preview it
Open `index.html` in Chrome. The logo is in `assets/highmark-logo.png`.

## 3. Publish free with GitHub Pages
1. Create or sign in to a GitHub account at https://github.com.
2. Create a **Public** repository named `highmark-digital-card`.
3. Upload `index.html` and the entire `assets` folder (keep the folder structure).
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then press **Save**.
7. Wait a minute or two. GitHub will show your public website address, usually:
   `https://YOUR-GITHUB-USERNAME.github.io/highmark-digital-card/`

## 4. Make the QR code
After the website is live:
1. Copy the exact GitHub Pages URL.
2. Create a static QR code using a reputable free QR generator.
3. Download it as PNG or SVG and test it by scanning with a second phone.
4. Keep the QR code unchanged. If you later update the page links or design, the same QR code will still work.

## Important
- Do not use a dynamic QR code that requires a paid subscription.
- The GitHub repository is public, so do not put private information in the code.
- The logo was cropped from the logo visible in the supplied screenshot. Replace it with the original high-resolution logo if available.
- The WhatsApp and social links are placeholders until you edit `CARD`.
