# Physics & Maths Teacher — Manzi Delick

Personal tutoring website for Manzi Delick, a Physics and Mathematics tutor based in Kampala, Uganda, coaching O-Level and A-Level students under the UNEB curriculum.

**Live site:** [physicsandmathsteacher.com](https://physicsandmathsteacher.com)

## Why This Project

This site was designed and built end-to-end by me — from layout and visual identity through to the technical implementation, SEO strategy, and lead-generation flow.

It reflects the kind of work I do as a website designer for small businesses and independent professionals:

- **Custom, from-scratch design** — no page builders or templates; every layout, color system, and interaction was designed intentionally for the brand
- **Conversion-focused UX** — a booking flow built specifically around WhatsApp, the channel my client's customers actually use, rather than a generic contact form nobody checks
- **Technical SEO done properly** — structured data (JSON-LD), canonical URLs, Open Graph/Twitter meta, and an FAQ section built to be picked up by both search engines and AI answer engines
- **Full-stack when needed** — a Supabase-backed private resource library with authentication and access control, built alongside the front-end rather than bolted on
- **Fast, framework-free** — hand-written HTML/CSS/JS, no unnecessary dependencies, quick to load even on slower connections

If you're looking for a website that's designed around how your actual customers behave — not just a template with your logo on it — this is the kind of work I deliver.

---

## About the Site

This is the website and booking system for one-on-one and group Physics and Mathematics coaching, covering:

- O-Level (UCE) Physics and Mathematics
- A-Level (UACE) Physics, Pure Mathematics, and Applied/Subsidiary Mathematics

Visitors can browse subjects taught, read coaching notes on the blog, book a diagnostic or coaching session directly via WhatsApp, and (for enrolled students) access a private resource library of past papers and notes.

## Tech Stack

- **Frontend:** Plain HTML, CSS, and JavaScript — no framework or build step
- **Hosting:** GitHub Pages, served on a custom domain via `CNAME`
- **Library backend:** [Supabase](https://supabase.com) (PostgreSQL with Row Level Security, private storage bucket, OTP email sign-in via Resend)
- **Booking:** Direct WhatsApp integration — the contact form builds a pre-filled WhatsApp message from the visitor's details

## Site Structure

```
/
├── index.html              # Homepage
├── blog/                   # Coaching notes and articles
│   ├── index.html          # Blog listing + FAQ section
│   └── *.html               # Individual posts
├── library/                 # Private resource library (gated, Supabase-backed)
├── login/                   # Student sign-in for the library
├── admin/                   # Admin panel for managing library content
├── sitemap.xml
├── robots.txt
└── CNAME                    # Custom domain configuration
```

## SEO

The site includes canonical tags, Open Graph and Twitter Card meta, JSON-LD structured data (`Person`, `BlogPosting`, `FAQPage`), and a sitemap — targeting local search terms around O-Level and A-Level tutoring in Kampala.

## Contact

Bookings and enquiries go through WhatsApp — use the "Book a session" button on the site, or reach out directly at [+256 750 349712](https://wa.me/256750349712).
