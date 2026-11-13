ONE YEAR OF US — your anniversary gift page
================================================

WHAT'S IN HERE
  One_year_of_us.html   the page itself — open this file to see it
  images/               the cat pictures the page needs (8 frames)
  photos/               your photos go here (6 placeholders for now)
  music/                your song goes here (a silent placeholder for now)

HOW TO OPEN IT
  1. Unzip this folder somewhere on your computer.
  2. Double-click One_year_of_us.html — it opens in your browser.
  3. Keep the images, photos and music folders next to the html file,
     or the cat and photos won't load.

HOW TO ADD YOUR PHOTOS
  Easiest way: open the photos folder and replace photo1.jpg … photo6.jpg
  with your own pictures, keeping the same file names. That's it — the
  page will pick them up automatically.
  Or: put your pictures in the photos folder under any name, then open
  One_year_of_us.html in a text editor, find the CONFIG block near the
  top, and change the src lines, e.g. src: "photos/our-trip.jpg".
  You can also change the caption and date under each photo there, and
  add more photos by copying a whole { src: ..., caption: ..., date: ... }
  line, or remove one by deleting its line.

HOW TO CHANGE THE TEXT
  Open One_year_of_us.html in any text editor (Notepad, TextEdit, VS Code).
  Near the top is a block marked EDIT THIS BLOCK ONLY. Everything you
  would want to change lives there:
    herName / hisName   the two names
    anniversaryDate     the date you got together, year-month-day
    openingNote         the note under the heart button
    question            the big question ("Do you love me?")
    noLines             what the page says each time she taps NO
    yesLine             what shows after she taps YES
    photosTitle         the title above the photo wall
    letter              to / body / sign — the love letter
  Only change the words inside the "quotes". Keep the quote marks and
  the commas exactly as they are. For apostrophes use ’ (curly), and
  don't type a straight " inside any text. In the letter, just type or
  paste your words between the two ` marks — press Enter for a new
  paragraph, and don't use the ` mark or ${ inside it.

HOW TO ADD YOUR SONG
  Replace music/song.mp3 with your song file, keeping the name song.mp3.
  (The file in there now is 3 seconds of silence — just a placeholder so
  the player has something to point at.) Then set the song title and
  artist in the CONFIG block. If your file has a different name, update
  the file: "music/song.mp3" line to match it.

HOW TO SHARE IT WITH HER
  Zip the whole folder back up and send it, or put the folder on any
  hosting (Netlify Drop, GitHub Pages, etc.) and send her the link.
  Don't send just the html file on its own — it needs the images,
  photos and music folders beside it.

TROUBLESHOOTING
  - Cat or photos don't show: the images/photos folder isn't next to
    the html file. Keep them together.
  - Page looks broken after editing: you probably deleted a quote mark
    or a comma in CONFIG. Undo the last change and try again.
  - No sound when pressing play: the placeholder song is silent on
    purpose. Replace music/song.mp3 with your song.
  - The "together for" counter counts from anniversaryDate in CONFIG.
