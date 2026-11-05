<div align="center">

# 👔 FitCheck

### Stop wondering what to wear. Let your wardrobe tell you.

An AI-powered outfit matcher that lives on your phone. Photograph your clothes once, and FitCheck rates every shirt and pants combination out of 10, suggests shoe colors, picks jackets for winter, and tells you what to buy next.

**Free. No account. No app store. No backend.**

### 👉 [Open FitCheck: risalkalwar.github.io/AI-Outfit-App](https://risalkalwar.github.io/AI-Outfit-App/) 👈

![Free](https://img.shields.io/badge/price-free%20forever-22c55e)
![PWA](https://img.shields.io/badge/app-installable%20PWA-8b5cf6)
![Privacy](https://img.shields.io/badge/data-stays%20on%20your%20phone-06b6d4)
![No backend](https://img.shields.io/badge/backend-none-f59e0b)

</div>

---

## ✨ Why FitCheck?

Almost every morning the same question shows up: *does this green shirt go with these grey pants?* FitCheck answers it with real color theory, applied to the clothes you actually own, in a few seconds.

- 🎯 **Honest ratings out of 10**, with color-coded rings that animate as they fill
- 🧠 **AI that reads your photos**: it finds the true color, the clothing type and the pattern, and crops each photo to the garment
- 🧥 **Winter ready** with a separate Jackets section
- 🛍️ **Tells you what to buy** to unlock the most new outfits
- 🔒 **Private by design**: your wardrobe is stored only on your own phone
- 💸 **Costs nothing**, for you or for anyone you share it with

---

## 🚀 Get started in 60 seconds

**Open this link on your phone:** https://risalkalwar.github.io/AI-Outfit-App/

### 📱 iPhone (iOS)
1. Open the link in **Safari** (it only installs from Safari).
2. Tap the **Share** button.
3. Tap **Add to Home Screen**, then **Add**.
4. Open FitCheck from your home screen. It runs full screen like a normal app.

### 🤖 Android
1. Open the link in **Chrome**.
2. Tap the **⋮** menu, then **Install app** (or **Add to Home screen**).

### 💻 Computer
It works in any modern browser, but it is designed for phones.

---

## 🧭 A tour of the app

### 👔 Outfits
Your daily answer. Pick the occasion (**Casual, Office, Wedding, Eid**) and FitCheck shows your best matches first.

- A large **Best match** card, then a grid of more matches
- By default only outfits rated **7 or higher** are shown. Flip **Show outfits below 7** to see the rest
- **With jacket** adds the best matching jacket to each outfit
- **♥ Saved** keeps your favorite outfits in one place
- **Surprise me** opens a random great outfit
- Filter by one piece to see only outfits that include it
- Tap any outfit for **large photos**, the rating ring, **shoe colors** (formal shoes, sneakers, sandals/slides), the best jacket, and an optional AI review

### 🎨 Studio
Pick any piece of clothing from the photo strip and swipe through everything that goes with it, ranked. Picking a jacket shows the outfits it suits best.

### 🧺 Wardrobe
Your digital closet, split into **Shirts**, **Pants** and **Jackets**.

| Section | Types |
|---|---|
| Shirts | T-shirt, Polo, Button-up |
| Pants | Jeans, Trousers, Chinos, Cargo, Joggers, Shorts |
| Jackets | Blazer, Leather, Bomber, Hoodie, Denim jacket, Puffer, Coat |

- Add **many photos at once**. They appear instantly while the AI scans in the background
- **Tap the garment** in the photo to pick its exact color
- Support for **two-color pieces** (striped, checked, color-blocked)
- A **duplicate warning** if a new photo looks like one you already added
- **Clean up with AI** to re-scan and crop older photos

### 🛍️ Shop
Not sure what to buy next? FitCheck tests common colors against your wardrobe and shows the **top 4 shirt colors and top 4 pants colors** that would unlock the most new outfits rated 7+. It also has a **Test any two colors** tool, so you can check a combination before you buy anything.

### ⚙️ Settings
Skin tone and season preferences, AI provider, haptic feedback, **backup and restore**, a replay of the welcome tour, and reset.

---

## 🤖 Turn on AI scanning (optional, free)

FitCheck works without AI using a simpler color guess. For the best results, add a free Google Gemini key:

1. Open **https://aistudio.google.com/apikey** and sign in with a Google account.
2. Tap **Create API key** and copy it. No credit card is needed.
3. In FitCheck, go to **Settings**, paste it into **Gemini API key**, and tap outside the box.
4. Go to **Wardrobe** and add photos. Each one is scanned automatically.

**What the AI does for each photo**
- Judges the **true fabric color**, correcting for camera lighting (a dark green shirt that looks grey in a photo is read as dark green)
- Names the color, picks the clothing type, and detects solid, striped, checked or printed
- Finds a second color on two-tone garments
- Finds the garment and **crops the photo** to it

> 💡 **About limits:** Google's free tier has per-minute and per-day request caps, and the numbers change over time. If you see *"Free AI limit reached"*, wait about a minute and tap **Scan & crop with AI** on that item. Adding a few photos at a time works best. You can check your current limits in Google AI Studio.

**Using another AI service?** In Settings, choose **Other** and enter the base URL, a vision-capable model name and a key for any OpenAI-compatible service.

---

## 🧮 How the rating works

FitCheck does not guess. Every outfit is scored by a color engine that looks at:

- **Color families:** neutrals (black, white, greys), earthy tones (navy, brown, beige, olive and similar), denim, and bright colors, with rules for which families pair well
- **Hue, lightness and saturation:** tonal pairs (like light blue with navy) score well, while two loud colors or clashing hues are penalized
- **Garment formality:** a T-shirt with joggers scores poorly for the office, while a button-up with trousers scores well
- **Occasion:** Office favors calm colors, Wedding favors rich or classic tones, Eid favors light colors, Casual is relaxed
- **Patterns:** two patterned pieces together lose points
- **Second colors** on striped or two-tone pieces
- **Your skin tone and season,** as a small nudge

Rating bands: 🟢 8.5+ great match, 🟩 7+ good match, 🟠 5.5+ okay, 🔴 below that.

The engine is made of rules, so it is not perfect. If a rating looks wrong, open that outfit and tap **Report a wrong rating**. It copies both pieces' colors, types and the score so you can send it to whoever shared the app.

---

## 🔒 Privacy

- Your wardrobe, photos and settings are stored **only on your phone**, inside the browser. There is no account and no server, and nobody else can see your clothes.
- Photos leave your phone **only when AI scanning is on**, and they go straight to Google's Gemini service (or the provider you choose). Free-tier terms can allow providers to use content to improve their products, so check their terms before scanning anything private.
- Your API key stays on your phone and is **never included in backups**.

---

## 💾 Backup and restore

Clearing Safari's website data erases the wardrobe, so back it up now and then.

- **Settings > Export backup** saves a `fitcheck-backup.json` file. On iPhone, a share sheet lets you save it to Files or send it to yourself.
- **Settings > Import backup** loads that file onto any phone. It replaces the current wardrobe after you confirm.

---

## ♿ Accessibility

Photos, buttons, cards, pop-ups and rating rings have spoken labels for VoiceOver, toggle states are announced, focus is clearly visible, and animations switch off when your phone's **Reduce Motion** setting is on. Haptic feedback is best-effort (iPhone Safari has no standard vibration feature) and can be turned off in Settings.

---

## 🛠️ Troubleshooting

| Problem | What to do |
|---|---|
| App looks old after an update | Fully close it and reopen. If it persists, remove it from the home screen, open the link in Safari and add it again. |
| "Free AI limit reached" | Wait about a minute, then tap **Scan & crop with AI** on that item. Add fewer photos at a time. |
| "The AI key was not accepted" | Re-copy the key into Settings with no extra spaces. |
| "AI model name was not found" | Clear the model box in Settings to use the default. |
| A color looks wrong | Open the item and **tap the garment** in the photo, or pick the color by hand. |
| A photo will not load | Try a JPEG or PNG photo, and tell the person who shared the app which phone and browser you use. |
| Wardrobe disappeared | Safari data was cleared. Restore from your backup file. |
| It will not install on iPhone | You must use **Safari**, not Chrome or an in-app browser. |

---

## 🧩 Under the hood

FitCheck is a single-page **Progressive Web App** with no build step, no framework and no dependencies.

| File | Purpose |
|---|---|
| `index.html` | The whole app: interface, color engine, AI scanning, storage |
| `sw.js` | Service worker, so the app opens fast and works offline |
| `manifest.webmanifest` | Makes it installable with a name and icon |
| `icon-180.png`, `icon-512.png` | App icons |
| `README.md` | This guide |
| `LICENSE` | MIT License |

- **Storage:** IndexedDB in the browser
- **Image work:** the Canvas API (resizing, cropping, color sampling, duplicate fingerprints)
- **AI:** Google Gemini's vision API by default, or any OpenAI-compatible vision service
- **Hosting:** GitHub Pages, free

---

## 📣 Share it

Send this link to friends and family: **https://risalkalwar.github.io/AI-Outfit-App/**

Each person gets their own private wardrobe and uses their own free AI key, so nobody shares limits and nobody sees anyone else's clothes.

### Running your own copy
1. Fork or upload these files to a **public** GitHub repository.
2. Go to **Settings > Pages**, choose the `main` branch and the root folder, and save.
3. Open `https://YOUR-USERNAME.github.io/REPO-NAME/` after a minute.
4. To update, upload new files with the **same file names** to replace the old ones.

> ⚠️ **Never put an API key in the repository.** It is public, and anyone could use the key. Keys belong only in the app's Settings on each phone.

---

## 🗺️ Ideas for the future

- Run color detection and background removal **on the phone** so scanning has no limits and works offline
- Automatic pacing and retry when the free AI limit is hit
- Learn your taste from 👍 / 👎 on outfits
- A "why this score" line on each outfit
- Share an outfit as one image
- Belt and watch color suggestions
- Pakistani wear mode (shalwar kameez, waistcoat, kurta)

Have an idea or found a wrong rating? Tell the person who shared the app, or open an issue on the repository.

---

## 📄 License

FitCheck is open source under the [MIT License](LICENSE). You are free to use, copy, modify and share it, including for your own projects, as long as the license notice stays with it.

---

<div align="center">

Made with care by **Risal Kalwar**

*Dress well. Decide fast.* 👔

</div>
