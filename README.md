# Digital Business Card (NFC → GitHub Pages)

This repo is a minimal NFC-friendly digital business card.

## What it does

- Your NFC tag stores **one URL** (this GitHub Pages URL).
- Tapping the tag opens the page.
- The **Save contact** buttons download a `.vcf`, which both iPhone and Android can import.

## Enable GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`) and `/ (root)`
4. Your URL will look like: `https://<username>.github.io/<repo>/`

## Program the NFC tag

Use an app like **NFC Tools**:

- Write → Add a record → **URL / URI**
- Paste your GitHub Pages URL
- Write and tap the tag

## Edit your details

- Contact download files: `contact.vcf` (Camiel) and `rutger.vcf` (Rutger)
- Page layout/styles: `index.html`, `styles.css`
- Logo image: `logo.png`
