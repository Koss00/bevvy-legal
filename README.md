# chasr-legal (redirect)

This page used to host the CHASR privacy policy and terms of service. The current
text lives at **https://chasr.club/privacy** and **https://chasr.club/terms**, served
from the `chasr-site` repo (`app/(marketing)/privacy` and `app/(marketing)/terms`).

`index.html` is now a redirect to `chasr.club/privacy`, kept so the old URL keeps
working in older app builds and any listing that still points here. Do not put
policy text back in this file; edit the site pages instead.

The repo is named `bevvy-legal` for the same reason the app's bundle id and
deep-link scheme still say `packd`: the product was renamed twice (Packd →
Bevvy → CHASR) and the identifiers were deliberately frozen so existing
sessions, deep links, and store listings keep working.
