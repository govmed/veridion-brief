# veridion-brief

The static site served at <https://brief.veridion-llc.com>, split out of `govmed/veridion-site`
so each property has its own subdomain, its own certificate and its own
1 GB GitHub Pages budget.

Styling is shared: every Veridion site loads
`https://veridion-llc.com/style.css` so the five cannot drift apart. This
site overrides only its accent colour, in a `<style>` block in `index.html`.

`veridion-llc.com` remains the hub and keeps Transparency, Support and
Members. **`veridion-llc.com/support` and `veridion-llc.com/curo/privacy`
are compiled into the shipped Curo binary and registered with Apple — they
must never move.**
