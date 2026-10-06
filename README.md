# BODY IQ Analytics — website (static, first draft)

## Files
- index.html — the website (hash routes: /#/how-it-works, /#/packages, /#/pkg-womens-health …)
- assessment.html — the 24-question assessment
- support.js, image-slot.js — runtime
- assets/ — photos (assets/web = optimized), hero3.mp4, cta.mp4
- logos/ — icon-swirl.png (default), icon-hex.png
- vercel.json — clean URLs + asset caching

## Deploy to Vercel
1. npm i -g vercel
2. cd deploy && vercel  (framework: Other, output: this folder)

## Notes
- Chat assistant: uses the in-page AI helper when present; on Vercel it falls back to built-in answers. For a live model, add an API route (e.g. api/chat.js) and call it from chatAsk() in index.html.
- Prices, names, references and legal text are placeholders marked "to confirm".
"# Body-Iq" 
