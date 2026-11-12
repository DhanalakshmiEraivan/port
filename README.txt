QUADRAFROYN SOLUTIONS — PREMIUM STANDALONE WEBSITE

RUN
1. Extract the complete ZIP archive.
2. Keep index.html, assets/, and videos/ together in the same folder.
3. Open index.html in a modern browser, or serve the folder with any static web server.

MEDIA
- assets/hero-poster.svg and assets/cta-poster.svg are included local visual fallbacks.
- The optional videos/hero.mp4 and videos/cta.mp4 files were not present in the supplied source archive.
- The page attempts to load those optional files and gracefully falls back to the included local SVG artwork when they are unavailable.
- To add your own videos, place MP4 files at the exact paths above (H.264 video + AAC audio, muted autoplay-friendly, optimized loop).

EXTERNAL RESOURCES
Google Fonts and the existing editorial photography use external URLs and therefore require internet access. The core page layout, navigation, animations, icons, and fallback artwork are local.

NOTES
- No build step or framework is required.
- Article routes are supported by the included client-side article renderer; on static hosting, configure unknown /insights/* paths to fall back to index.html.
