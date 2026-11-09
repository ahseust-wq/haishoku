Haishoku website — upload this folder as-is (e.g. GitHub Pages, Netlify).

index.html     landing page (shows the same daily combination as the app)
privacy.html   privacy policy — fill in REPLACE@EMAIL and your postal address
app-ads.txt    must be reachable at the ROOT of the domain entered as "Website"
               in Play Console (https://yourdomain/app-ads.txt). On GitHub Pages a
               project site lives at user.github.io/haishoku/, so put app-ads.txt in
               the user.github.io repository root, or use a custom domain.
wada-data.js   colour data for the daily plate
img/           icon and screenshots

After hosting, set PRIVACY_URL in app.js to https://yourdomain/.../privacy.html
and replace REPLACE@EMAIL in index.html and privacy.html.
