# NoteWise — AI Note Generator frontend

A responsive frontend prototype based on the points in the mini-project presentation: automatic note preparation, text summarization, key-point extraction, multiple note styles, editing, searching, saving and exporting notes.

## Run

Open `index.html` in a modern browser. The app uses browser storage and needs no build step.

## Current prototype behavior

The app accepts pasted text or `.txt` / `.md` uploads, then creates a basic extractive summary and key-point list in the browser. Notes can be edited, searched, saved locally and exported as Markdown. No text is sent to a server.

The presentation also mentions NLP-based AI processing, translation, PDFs/documents, spoken content and MySQL. Those require a backend and service integrations; they are not implemented by this static frontend. The current summarizer is a lightweight demo, not a production AI model.
