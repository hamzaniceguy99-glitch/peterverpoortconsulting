# Peter Verpoort — business support & interim

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `peterverpoortconsulting.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/peterverpoortconsulting.mjs`).
> To change the content, edit that file and run `node build.mjs peterverpoortconsulting` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@peterverpoortconsulting.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Referred) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are Peter Verpoort Consulting, an operational business support company based in Kontich, with head office support functions run from Lier. We take on back-office and administrative work that an owner-managed business has outgrown, step in as interim management when a role is vacant or a project needs running, review processes that have stopped working, and carry head office functions for small groups. One boundary shapes every engagement and it protects the client more than it protects us. Belgian law prohibits making your personnel available to a third party who would exercise employer authority over them, and temporary agency work is lawful only through a regionally licensed agency. So we deliver defined results under our own direction and we do not supply or lend people. A client who actually needs staff needs a licensed agency, and we will say so. Site: peterverpoortconsulting.shop
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
