# VANTA DETAIL — Automotive Detailing Website Template

**Your car. Reimagined.** A premium, cinematic website template for car detailing businesses:
a scroll-driven 3D vehicle that gets cleaner as you scroll, a live quote builder, vehicle-size
pricing and a real seven-step booking flow.

**[Live demo](https://vanta-detail-muad1.vercel.app)** · **[Get the template ($49)](https://muadme.gumroad.com/l/wdpgn)**

![VANTA DETAIL hero](screenshots/01-hero.png)

## What's inside

- **Scroll-driven 3D hero** — the camera circles a realistic car (front ¾ → front → side → rear → paint
  close-up) while the dust clears, with a small surface-analysis readout. Phones and weak devices get
  a pre-rendered scroll sequence instead of live WebGL.
- **Vehicle-size pricing** — choose Sedan, SUV, Truck… and every price on the site updates from one config.
- **Quote builder** — vehicle, service, condition, add-ons, service-area check with travel fee, photo
  upload and a live estimate. One question per screen on phones.
- **Booking in seven steps** — service, vehicle, calendar, time, location, details, confirmation with a
  booking number, Google Calendar / .ics and a prefilled WhatsApp message.
- **Before/after sliders**, a filterable transformation gallery and a fullscreen lightbox.
- **Interactive explainers** — a vehicle "detailing scan", a paint surface lab, a water-beading demo that
  reacts to the cursor, paint-correction levels, ceramic packages and interior hotspots.
- Memberships (monthly / annual), fleet enquiries, a service finder, a mobile-service map, testimonials,
  a journal, FAQ, a "/" quick-nav and a light theme. 14 pages plus service and article pages.

![Surface analysis](screenshots/02-surface-analysis.png)
![Quote builder](screenshots/11-quote-builder.png)
![Before and after](screenshots/06-before-after.png)
![Booking calendar](screenshots/12-booking-calendar.png)
![Confirmation](screenshots/13-confirmation.png)
![Detailing scan](screenshots/04-detailing-scan.png)
![Ceramic water test](screenshots/08-ceramic.png)
![The finish](screenshots/09-the-finish.png)
![Mobile](screenshots/14-mobile.png)

## Built with

React 19 · TypeScript · Vite · Tailwind CSS v4 · three.js / React Three Fiber · React Router.
Content lives in a few documented config files; the demo booking engine runs in the browser and has
two functions to swap for a real calendar API.

**Lighthouse** (production build): desktop Performance 99 · mobile 86–94 · Accessibility 95–100 ·
Best Practices 100 · SEO 100.

All imagery is rendered from the site's own 3D scene. The 3D car is "Car Concept" by Eric Chadwick /
Darmstadt Graphics Group, CC BY 4.0 (modified, logos removed).

---

This repository is a showcase. The full source code is available as a paid template.
Built by [Mouad Sehli](https://muad-portfolio.vercel.app).
