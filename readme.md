# Chat Analyzer 🧮

A simple Streamlit app to analyze WhatsApp chat exports. It calculates message statistics, timelines, activity heatmaps, most common words, emoji analysis, and more.

---

## Features ✅

- Top statistics: total messages, words, media, links
- Monthly and daily timelines with plots
- Activity maps (day/month heatmaps)
- Most busy users and most common words
- Emoji analysis and visualizations
- Simple UI with sidebar to upload chat file and select user

---

## Getting started 🔧

Clone the repository and create a virtual environment:

Windows (PowerShell):

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
pip install -r requirements.txt
streamlit run app.py
```

macOS / Linux:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
```

---

## Usage 💡

1. Export a WhatsApp chat (without media) and upload the `.txt` file using the sidebar.
2. Select a user (or "Overall") and click **Show Analysis**.
3. Browse the generated charts and tables.

Note: The app looks for `149376784.jpg` in the project root to show your avatar in the sidebar — add your own image with that filename or change `img_path` in `app.py`.

---

## Development & Tests 🧪

- The core preprocessing is in `preprocessor.py` and analysis helpers are in `helper.py`.
- If tests are added, run them in the venv using `pytest`.

---

## Author ✨

**Samarth gour** — add your email or contact info here if you want people to reach out.

---

## License

This project is available under the terms of the MIT License. See `LICENSE` for details.
