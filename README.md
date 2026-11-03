# RoyalDox by HKU

Single-page app (index.html). Cloud saving uses Firebase project `re-dox-by-hky` (Firestore collection `histories`).

## Files
- `index.html`: the whole app
- `vercel.json`: Vercel settings
- `firestore.rules`: Firestore rules (already published in Firebase console)

## Deploy
1. Upload these files to a GitHub repository (files at the repository root).
2. Vercel: Add New > Project > import the repository. Framework Preset: Other. Deploy.
3. Open the Vercel link. "Cloud saving ON" in the header means Firebase is connected.

## Update later
Replace `index.html` in GitHub. Vercel redeploys automatically.
