Highlight Extractor PWA

A lightweight Progressive Web App to extract highlighted text and generate PDF files.

Features

- Extract highlighted text
- Generate PDF documents
- Installable on mobile devices
- Offline support using Service Workers
- Cached resources for offline access

Tech Stack

HTML • CSS • JavaScript • PWA • Service Workers

Project Structure

highlight-text-pdf/
├── index.html
├── manifest.webmanifest
├── sw.js
├── icon-192.png
├── icon-512.png
└── apple-touch-icon.png

Deployment

Hosted using Netlify.

1. Extract the ZIP file.
2. Upload the project folder to "Netlify Drop" (https://app.netlify.com/drop).
3. Open the generated HTTPS URL.

Offline Support

The Service Worker caches essential resources during the first online visit, allowing the app to work offline afterward.

Note: Offline functionality depends on required resources being cached successfully.
