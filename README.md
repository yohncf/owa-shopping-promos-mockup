# Outlook Web Access — "Shopping & Promos" Mockup

A high-fidelity, fully interactive single-file web mockup of the free consumer version of
**Outlook Web Access (OWA)**, featuring a custom, heavily monetized **"Shopping & Promos"**
inbox experience.

Everything lives in one self-contained file: [`index.html`](./index.html) — no build step,
no dependencies. Just open it in a browser.

## Features

### Faithful Outlook foundation
- Outlook blue (`#0078D4`) header with the Microsoft 365 app-launcher grid, logo, centered
  search bar, and notifications / settings / profile controls
- Slim left navigation rail (Mail, Calendar, People, To-Do, Files)
- Collapsible folder pane (Inbox, Sent, Drafts, Archive, Junk, Deleted…)
- **Focused** / **Other** tabs plus a glowing, animated **✨ Shopping & Promos** tab

### The "Shopping & Promos" dashboard
- **Active Orders** — a visually distinct, blue-bordered *personal* panel ("👤 Yours",
  "🔒 From your account · No ads") so your own purchases never get confused with adverts.
  Rich product cards with animated delivery progress bars and **Track Package** buttons.
- **Daily Deals** — vibrant deal cards with countdown timers and **Claim** coupon buttons.
- **Newsletter Inbox** — email-style rows that still feel like real mail (sender avatar,
  unread markers, subject, preview, tags, thumbnail).
- **Featured Reads** — rich newsletter cards.
- Click any card/email to open a slide-in **reading pane** (HTML receipts & newsletters).

### MSN-style monetization
- Auto-rotating **top banner ad** with a muted "video" placeholder
- Sticky right-hand **skyscraper** column with an interactive shopping **carousel** and
  rich-media ad units (auto & manual navigation, glow/scale hover effects)
- **Native in-feed** sponsored cards injected into the shopping grid

### Design
- Microsoft Fluent-style soft shadows, rounded corners, Segoe UI typography
- Responsive flexbox/grid layout
- Light & dark theme support via `?scoutTheme=dark`

## Run it

```
# just open the file
start index.html        # Windows
```

Or serve it locally:

```
python -m http.server 8000
# then visit http://localhost:8000/
```

## Note

This is a **design mockup** for demonstration purposes. It is not affiliated with or endorsed
by Microsoft. All product images are Unsplash placeholders; all emails, orders, and ads are
fictional.
