# md-share storage backend

This repository stores encrypted documents for md-share.

All document bodies are fully encrypted client-side using AES-256-GCM. The keys never leave the client.
Plaintext title and description metadata are stored in the JSON files to support rich link previews and search.
