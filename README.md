# Great AI Lab v5 — Gemini Free-Tier Private Test

Five studios: Business, Growth, Course, eBook, Kids. Generate an AI blueprint and individual units; edit, save browser-locally, export Markdown/HTML and Print to PDF. Kids outputs include text and visual briefs, NOT AI-generated images.

## No payment required for eligible Gemini free-tier usage
1. Visit https://aistudio.google.com/apikey and sign in with a Google account. Create a key for a **Free Tier** project. Do not enable paid billing.
2. Create a private GitHub repository and upload the *contents* of this ZIP, preserving `netlify/functions/generate.mjs` and `netlify.toml`.
3. In Netlify, import the repository as a site. Netlify Drop of a static HTML alone will not deploy the function.
4. Netlify site → Project configuration → Environment variables. Add `GEMINI_API_KEY` (your secret key) and `LAB_ACCESS_CODE` (a private password you create). Optional `GEMINI_MODEL=gemini-2.5-flash`.
5. Deploy/redeploy. Open the Netlify site, enter your private access code, then try Business Studio → Generate blueprint → Unit 1.
6. Verify actual quality. Repeat with Course, eBook, Growth and Kids. Test PDF using browser Print → Save as PDF.

Never paste the API key in ChatGPT, public GitHub, website HTML, or social posts. Keep the project private. Free tier has quotas and may be unavailable for some models/accounts; see Google AI Studio quotas. Do not turn on billing if you want zero API cost. Netlify's free plan also has platform limits.

## Limitations
- Live Gemini API not end-to-end tested here because no user API key is available.
- The app is a PRIVATE test beta, not safe for public users. A shared access code is not per-user auth, quota or bot protection.
- No real AI illustrations, polished PDF layout, cloud saved accounts, or guaranteed full book in one click.
- Free-tier content may be used by Google to improve products: do not enter confidential client data.
- Long projects require generating units one by one. Free-tier rate limits can interrupt runs.
