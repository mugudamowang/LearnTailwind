## floder
- public : put in web server
- - s

## Steps
1. build tailwindcss source file in public floder. ( use@1.4.6 )
   - to install `npm install tailwindcss`
   - vscode built-in css validate unknown tailwindcss's rule, so use extension like `vscode-stylelint` and setting like this
   ```bash
      "css.validate": false, // Disable css built-in lint
      "stylelint.enable": true, // Enable sytlelint
   ```
2. add html template to the page
3. test tailwind's text & font-weight
4. use padding and margin in taiwind
5. tailwindcs config setting;
   - just run `npx tailwindcss init --full ` to load a complete list of configuration
   - change value in tailwindcss.config.js will automatic process in styles.css, you just need to rebuild it, in this project, `npm run build-css`
   - it's not recommand to custom in default config.js, use new congfig without --full
   `npx tailwindcss init`
6. use custom font
   - import Nunito font style in tailwind.config.js
   - use in class
7. use flex layout
8. use media query to make website responsive in tailwind
   - setting custom sizes in tailwindcss.config.js
   - usage: `sm:text-red-500`, it means make text red when screen in small size
9.  make cards
   - make img fill and something other componets
   - make a badge
   - use @applay directive
10. add a grid layout comfortably
11. make a button.
   - use @apply to organizate common part of style
12. add icons