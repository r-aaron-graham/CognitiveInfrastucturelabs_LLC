# Cognitive Infrastructure Labs website

A responsive landing page for the Princeton, WV consultancy. It describes AI and automation services for small businesses, explains the engagement process, and gives visitors a way to request a discovery call.

## Preview locally

Clone this repository and open [index.html](index.html) in a web browser. You can also start a local server from the repository root:

```sh
python3 -m http.server 8000
```

Visit `http://localhost:8000/`. The page is plain HTML, CSS, and JavaScript. The logo images are embedded in the HTML. Google Fonts uses a network request, with fallback fonts available offline.

## What to verify

- Use the top navigation to jump to each section.
- Narrow the browser window and check that the mobile menu opens and closes.
- Select **Email to Request a Discovery Call**. It opens a draft in your configured email app with the subject `Discovery call`.

This repository contains the landing page. The service descriptions describe the consultancy’s offerings.
