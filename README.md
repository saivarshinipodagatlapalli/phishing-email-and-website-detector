# Phishing Email & Website Detector — Cybersecurity Detection System

A multi-layered cybersecurity intelligence engine for analyzing suspicious emails, phishing lures, deceptive URLs, and rogue media streaming/mirror networks.

Frontend and Python backend are connected. Flask serves `backend/static/index.html` and the frontend interacts with `/api/analyze`.

## Key Capabilities
- **Advanced Cybersecurity Detection Engine v2.0**:
  - Shannon Entropy calculation for detecting algorithmically generated domains (DGA).
  - Typosquatting & homograph brand spoofing analysis (targeting PayPal, Google, Microsoft, Apple, etc.).
  - Illicit streaming, piracy, and unverified mirror network detection (MovieRulz, NetMirror, torrent trackers, etc.).
  - Business Email Compromise (BEC) and executive freemail spoofing detection.
  - Multi-vector threat matrix: Social Engineering Index, Domain Evasion, Credential Theft Exposure, Malware/Malvertising Risk.
  - Cyberpunk-styled neon UI with interactive scan beam animation, dynamic risk gauges, one-click report copying, and print/PDF formatting.

## Run on Windows

Open CMD/PowerShell inside `backend`:

```powershell
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
python ml\train_model.py
python app.py
```

Open **http://127.0.0.1:5000** in your browser.
