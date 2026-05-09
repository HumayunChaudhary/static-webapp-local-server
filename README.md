# Static Website + Local Server Testing

## Overview

This project is a simple static website built using HTML, CSS, and JavaScript.

It was created to understand how static websites behave when served over a local HTTP server instead of being opened directly from the filesystem.

---

## Key Learning

A key learning from this project is:

> Static websites should be served over HTTP (not `file://`) to accurately simulate real-world browser and web server behavior.

Running a local server helps avoid issues such as:
- Broken JavaScript module loading
- CORS restrictions in browser APIs
- Inconsistent routing behavior

---

## How to Run the Project

Start a lightweight local HTTP server:

```bash
python3 -m http.server 8080
