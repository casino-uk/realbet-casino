# Realbet — Casino Overview (honest promo, with /go affiliate)

Companion to the sportsbook page. Dark + red/gold casino landing, openly promotional, with
truthful Tobique licensing and disclosures. Responsive, `lang="en-GB"`.

## Files
```
index.html      → casino overview (links logo.svg + favicon.png + style.css; hero is inline SVG)
style.css       → dark + red + gold theme (Montserrat + Barlow)
logo.svg / logo.png / favicon.png  → R-monogram logo (no Union Jack)
go/index.html   → cloaked redirect; /go → partner URL
```

## /go redirect (referral link)
Play now / Sign Up CTAs point to `/go`. In-page links are intercepted by JS; direct hits use
go/index.html. The affision referral link is already inserted:
  https://go.affision.com/visit/?bta=48740&nci=5426
in BOTH `PARTNER_URL` (index.html) and the three URLs in go/index.html.

## Deploy (GitHub Pages)
Upload all files (keep `go/`), Settings → Pages → branch `main`, root.
Project page → set CTA links to `/<repo>/go`.

## Notes
Honest version: licence stated as Tobique Gaming Commission (offshore; operator Forestflur
Limited, Cyprus), NOT UKGC; no UK/British framing, no Union Jack, no UKGC logo. UKGC/GamStop
noted as not applicable; 18+, check-local-law and responsible-gambling resources included.
