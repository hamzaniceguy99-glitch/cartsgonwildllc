# Carts Gon Wild — carts gon wild llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `cartsgonwildllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/cartsgonwildllc.mjs`).
> To change the content, edit that file and run `node build.mjs cartsgonwildllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@cartsgonwildllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Carts Gon Wild LLC is a Florida limited liability company working on golf carts and low-speed vehicles since 2020: supply, custom work, street-legal conversions and service. One number governs all of it and almost nobody gets told it, which is top speed. A cart that cannot exceed 20 mph is exempt from titling, registration and compulsory insurance in Florida, and may only be used on roads approved for golf carts. Lift it, regear it or fit a bigger controller so it runs 24 mph and the same machine has become a low-speed vehicle, which is a motor vehicle: titled, registered, insured with personal injury protection and property damage liability, driven by someone holding a driver license, and kept to roads posted at 35 mph or less. It also has to carry the federal equipment a low-speed vehicle needs, including a windshield, mirrors, lamps, turn signals, a parking brake, seat belts at every seat and a vehicle identification number. Above 25 mph there is no road category left to fall into, so a machine built past that point is not street legal and we will not describe it as such. We measure top speed before quoting the work. Site: cartsgonwildllc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
