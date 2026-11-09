SEBASTYAN NOVA PRAMUNEGARA — PORTFOLIO
Final performance-refined static website
Technology: Vanilla HTML, CSS, JavaScript
Deployment target: Vercel (static)

CONTENTS
- index.html
- assets/images/*.webp
- vercel.json

PERFORMANCE WORK INCLUDED
1. Extracted embedded Base64 artwork into separate WebP assets.
2. Added preload for the hero/profile image and retained lazy loading for below-the-fold artwork.
3. Added intrinsic image dimensions to reduce cumulative layout shift.
4. Added image decoding hints and responsive image sizing.
5. Added font preconnect and font-display swap through Google Fonts URL.
6. Capped canvas device-pixel-ratio and adapted star particle count to viewport width.
7. Limited starfield rendering to approximately 30 frames per second.
8. Paused canvas animations when the document is hidden; lanyard animation also pauses outside the viewport.
9. Respected prefers-reduced-motion and reduced-transparency preferences.
10. Applied content-visibility to below-the-fold sections and reduced blur intensity on smaller screens.
11. Added a 2 MB image upload limit and MIME type check to the demo guestbook to reduce memory pressure.
12. Added basic Open Graph metadata and theme metadata.
13. Kept all artwork paths relative so the site works from the deployment root and standard preview environments.

DEPLOY TO VERCEL
1. Extract this ZIP into a folder.
2. Import the folder/repository into Vercel, or deploy the extracted folder using Vercel CLI.
3. Framework Preset: Other.
4. Build Command: leave empty.
5. Output Directory: . (root).
6. Install Command: leave empty.
7. Deploy.

IMPORTANT FUNCTIONALITY NOTES
- Contact form remains a front-end demo and does not send email or store messages.
- Guestbook remains browser-session/demo functionality and is not backed by a database.
- Music player controls remain a visual demo; they do not play audio. The Spotify link opens Spotify.
- Do not describe these demo functions as production-ready backend services without connecting a trusted service/API and adding server-side validation.

VALIDATION
- JavaScript syntax checked with Node.js.
- ZIP structure and local asset references checked.
- This package has not been deployed to the user's Vercel account, and no real-device/Lighthouse run can be claimed from this build environment. After deployment, test at 320, 375, 768, 1440 and 1920 px and run Lighthouse/PageSpeed Insights.
