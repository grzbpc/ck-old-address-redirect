# ck-old-address-redirect

Sends every visit to the retired address
citizenknowledge.theperformanceofobedience.co.uk on to the same page at
https://citizenknowledge.co.uk, so links in emails sent before 30 October 2026
still work.

GitHub Pages serves `404.html` for any path that does not exist here, and that
page forwards the visitor to the matching path on the new domain. `index.html`
does the same for the bare address.

Nothing in this repository needs changing when new posts are published.
