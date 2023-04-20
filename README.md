# resume

My resume using [JSON Resume](https://jsonresume.org/) and theme [stackoverflow](https://www.npmjs.com/package/jsonresume-theme-stackoverflow).

## Getting Started

1. Init theme and resume.json `npm run init`

2. Start server `npm run serve`

3. Edit resume.json and view changes in browser

4. Export resume.json to pdf `npm run export`

View your pdf in `exports/resume.pdf`

## Themes

Change theme for resume.json.

1. Checkout themes at https://jsonresume.org/themes/

2. Add dependency

   ```bash
   npm install jsonresume-theme-YOUR_THEME
   ```

3. Serve theme `resume serve --theme YOUR_THEME`

4. Export `resume export --theme YOUR_THEME exports/resume.pdf`