BIRTHDAY SURPRISE — QUICK SETUP
================================

1) Open index.html in a code editor.
2) Search for: EASY CUSTOMIZATION SECTION
3) Change:
   - herName
   - yourName
   - memories text
   - reasons
   - quiz questions/answers
   - finalLetter
   - finalMessage

PHOTOS
------
Put your real photos in the assets folder using these names:
  photo1.jpg
  photo2.jpg
  photo3.jpg
  photo4.jpg
  final-photo.jpg

VOICE MESSAGE
-------------
Record your voice on your phone, export as MP3, rename it to:
  voice-message.mp3
and put it inside the assets folder.

If you do not want audio, set:
  showAudio: false

If you do not want the fake AI section, set:
  showAssistant: false

QUIZ ANSWERS
------------
Each quiz answer is a zero-based option number:
  0 = first option
  1 = second option
  2 = third option
  3 = fourth option

FREE GITHUB PAGES DEPLOYMENT
----------------------------
1) Create a new public GitHub repository, e.g. birthday-surprise
2) Upload everything INSIDE this folder to the repository root.
3) GitHub repo -> Settings -> Pages
4) Source: Deploy from a branch
5) Branch: main / (root)
6) Save.
7) Your link will look similar to:
   https://YOUR-USERNAME.github.io/birthday-surprise/

IMPORTANT
---------
- Music/audio cannot autoplay before a user interaction in most mobile browsers. This app starts after she taps the Begin button, so the experience is browser-friendly.
- Progress is stored only in her browser using localStorage. No database/API is used.
- To test from the beginning, tap Restart.
- Everything is static and can be hosted for free.
