SELECTED GOODS — Website package

STRUCTURE
  index.html          English version (site root)
  it/index.html       Italian version
  assets/favicon.svg  Favicon (already embedded in the pages)
  assets/symbol-ink.svg / symbol-paper.svg  Symbol, dark and light

Both HTML files are self-contained: fonts, symbol, animations and scripts are embedded.
Upload the whole folder to any static hosting (Netlify, Vercel, GitHub Pages, cPanel...).

DEPLOY
  GitHub Pages via .github/workflows/pages.yml (runs on every push to main).

FORM
  Submissions go through FormSubmit (formsubmit.co) to selectedgoodsmusic@gmail.com.
  The FIRST submission triggers an activation email from FormSubmit to that inbox:
  click the confirmation link once, then all later submissions arrive normally.

TODO
  - Add the real Instagram / SoundCloud links to the footer (removed for now, they were placeholders).

FONTS
  Albert Sans + JetBrains Mono (Google Fonts, SIL Open Font License, free for commercial use).
