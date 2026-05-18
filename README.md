# 🎨 Project Circle Blueprint — Full-Featured System Document

A comprehensive, professionally-designed blueprint website for Project Circle (trust-centered dating app).

## Features

✅ **Table of Contents + Navigation Sidebar** — Easy section browsing
✅ **Search Bar** — Full-text search across all blueprint content
✅ **Page Numbers** — Traditional document structure (like a real system)
✅ **Section Headers** — Clear visual hierarchy
✅ **Responsive Design** — Mobile-friendly
✅ **Dark Mode** — Reader-friendly
✅ **Copy/Share** — Linked sections, easy reference

## Structure

```
/
├── pages/
│   ├── index.tsx          (landing page with toc + search)
│   ├── _app.tsx           (app wrapper)
│   └── _document.tsx      (document head)
├── components/
│   ├── Sidebar.tsx        (navigation)
│   ├── SearchBar.tsx      (fuse.js search)
│   ├── Content.tsx        (blueprint renderer)
│   └── PageNumber.tsx     (footer page numbers)
├── lib/
│   └── blueprint-content.ts (all content + structure)
├── styles/
│   └── globals.css        (tailwind + custom)
└── next.config.js         (export for static deployment)
```

## Deployment

```bash
npm run build
npm run export
# Upload 'out' directory to Cloudflare Pages
```

## Design System

- **Colors:** Circle Black (#1A1A1A), Emerald (#2D6A4F), Warm Neutral (#D4B5A0)
- **Typography:** Helvetica Neue (headlines), Avenir (body)
- **Spacing:** 8px grid system
- **Motion:** Smooth, intentional transitions

---

**Project Circle v3.3 Blueprint**  
May 17, 2026
