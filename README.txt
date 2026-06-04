=======================================================
  AMIR AZIZ PORTFOLIO WEBSITE — SETUP GUIDE
=======================================================

FOLDER STRUCTURE
-----------------
portfolio/
├── index.html              ← Main website file (open this in browser)
├── README.txt              ← This guide
│
├── images/                 ← ADD YOUR IMAGES HERE
│   ├── amir-profile.jpg         (Your profile/about photo)
│   ├── flood-project.jpg        (Project 1 screenshot)
│   ├── vehicle-tracking.jpg     (Project 2 screenshot)
│   ├── football-tracking.jpg    (Project 3 screenshot)
│   ├── infra-detection.jpg      (Project 4 screenshot)
│   ├── playstore-analysis.jpg   (Project 5 screenshot)
│   ├── classification.jpg       (Project 6 screenshot)
│   ├── detection-dashboard.jpg  (Project 7 screenshot)
│   └── pose-estimation.jpg      (Project 8 screenshot)
│
├── videos/                 ← ADD PROJECT DEMO VIDEOS HERE (optional)
│   ├── flood-demo.mp4
│   ├── vehicle-demo.mp4
│   └── ...
│
└── documents/              ← ADD YOUR PDFs HERE
    ├── Amir_Aziz_Resume.pdf
    ├── Amir_Aziz_Transcript.pdf
    ├── Amir_Aziz_Degree.pdf
    └── Amir_Aziz_NCAI_Letter.pdf


=======================================================
  HOW TO ADD YOUR PROFILE PHOTO
=======================================================

1. Name your photo:  amir-profile.jpg
2. Put it in the "images/" folder
3. Done! The website will show it automatically.

Recommended size: 500x500 pixels or larger (square)


=======================================================
  HOW TO ADD PROJECT IMAGES
=======================================================

Simply put your screenshots in the "images/" folder
with exactly these names:

  flood-project.jpg
  vehicle-tracking.jpg
  football-tracking.jpg
  infra-detection.jpg
  playstore-analysis.jpg
  classification.jpg
  detection-dashboard.jpg
  pose-estimation.jpg

If an image file is missing, the website will automatically
show a colored gradient background with an emoji instead.
So missing images will NOT break anything!

Recommended size: 800x450 pixels (16:9 ratio)
Supported formats: .jpg, .jpeg, .png, .webp, .gif


=======================================================
  HOW TO USE PROJECT VIDEOS INSTEAD OF IMAGES
=======================================================

Open index.html in Notepad or any text editor.
Find this line (example for project 1):

  <img src="images/flood-project.jpg" alt="Flood Segmentation"

Replace that whole <img ...> block with:

  <video autoplay muted loop playsinline
         style="width:100%;height:100%;object-fit:cover;">
    <source src="videos/flood-demo.mp4" type="video/mp4">
  </video>


=======================================================
  HOW TO ADD YOUR DOCUMENTS (PDF FILES)
=======================================================

1. Put your PDF files in the "documents/" folder
2. Name them exactly:
     Amir_Aziz_Resume.pdf
     Amir_Aziz_Transcript.pdf
     Amir_Aziz_Degree.pdf
     Amir_Aziz_NCAI_Letter.pdf

3. Done! The Documents section will link to them.

If a PDF is not ready yet, the link will just not work
until you add the file. Nothing else breaks.


=======================================================
  HOW TO OPEN THE WEBSITE
=======================================================

LOCALLY (to test on your computer):
  Just double-click index.html to open in your browser.
  Internet is needed for fonts and icons (Font Awesome).

TO HOST ONLINE (free options):

  OPTION 1 — Netlify (easiest, recommended):
  1. Go to https://netlify.com and sign up free
  2. Drag the entire "portfolio" folder onto the page
  3. Your site goes live instantly with a free URL!

  OPTION 2 — GitHub Pages:
  1. Go to https://github.com and create a repository
  2. Upload all files (keeping the folder structure)
  3. Go to Settings → Pages → Enable GitHub Pages
  4. Your site is live at: username.github.io/portfolio

  OPTION 3 — Vercel:
  1. Go to https://vercel.com and sign up free
  2. Import your GitHub repository
  3. Done! Auto-deploys on every update.


=======================================================
  CONTACT LINKS ALREADY SET UP
=======================================================

  Email:    amiraziz.uet@gmail.com
  WhatsApp: https://wa.me/923049274032
  GitHub:   https://github.com/AmirAziz1221
  LinkedIn: https://www.linkedin.com/in/amir-aziz-2868aa266/
  Fiverr:   https://www.fiverr.com/sellers/amiraziz1221
  Kaggle:   https://www.kaggle.com/amirazizdatascience
  Discord:  https://discord.gg/AE7wZjwH

All social icons use Font Awesome (loaded from CDN).
Internet connection required for icons to appear.


=======================================================
  NEED HELP?
=======================================================

  WhatsApp: +92 304 9274032
  Email:    amiraziz.uet@gmail.com

=======================================================
