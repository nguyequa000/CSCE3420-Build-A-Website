# Quan Nguyen | CSCE 3420

A static personal website for the CSCE 3420 assignment. No build tool or package manager is required.

## Local preview

From this directory:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/` in a browser.

## Publishing later

1. Run `gh auth login` and confirm the active GitHub account is the one you want to publish under (`nguyequa000`).
2. Create a GitHub repository and push this folder to its `main` branch.
3. In AWS Amplify, connect the GitHub repository and deploy `main`. Accept the detected defaults first. If detection is incorrect, configure the static output root; there is no mandatory build tool.
4. Submit the actual `amplifyapp.com` URL produced by Amplify, not the repository URL.

Nothing is deployed by this repository, and no AWS cost guarantee is made.

## Assets and license

- Bootstrap 5.3.8, MIT License. Local copies are in `css/` and `js/`; see `BOOTSTRAP-LICENSE.txt`.
- `img/workspace.svg` is the original coding-workspace illustration for this site. It is artwork, not a portrait.
