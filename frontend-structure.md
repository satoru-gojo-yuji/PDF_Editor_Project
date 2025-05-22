# Frontend Directory Structure

```
├── public/                   # Static files (index.html, favicon, etc.)
├── src/
│   ├── components/           # Reusable React components
│   │   ├── PDFUploader.js    # Likely handles PDF file upload
│   │   ├── PDFViewer.js      # Renders PDF for viewing
│   │   ├── PDFEditor.js      # UI for editing PDF (text, annotations, etc.)
│   ├── pages/
│   │   └── EditorPage.js     # Page component, likely uses above components
│   ├── services/
│   │   └── api.js            # Handles API communication with backend
│   ├── App.js                # Main application component
│   └── index.js              # Entry point for React app
├── package.json              # Project metadata and dependencies
```
