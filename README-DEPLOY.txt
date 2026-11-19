PROJECT ASTER - HOW TO PUT THIS ON NETLIFY
==========================================
1. Unzip this file. You get a folder with index.html and some other files.
2. Open your site on app.netlify.com -> Deploys.
3. Drag the WHOLE folder (not just index.html) onto the box that says "Drag and drop your site output folder here".
4. Wait for "Published". Open your site and refresh.

Then, once, in Firebase (Realtime Database -> Rules): paste the contents of database.rules.json and press Publish.

Files in this folder
  index.html               the app
  manifest.webmanifest     lets people install it as an app
  sw.js                    makes it open offline
  icon-*.png, apple-touch-icon.png, og.png   app icon and link preview picture
  privacy.html, terms.html your privacy policy and terms of use (public pages)
  _headers                 safety settings for Netlify
  database.rules.json      the database rules (paste into Firebase, do not upload to Netlify)

If your website address ever changes (for example a custom domain), search index.html for
singular-tarsier-665622.netlify.app and replace it with your new address (used for the link preview picture).
