# Behind the Green — Your First Month as a Leader

An original, illustrated leadership story for CCGL9079. You become Alex, a newly promoted team leader, make two decisions, and see their consequences unfold over time. Fictional events connect to sourced cases at Wells Fargo, Netflix and Ford.

The revised story establishes Alex’s responsibilities before the first meeting. Choices are written as things a leader might say. Full-screen consequence scenes show leaderboards, unsent messages, customer complaints, billing errors and team responses. A harmful choice ends with a “Try again” button. Each case has a concise explanation, visual comparison and practical takeaways. The optional notebook separates the two lessons from the supporting sources.

## Run

Serve `dist` over HTTP. No build step is required. For example: `python -m http.server 8000 --directory dist`. JavaScript modules need an HTTP server rather than opening index.html directly.

## GitHub Pages

The downloadable ZIP contains the contents of dist at its root. Upload the extracted files, including vendor and .nojekyll, into a GitHub repository. In Settings > Pages, select Deploy from a branch, then the main branch and /(root). GitHub provides the github.io address after deployment. This package is ready for GitHub Pages; this project has not been published to a GitHub account.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Edit

- dist/content.js: consequence scenes, cases, lessons and citations.
- dist/game.js: character setup, dialogue, decisions and navigation.
- dist/style.css: responsive layout and scene animations.
- dist/world.js: original 3D office using bundled Three.js.
- dist/office-canvas.js: isometric fallback for browsers without WebGL.
- dist/research.html: standalone reading version of lessons and sources.

## Experience

The direct route is intended for about four minutes, depending on reading speed. Replaying alternate choices and reading sources takes longer. There is no forced timer. Keyboard users can press 1 or 2 to choose an answer. Reduced motion is respected. Sound is optional; no audio autoplays. Character choices are cosmetic. Names and decisions are not stored or sent to a server.

All Clover Studio characters, dialogue and outcomes are fictional. Real-company examples are labelled and linked. The visual office and characters are original, not extracted from Animal Crossing. Netflix’s description is treated as its stated culture, not proof of universal psychological safety. The Ford case illustrates changes in reporting, not controlled evidence of performance improvement.

Three.js is MIT licensed; see vendor/THREE-LICENSE.txt. Optional Google Fonts fall back to local fonts.

Keep the course submission anonymous. Add group identifiers only to the separate submission materials required by the course.
