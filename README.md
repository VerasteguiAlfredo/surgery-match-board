# Surgery Match Board

Personal tracker for the ERAS 2027 General Surgery Match, served with GitHub Pages.

- `index.html` is the page (data is embedded).
- `state.json` holds your statuses, interview dates, notes and Step 2. The page writes it through the GitHub API.

## Saving from a device
1. Create a fine-grained token at GitHub → Settings → Developer settings → Fine-grained tokens.
2. Repository access: only this repository. Permissions: **Contents: Read and write**.
3. Open the page, click **Sync settings**, paste the token, then **Save token**. Repeat on each device.

Anyone can read this repository and `state.json` while it is public.
