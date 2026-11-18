# Sign Documents

A simple single-page app for signing documents in the browser.

- Upload a PDF, PNG or JPG
- Draw a signature, or type one in a handwriting font
- Add initials and text, such as today's date
- Click to place, drag to move, pull the corner to resize
- Download the signed PDF

Everything runs in the browser. Files are never uploaded anywhere. Saved signatures are kept in the browser's localStorage.

## Run it

Open `index.html` in a browser, or host the file anywhere that serves static files (GitHub Pages, Vercel, S3).

The app uses pdf.js and pdf-lib from cdnjs.

Inside Claude, the app downloads through Claude's `downloads` capability. Anywhere else, it falls back to a normal browser download.
