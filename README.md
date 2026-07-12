# Jiya's Diet — Website

Static website for a Registered Dietitian: diet plans, consultation booking, reviews and FAQ.

## Pages

| File | Page |
|---|---|
| `index.html` | Home (hero, about, plans, reviews, booking, FAQ) |
| `plan-details.html` | Plan details — one page for all plans via `#weight-loss`, `#diabetic`, `#post-pregnancy` |
| `consultation.html` | Book a consultation |
| `about.html` | About the dietitian |
| `faq.html` | FAQ |

Each page is fully self-contained (styles, scripts and images inlined) — no build step, no dependencies.

## Deploy

Any static host works:

- **GitHub Pages**: repo Settings → Pages → Deploy from branch → `main` / root. Site appears at `https://jiyasdiet.github.io/JiyasDiet_Website/`.
- **Netlify / Vercel**: drag the folder in, or connect the repo.

## Still demo (to wire before real orders)

- **Buy now** buttons show a demo message — point them at Razorpay Payment Pages / Instamojo links to take real payments.
- **Consultation form** shows a success state locally — connect Formspree / Google Forms / WhatsApp to receive enquiries.
