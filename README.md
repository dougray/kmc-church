# Kingsbury Methodist Church

One-page website for Kingsbury Methodist Church — Kingsbury, Texas.
A congregation of the Global Methodist Church, Bexar District, Mid Texas Conference.

**Live site:** https://dougray.github.io/kmc-church/

## Structure

Single self-contained `index.html`. All CSS is inline in `<head>`. No build step,
no JavaScript, no dependencies. The only external request is one Google Font (Lora).

## Editing

Open `index.html` and edit the text directly. Commit to `main` and GitHub Pages
redeploys within a minute or two.

Details that appear in more than one place — service time, phone, address, email —
are repeated in the page body and in the JSON-LD block near the top of the file.
Update both.

## Source of the church details

Service time, pastor, address, phone, and email come from the church's own
Facebook page. Denomination and district come from the Mid Texas Conference
directory. Third-party church directories (YellowPages, FaithStreet, joinmychurch)
carry stale data for this church and were not used.

## Assets

- `assets/church.jpg` — the church building, taken from the congregation's own
  Facebook cover photo (948×960, the largest size Facebook serves publicly).
- `assets/gmc-logo-white.png` — Global Methodist Church wordmark, white knockout
  version, from globalmethodist.org. Only legible on a dark background; it is
  used in the footer.
- `assets/gmc-logo.svg` — full-colour GMC logo (vector) from the Mid Texas
  Conference site. Kept as the source for the favicon; not referenced by the page.
- `assets/favicon.svg` — the GMC cross-and-circles mark alone, extracted from
  `gmc-logo.svg` and recoloured to the brand blue.
- `assets/apple-touch-icon.png` — 180×180 raster of the same mark on white.

The GMC logo is a Global Methodist Church trademark. Member congregations
normally use it; formal guidelines are in the GMC Brand Book, and logo files can
be requested via globalmethodist.org/brand.

## Map

The map is a keyless OpenStreetMap embed centred on 29.6447536, -97.8270816.
That point is an unnamed place-of-worship node in OSM, matched to this church by
position rather than by name — worth confirming the pin lands on the right
building. The "Get Directions" and "Open in Google Maps" buttons use the street
address, not these coordinates.

## License

The site's own code — `index.html` and everything in it — is MIT licensed. See
`LICENSE`.

**The MIT licence does not cover the contents of `assets/`,** which are not ours
to relicense:

- `church.jpg` belongs to Kingsbury Methodist Church.
- `gmc-logo-white.png`, `gmc-logo.svg`, `favicon.svg`, and `apple-touch-icon.png`
  are the Global Methodist Church trademark, used here as a member congregation.
  Anyone reusing this code should swap in their own artwork.
