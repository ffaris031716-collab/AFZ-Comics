AFZ COMICS WEBSITE — EASY UPDATES

YOUR FILES ARE IN assets.rar

-------------
HOW TO EXTRACT AND SET UP YOUR WEBSITE
-------------

1. Download assets.rar from your GitHub repository

2. Extract the RAR file (use WinRAR, 7-Zip, or any extraction tool)

3. Inside assets.rar you'll find your images:
   - afz-logo.png
   - the-legion-of-muslims.jpg

4. EXTRACT THESE IMAGES to the SAME folder as index.html

   Your folder structure should look like this:
   ├── index.html
   ├── style.css
   ├── script.js
   ├── README.txt
   ├── assets.rar          (the RAR file)
   ├── afz-logo.png         (extracted from RAR)
   └── the-legion-of-muslims.jpg  (extracted from RAR)

-------------
IMPORTANT: IMAGES MUST BE EXTRACTED!
-------------

The images will NOT work while inside the RAR file. 
You must extract them to the same folder as index.html.

-------------
HOW TO ADD YOUR COMIC PDF
-------------

When your comic PDF is finished:

1. Put the PDF in the same folder as index.html

2. Open index.html in a text editor

3. Find this button:
   <button class="disabled" disabled>PDF COMING SOON</button>

4. Replace it with:
   <a class="primary" href="your-file.pdf" target="_blank">READ PDF</a>

   (Change "your-file.pdf" to your actual PDF filename)

-------------
HOW TO ADD MORE COMICS
-------------

To add more comics to the library:

1. Open script.js in a text editor

2. Find the "comics" array and add new entries:

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

3. Save script.js and upload your new cover image

-------------
HOW TO PUBLISH ON GITHUB PAGES
-------------

1. Upload ALL files to your GitHub repository

2. Go to Settings → Pages

3. Under "Branch", select "main" and save

4. Your site will be live at: https://YOUR-USERNAME.github.io/afz-comics/

-------------
FILE LIST
-------------

index.html
style.css
script.js
README.txt
assets.rar
afz-logo.png          (extracted from RAR)
the-legion-of-muslims.jpg  (extracted from RAR)
(any PDF comics you add)

-------------
TIP: 
-------------

This is a STATIC website — everything works without a database. Just upload new files whenever you want to update your site!

© 2026 AFZ Comics
