# Gomez Woodworking Shop — Website

A premium custom cabinetry website built with HTML, CSS, and Vanilla JavaScript.

## 🚀 Deployment (Vercel)

Set the following in your **Vercel Dashboard → Project → Settings → Environment Variables**:

| Variable | Description | Example |
|---|---|---|
| `PHONE_TEL` | Phone for `tel:` links (digits only, no +) | `5551234567` |
| `PHONE_DISPLAY` | Phone as displayed (full format) | `+1 (555) 123-4567` |
| `PHONE_DISPLAY_SHORT` | Phone short format | `(555) 123-4567` |
| `PHONE_SCHEMA` | Phone for Schema.org JSON-LD | `+1-555-123-4567` |
| `EMAIL` | Contact email address | `contact@yourshop.com` |
| `SITE_URL` | Canonical site URL (with trailing slash) | `https://yoursite.com/` |

> **Note:** The HTML uses `{{PLACEHOLDER}}` tokens. Vercel runs `build.js` at deploy time to inject your real values.

## 📁 Project Structure

```
├── index.html    # Main website (single-page, self-contained)
├── build.js      # Vercel build-time env var injector
└── vercel.json   # Vercel deployment config
```
