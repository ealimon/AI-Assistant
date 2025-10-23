# Limon Media AI Assistant Widget

This repository contains the front-end code (HTML, CSS, and JavaScript) for the Limon Media AI Assistant widget.

The widget is designed to be embedded into the Limon Media website (https://www.limon.media/) to answer visitor questions about our digital marketing services.

## Core Services Covered:
- Google Ads Campaigns
- Professional Website Design
- Google Business Profile Optimization

## 🛠️ Implementation Notes

1.  **Backend Required:** This is a **front-end template only**. The logic for generating intelligent answers is handled in the JavaScript's `demoAnswer` function. To make this live, a **Retrieval-Augmented Generation (RAG)** system must be deployed and the `BACKEND_URL` variable must be updated.
2.  **Configuration:**
    * Set `DEMO_MODE = false` once the backend API is live.
    * Update `BACKEND_URL` with the actual API endpoint.
3.  **Embedding:** This widget is intended to be embedded using an `<iframe>` or injected via a small JavaScript snippet on the main website.
