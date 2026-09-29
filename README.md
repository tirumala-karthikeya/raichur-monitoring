# raichur-monitoring

School link page for the Raichur District School Monitoring web app.

Opening the Apps Script link directly on a phone signed into several Google
accounts redirects to `.../macros/u/1/s/...` and fails with "Sorry, unable to
open the file at present". `index.html` loads the app in a credentialless frame
(no Google cookies), so it always opens as an anonymous visitor.

Served with GitHub Pages. If the Apps Script deployment ID changes, update
`APP_URL` in `index.html` and `WEB_APP_URL` in the Config sheet together.
