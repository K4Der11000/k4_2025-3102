# CVE-2025-3102 Vulnerability Scanner

This tool scans WordPress websites for the SureTriggers user creation vulnerability (CVE-2025-3102).

## Features
- Web interface with hacker-style theme
- Auto account creation detection
- Sound alert when vulnerable
- Report saved as HTML
- Downloadable scan results
- Login protected interface

## How to Run

1. Make sure you have Python 3 and pip installed.
2. Install dependencies:
   pip install flask requests

3. Run the script:
   python app.py

4. Open your browser and go to:
   http://127.0.0.1:5000

5. Login with:
   - Username: admin
   - Password: kader11000

6. Enter the target WordPress site and press "Scan".

## Folder Structure

- `app.py`: Main Flask backend
- `templates/index.html`: Frontend HTML UI
- `static/alert.mp3`: Sound alert file (online)
- `results/`: Saved scan reports in HTML format
