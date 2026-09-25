# Support the Creator

A playful static landing page for collecting support from friends, visitors, and supporters. The page includes a QR-style support card and a direct UPI payment button for quick donations.

## Features

- Minimal one-page support page
- UPI payment link for mobile users
- Soft pastel design with decorative stickers
- Fully static HTML and CSS setup

## Project structure

- `index.html` — page structure and content
- `style.css` — styling, layout, and animations
- `assets/` — decorative SVG illustrations and visuals

## Run locally

Open `index.html` directly in a browser, or serve the folder with a simple local server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Customize

Update the UPI payment address in `index.html` to your own VPA:

```html
<a href="upi://pay?pa=your-upi-id@upi&pn=YourName&cu=INR" target="_blank">
    Pay via any UPI app
</a>
```

## License

This project is provided as-is for personal or small-project use.
