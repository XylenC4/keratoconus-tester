# Keratoconus test

A single-file, browser-based visual check inspired by keratoconus “ghosting/double vision” symptoms. It renders multiple preview panels using bold text and bloom-like shadows (via CSS `text-shadow`) to make subtle duplication/blur effects easier to notice.

The page provides:
- Multiple preview cards (text, dots, and lines) to compare perception across shapes
- A focused “maximized” view when clicking a card
- Adjustable parameters (direction, distance, size, bloom/blur, opacity) and a dial UI in focused view
- Save/Load of settings to a local JSON file
- Print-friendly layout

## Disclaimer (not medical advice)
This project is for educational and self-check purposes only. It is **not** a medical device and does **not** diagnose keratoconus or any eye condition. If you have visual symptoms or concerns, consult a qualified eye-care professional.

## Usage
1. Open `index.html` in a modern browser.
2. Click any preview card to open the focused view.
3. Adjust direction/distance/size/bloom/opacity in the left control panel.
4. Use:
   - **Save…** to export settings to `bloom-settings.json`
   - **Load…** to import previously saved settings
   - **Print view** for a clean print layout

## Hosting on GitHub Pages
1. Put the file in the repo as `index.html`.
2. GitHub repo → **Settings** → **Pages**
3. Source: `main` branch, `/root` folder
4. Your site will be available at `https://<username>.github.io/<repo>/`

## Acknowledgements
This project was developed using an iterative, AI-assisted workflow (“vibe coding”) with the help of ChatGPT.  
All final design decisions, testing, and responsibility for the code remain with the repository owner.

## License
MIT License

