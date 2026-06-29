Vercel-ready static website

What changed:
- client-preview.html has been renamed to index.html because Vercel serves the root URL from index.html.
- vercel.json has been added so the root URL and any route fallback load index.html.

How to deploy:
1. Unzip this folder.
2. Upload the whole folder to Vercel, or push the folder contents to GitHub and import it into Vercel.
3. On Vercel, keep Framework Preset as Other.
4. Build Command: leave empty.
5. Output Directory: leave empty or use root if Vercel asks.
6. Deploy.

Important before client/live use:
- Replace placeholder clinic name, phone, email, address, business hours, reviews, canonical URL, and schema data.
