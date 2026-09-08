# Day 39 — PDF Splitter & Merger

## Project
**PDF Splitter & Merger**

Day 39 focused on building a polished browser-based PDF utility that helps users split PDF documents into smaller files and merge multiple PDFs into one document.

## Objective

The goal was to create a professional, beginner-friendly PDF tool with:

- PDF upload and drag-and-drop support
- Automatic page-count detection
- Visual PDF page previews
- Custom page-range splitting
- Multiple split ranges in one operation
- Split-every-page functionality
- Multiple PDF uploads for merging
- Drag-and-drop PDF reordering
- File and page-count statistics
- Processing progress indicators
- Downloadable processed PDFs
- Responsive design
- Dark/light mode
- Keyboard shortcut support
- Client-side PDF processing

## Application

The application was created as a single HTML file:

`pdf-splitter-merger.html`

The interface contains two main tools:

### 1. PDF Splitter

Users can:

- Upload a PDF.
- See the total number of pages.
- Preview page thumbnails.
- Enter page ranges such as `1-3, 5, 8-10`.
- Create multiple split ranges in one operation.
- Validate invalid page ranges.
- Split every page into individual PDF files.
- Generate and download the resulting PDFs.

### 2. PDF Merger

Users can:

- Upload multiple PDF files.
- View each file's name and page count.
- Reorder files before merging.
- Remove individual files.
- View total files, pages, and source size.
- Merge the selected PDFs.
- Download the final merged PDF.

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- PDF.js for PDF rendering and page inspection
- pdf-lib for PDF creation and merging
- Browser File APIs
- Drag-and-drop APIs
- Blob URLs for local downloads

## Key Learning

### Browser-based document processing

PDF operations can be performed directly in the browser using JavaScript libraries. This makes it possible to process user documents without sending them to a backend server.

### PDF page ranges

A useful PDF splitter needs strong input validation. Expressions such as:

`1-3, 5, 8-10`

can represent multiple output documents and must be checked against the actual page count.

### PDF merging

The order of input documents matters. A drag-and-drop interface makes the final merge order easy to understand and control.

### User experience

Document-processing tools should clearly communicate:

1. What file was uploaded.
2. How many pages/files are being processed.
3. What operation will happen.
4. Whether the input is valid.
5. When processing is complete.
6. Where the resulting file can be downloaded.

### Client-side privacy

Keeping PDF processing in the browser can reduce privacy concerns because the document does not need to be uploaded to a custom backend.

## Testing Completed

The application was designed to test:

- PDF upload
- Page detection
- Page thumbnail rendering
- Page-range validation
- PDF splitting
- Multiple split ranges
- PDF merging
- PDF reordering
- Processed PDF downloads
- Responsive layout
- Dark/light theme
- Drag-and-drop interactions

## Challenges

One important implementation challenge was combining PDF preview functionality with PDF generation in a single-page application. PDF.js handles reading and rendering PDF documents, while pdf-lib handles creating and combining PDF files.

Another consideration is offline support. The application itself contains the UI and JavaScript logic in one HTML file, but external PDF library scripts must be made locally available for completely offline operation. For a fully offline distribution, PDF.js and pdf-lib should be downloaded and bundled or referenced from local files.

## Result

Day 39 produced a premium-style **PDF Splitter & Merger** interface focused on privacy, usability, responsive design, and browser-based document processing.

## Takeaways

- Learned how to inspect PDF page counts in the browser.
- Learned how to render PDF pages as visual previews.
- Learned how to validate user-defined page ranges.
- Learned how to create new PDFs from selected pages.
- Learned how to merge multiple PDFs in a chosen order.
- Improved understanding of drag-and-drop UI patterns.
- Practiced creating progress feedback for longer operations.
- Reinforced the importance of privacy-focused client-side processing.
- Improved single-file HTML application architecture.

## Day 39 Status

**Completed:** PDF Splitter & Merger application

**Main file:** `pdf-splitter-merger.html`

**Next step:** Upload the application, screenshots, processed PDFs, and learning notes to the `Day39` folder in the GitHub repository and commit the changes.
