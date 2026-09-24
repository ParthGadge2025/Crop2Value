# Crop2Value

Turn Agricultural Waste Into Rural Wealth. A free, static website: marketplace, equipment rental with booking, request board,
aggregation batches, government schemes (Apply opens the official portal), map, history, chat and offers, voice control,
5 languages (English, Hindi, Marathi, Malayalam, Tamil), dark/light mode, installable on phones.

No accounts to create, no OTP, no server, no cost. Everything runs in the visitor's browser and is saved there (localStorage).
Listings, chats and bookings are therefore private to each visitor's device and are demo data, not shared between users.

## Put it on GitHub (free, about 5 minutes)
1. Make a free account at github.com and click New repository. Name it crop2value, choose Public, click Create repository.
2. On the empty repository page click "uploading an existing file". Unzip this zip first, then drag EVERYTHING inside the folder
   (index.html, css, js, icon.svg, manifest.webmanifest, sw.js, robots.txt, .nojekyll, README.md) into the page. Click Commit changes.
   Tip: if .nojekyll is hidden on your computer, it is fine to skip it.
3. Open Settings > Pages. Under "Build and deployment" set Source to "Deploy from a branch", Branch to main and folder to / (root). Save.
4. Wait 1-2 minutes and refresh that page. It shows your link: https://YOUR-USERNAME.github.io/crop2value/
5. To change anything later, open a file on GitHub, click the pencil, edit, and commit. The site updates by itself.

Other free hosts work the same way: Netlify Drop (app.netlify.com/drop, drag the folder) or Cloudflare Pages.

## Test on your computer
    python3 -m http.server 8080      (then open http://localhost:8080)

## Where to edit things
- Translations: the D object in js/app.js, one line per key: [English, Hindi, Marathi, Malayalam, Tamil].
- Demo listings, requests, buyers: SEED, RQ, BUY, CC in js/app.js. Storage key is c2v3; change it to reset every visitor's saved data after you edit demo data.
- Government schemes: the GOV list in js/app.js. Check every rule and link on the official portal first.
- Price ranges: MR in js/app.js.
- Colours and animations: css/style.css.

## What this version does not do
- No real accounts, no shared data between users, no real phone calls (the Call button is a demo), no payments, no SMS.
- The map is a schematic radar view with approximate positions.
- If you later want real users, chat between devices and payments, that needs a backend (for example Supabase). The earlier zip that includes the Supabase code still works for that.

## Price data (indicative, September 2026)
The demo listings and the "Typical market range" bar use these ranges (edit MR in js/app.js to update them):
- Rice straw: farm gate about Rs 1,200-2,000/t (PelletRates, Mar 2026); loose Rs 1,000-1,500 and baled Rs 2,500-3,000/t (Servoday). App range: Rs 1,200-3,000/t.
- Cotton stalk (raw): about Rs 3-3.5/kg, i.e. Rs 3,000-3,500/t (BioBiz, Dec 2024).
- Compost / fermented organic manure (bagged): Rs 3,000-6,000/t (GrowDiesel, Aug 2026); an IndiaMART listing shows Rs 5,000/t.
- Tractor with implements: Rs 800-1,500 per hour (Tractor Gyan, Jun 2026); a 75 HP+ tractor with rotavator listing shows Rs 1,300/hour (IndiaMART).
- Harvesting (custom hiring centres): Rs 1,800-2,900 per acre (iHarvester price guide, Feb 2026); combine rental Rs 2,000-3,000/hour (agriculture.institute, Nov 2025).
- Coconut husk and wheat straw (bhusa): no reliable public benchmark found, so the app shows "No reliable benchmark yet" instead of a range.
- The logistics estimate on aggregation batches (Rs 20 per km) is an assumption, not a sourced rate.
Caveats: these come from trade portals and industry blogs, not official mandi data. Prices differ by district, season, moisture and quality, and straw prices swing sharply after harvest. Re-check them before showing real farmers, and never present them as guaranteed prices.
