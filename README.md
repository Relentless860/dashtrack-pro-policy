# DashTrack Pro policy website

Public support and privacy information for DashTrack Pro.

- Website: https://relentless860.github.io/dashtrack-pro-policy/
- Privacy policy: https://relentless860.github.io/dashtrack-pro-policy/privacy.html
- Support contact: dashtrackpro@gmail.com

## Edit in VS Code

Open the DashTrack workspace at `C:\DashTrackMobile\DashTrackPro.code-workspace` and find this repository under `policy-site/`.

Edit `privacy.html` for policy changes or `index.html` for the landing page. Keep the app's `app/PRIVACY_POLICY.md` and `app/docs/privacy.html` consistent with the published policy.

## Publishing

GitHub Pages publishes the `main` branch at its root. Commit and push approved changes from this folder to update the website:

```powershell
git add index.html privacy.html README.md .nojekyll
git commit -m "Update DashTrack policy website"
git push
```

This repository contains the policy website. The mobile application is maintained separately.
