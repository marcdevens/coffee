# Coffee

A small, phone-first brew calculator for my home coffee setup. Pick a method and it shows the grind setting, scales the water and coffee together, and walks through the steps with a built-in timer.

**Methods**
- **Drip** (OXO Barista Brain 9-cup), sized by carafe cups
- **French press**, with a bloom and steep timer
- **Moka pot** (6-cup Bialetti Moka Express)
- **Pourover** (Kalita Wave 185), with a timer that tells you when and how much to pour

Grind settings and grind times are for a Baratza Encore ESP.

**Features**
- Amounts in grams or ounces
- Grind countdown, plus beep, vibration and on-screen flash cues
- Light and dark mode
- Saves your last amounts on the device

## How it's built

One static `index.html` with inline CSS and JavaScript. There's no framework, build step or backend, and it's deployed on Vercel. `vercel.json` and `robots.txt` keep it out of search engines.

To run it locally, serve the folder with any static server, for example:

```bash
python3 -m http.server
```

## Credits

The method icons are from [IconOven](https://iconoven.com/icons) by Appic Marketing, used under the MIT License. The pourover dripper icon is drawn to match them. The font is [Manrope](https://fonts.google.com/specimen/Manrope) (SIL Open Font License).
