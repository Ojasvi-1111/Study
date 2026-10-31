# Study

Daily study PDF launcher, served with GitHub Pages.

- `index.html`: the site (design and features). The PDF agent never edits it.
- `data/today.json`: today's PDF, overwritten daily by the PDF agent.
- `data/history.json`: all PDFs, newest first; the agent adds one entry a day.

Entry format:
{"date": "YYYY-MM-DD", "title": "Short title", "url": "https://drive.google.com/file/d/<FILE_ID>/view", "pages": 70}
