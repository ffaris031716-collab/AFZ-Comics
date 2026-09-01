AFZ COMICS WEBSITE — EASY UPDATES

All images are in the same folder as index.html (no subfolders needed).

YOUR COMIC COVER:
the-legion-of-muslims.jpg

YOUR LOGO:
afz-logo.png

-------------
HOW TO ADD YOUR PDF COMIC
-------------

When your comic PDF is finished:

1. Put the PDF in the same folder as index.html

2. Open index.html in a text editor (like Notepad)

3. Find this button:
   <button class="disabled" disabled>PDF COMING SOON</button>

4. Replace it with:
   <a class="primary" href="your-file.pdf" target="_blank">READ PDF</a>

   (Change "your-file.pdf" to your actual PDF filename)

-------------
HOW TO UPDATE IMAGES
-------------

To change the logo or comic cover:

1. Upload your new image to the same folder as index.html

2. Make sure the filename matches what's in the HTML

3. The current filenames are:
   - afz-logo.png (for the logo in the header)
   - the-legion-of-muslims.jpg (for the hero background and comic cover)

-------------
HOW TO ADD MORE COMICS
-------------

To add more comics to the library:

1. Open script.js in a text editor

2. Find the "comics" array:

   const comics = [
     {
       title: "Your First Comic",
       description: "Add your comic cover and PDF here.",
       cover: "",
       pdf: ""
     }
   ];

3. Add a new comic like this:

   const comics = [
     {
       title: "The Legion of Muslims",
       description: "The first chapter of our epic saga.",
       cover: "the-legion-of-muslims.jpg",
       pdf: "legion-issue-1.pdf"
     },
     {
       title: "New Comic Title",
       description: "Description of your new comic.",
       cover: "new-comic-cover.jpg",
       pdf: "new-comic.pdf"
     }
   ];

4. Save script.js and upload your new cover image

-------------
HOW TO PUBLISH ON GITHUB PAGES
-------------

1. Upload ALL files (index.html, style.css, script.js, README.txt, and all images) to your GitHub repository

2. Go to Settings → Pages

3. Under "Branch", select "main" and save

4. Your site will be live at: https://YOUR-USERNAME.github.io/afz-comics/

-------------
FILE LIST (All in one folder)
-------------

index.html
style.css
script.js
README.txt
afz-logo.png
the-legion-of-muslims.jpg
(any PDF comics you add)

-------------
TIP: 
-------------

This is a STATIC website — everything works without a database. Just upload new files whenever you want to update your site!

© 2026 AFZ Comics
