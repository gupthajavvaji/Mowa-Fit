# Mowa Fit MVP

A local-first, mobile-friendly PWA. No AI API, login, database or paid service is required for this MVP.

## Run locally

Because service workers require localhost or HTTPS, use a local server:

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080` in a browser.

## Deploy for iPhone install

1. Upload the contents of this folder to a static HTTPS host (for example, a GitHub Pages repository or a static host of your choice).
2. Open the deployed HTTPS URL in Safari on your iPhone.
3. Tap Share → Add to Home Screen → Add.
4. Launch Mowa Fit from the Home Screen.

## Notes
- Meal calories and protein are estimates. Change them to match actual brands and portions.
- Data is saved in localStorage on the current browser/device. Export JSON from Progress for backup. There is no cloud sync.
- The workout template is conservative, not a medical rehabilitation plan. With a previous meniscus surgery and intermittent pain, stop movements that cause pain, swelling, locking or instability and seek clinician/physical therapist advice.
- Targets are starting placeholders, not a clinical prescription. Calorie/protein needs depend on age, sex, activity, health and preferences.
