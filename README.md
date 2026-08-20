# chasr-legal

The public privacy policy and terms of service for **CHASR**, a nightlife
discovery app for Ann Arbor and New York City.

A single static `index.html`, deployed as the policy URL that the App Store and
Google Play listings point at, and that the app links to from its settings
screen. No build step and no dependencies — a legal page should still render in
ten years, and the surest way to manage that is for it to be one file.

The repo is named `bevvy-legal` for the same reason the app's bundle id and
deep-link scheme still say `packd`: the product was renamed twice (Packd →
Bevvy → CHASR) and the identifiers were deliberately frozen so existing
sessions, deep links, and store listings keep working. Only display strings
carry the current brand.
