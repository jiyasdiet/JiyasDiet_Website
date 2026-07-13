# Jiya's Diet — Website

Static website for a Registered Dietitian: diet plans, reviews and FAQ.

## Pages

| File | Page |
|---|---|
| `index.html` | Home (hero, services, kitchen gallery, reviews, about, FAQ) |
| `plan-details.html` | Diet plans — swipeable carousel; deep-link via `#weight-loss`, `#diabetic`, `#post-pregnancy` |
| `about.html` | About the dietitian |
| `faq.html` | FAQ |

Each page is fully self-contained (styles, scripts and images inlined) — no build step, no dependencies.

## Deploy

Any static host works:

- **GitHub Pages**: repo Settings → Pages → Deploy from branch → `main` / root. Site appears at `https://jiyasdiet.github.io/JiyasDiet_Website/`.
- **Netlify / Vercel**: drag the folder in, or connect the repo.

## Still demo (to wire before real orders)

- **Buy now** buttons show a demo message — point them at Razorpay Payment Pages / Instamojo links to take real payments.
- Contact: `jiyasdiet@gmail.com` (footer of every page).
