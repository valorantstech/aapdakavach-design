Aapda Kavach design demo (Phoenix Software)
===========================================

What this is
  A clickable design prototype. All data is sample data. Nothing is saved.

How to host it
  Upload the WHOLE folder, keeping every file in the same folder, to any
  static web host. Open index.html. It starts at the sign-in page.

  Amazon S3: create a bucket, upload all files, turn on
  "Static website hosting" with index document index.html, and allow
  public read (or put CloudFront in front of it).
  .html files must be served as text/html and support.js as
  text/javascript. The AWS console and CLI do this by default.

To try it on your own computer
  Open a terminal in this folder and run:
      python3 -m http.server 8080
  Then open http://localhost:8080 in Chrome or Edge.
  Opening the files by double-click does NOT work.

Notes
  - Needs an internet connection for the fonts (Google Fonts).
  - Best in Chrome or Edge on a laptop or desktop screen.
  - Sign in: press either sign-in button, then "Verify and open the console".
    No user name or password is needed.
  - The Dark / Light button at the top right switches the theme.
