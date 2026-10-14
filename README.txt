OPENWITHLOVE B8 — PASTEL ANNIVERSARY GIFT BOX

FILES
- index.html: webpage structure
- style.css: design, responsive layout, animations
- script.js: navigation, interactive chocolate and music playback
- config.js: EDIT ALL CUSTOMER PERSONALISATIONS HERE
- assets/photos/: replace sample photo paths with your customer photos
- assets/music/: put the chosen MP3 here

PERSONALISE A CUSTOMER ORDER
1. Open config.js in VS Code.
2. Edit names.recipient and names.sender. (recipient is available for your own text; update opening/letter content where needed.)
3. Change anniversaryDate and the opening/letter/finale text.
4. Replace the memories array titles/captions and image paths.
5. Add customer images inside assets/photos/ and use paths such as assets/photos/memory-1.jpg.
6. Add a licensed/customer-provided MP3 at assets/music/our-song.mp3 and keep music.src as assets/music/our-song.mp3.
7. Test index.html in a browser and deploy the whole folder.

MUSIC
There is deliberately NO visible music control or upload picker on the webpage. Music is configured only in config.js. Browsers block autoplay until the visitor interacts with the page, so playback starts after the first tap/click. If music is not wanted, set music.enabled to false.

PHOTOS
The sample memory image files are placeholders by path only; add your own images using the exact filenames configured in config.js. If a photo is missing, a cute decorative placeholder appears.

NOTES
- This is a faithful functional recreation of the screen sequence visible in the provided short recording, not a copy of any original site's source code.
- Use only music and photos you have permission to use.
- Keep customer photos/messages private; do not commit sensitive files to a public repository without customer permission.
