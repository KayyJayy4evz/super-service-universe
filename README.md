# Super Service World

Static site deployed on Netlify from `main`. Game data lives in Firebase (Firestore).

- `index.html`: the game
- `how-xp.html`, `recap.html`, `pages.css`: How XP Works and Monthly Recap pages
- `tailwind.css`: prebuilt styles. If you add new Tailwind classes to `index.html`, rebuild:
  `npx tailwindcss@3.4.17 -i in.css -o tailwind.css --minify --content index.html`
  (where `in.css` contains the three `@tailwind` lines)
- `firestore.rules`: database rules (paste into the Firebase console to apply)
- `sounds/`: original 8-bit sound effects
