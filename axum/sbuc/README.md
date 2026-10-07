# SBUC
Simple Bookmark Url Collection
- A mini backend to save and categorize web links or API endpoints.

``
Operations:

    POST /bookmarks — Save a link.

    GET /bookmarks — List all bookmarks.

    GET /bookmarks?category=rust — Filter bookmarks by category using the Query extractor.

    DELETE /bookmarks/:id — Delete a bookmark.