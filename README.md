# G3 Seoul Plan · Seoul IDEA Policy Lab (English)

A static HTML, CSS and JavaScript website. No npm installation or build step is required.

## Upload to GitHub
1. Extract the ZIP archive.
2. Upload the extracted files, preserving their folder structure.
3. Keep dist/, vercel.json and README.md at the repository root.
4. For an update ZIP, replace matching files and retain the existing image assets.

## Files
- dist/index.html: Home page
- dist/explore.html: Policy exploration, citizen personas and IDEA workshop
- dist/promotion.html: Promotional content prompt builder
- dist/app.js: Policy data, interface behavior and English prompts
- dist/style.css: Responsive styles
- dist/*.png: Existing visual assets
- vercel.json: Static hosting configuration with dist as the output directory

## Local preview
From this project directory, run:

    python -m http.server 8000 --directory dist

Then open http://localhost:8000.

## English version
All interface text, policy examples, citizen scenarios and generated prompts are in English. Prompts request English output, including image text, dialogue and song lyrics.

- Video: three independently generated 10-second advertisements, each with a distinct concept and complete context. They do not form a connected 30-second story.
- Visual story: one image with six panels in a 3-column by 2-row grid.
- Poster: six distinct design concepts in one comparison image.
- Song: approximately two minutes, with complete lyrics and music settings in one code block.
- Citizen exercise: a persona image and a journey map image.
- IDEA: continue in the same Gemini conversation, retaining earlier context.

Inputs are saved in this browser under the separate seoul-idea-en-v1 localStorage key. Previous Korean-version records are preserved under their original key and are not automatically translated or imported. Gemini responses are not collected automatically.

Policy names and descriptions are English translations for this workshop; goals and plans should not be read as completed outcomes.