# Jackson Hole Guys Weekend

A static site. No build step.

## Deploy to Vercel

1. Open a terminal in this folder.
2. Run `npx vercel` and follow the prompts (log in, accept the defaults). This gives you a preview link.
3. Run `npx vercel --prod` to publish it at the main address.

To update the site later, replace the files and run `npx vercel --prod` again.

## Notes

- Picks, crew and expenses save in each visitor's own browser. The shared crew sync only works in the Claude version.
- The page asks search engines not to list it (`noindex`). Remove that line from `index.html` if you want it to be found.
- The 3D model loads three.js from cdnjs and fonts from Google Fonts.

## Also in this repo

`coeur-dalene/` is a second static trip page (Coeur d'Alene, Idaho), deployed as a separate Vercel project that uses that folder as its root directory.
