

# 🛡️ Cyber Defense Lab

### Explore cybersecurity. Learn through practical examples. Build safer digital habits.

[🌐 **Open the Live Website**](https://cyber-defense-lab-site.vercel.app/ )

![Cybersecurity project](https://img.shields.io/badge/Project-Cybersecurity-0f766e?style=for-the-badge ) ![Beginner friendly](https://img.shields.io/badge/Level-Beginner%20Friendly-2563eb?style=for-the-badge ) ![Live](https://img.shields.io/badge/Status-Live-16a34a?style=for-the-badge )


*A beginner-friendly website and Jupyter notebook for exploring defensive cybersecurity.*



---

## Quick Navigation

- [About](#about)
- [Features](#features)
- [Project Files](#project-files)
- [Open the Website](#open-the-website)
- [Run the Notebook](#run-the-notebook)
- [Deployment](#deployment)
- [Safety Notes](#safety-notes)

## About

- Cyber Defense Lab introduces cybersecurity topics through a simple website and a companion learning notebook.
- It is a learning project, not a professional security audit tool. Dashboard figures are examples, not live measurements.
- The live website is available at [cyber-defense-lab-site.vercel.app](https://cyber-defense-lab-site.vercel.app/ ).

## Features

- Explore **12 defensive security topics**, including web, account, cloud, and network security.
- Try the basic Web Scanner, which checks selected website security headers.
- Open the optional notebook for learning activities and eight example CSV exports.
- See a shield logo and matching browser-tab icon.

## Project Files

- `CyberDefenseLab.html` — website; open it in a browser.
- `CyberDefenseLab.ipynb` — learning notebook; open it with JupyterLab.
- `CyberDefenseLab_Project_Report.docx` — project report.
- `requirements.txt` — packages used by the notebook.
- `README.md` — this guide.

## Open the Website

- Open `CyberDefenseLab.html` in Chrome, Edge, Firefox, or Safari.
- No installation is needed to view the website.

## Run the Notebook

- Install Python 3.9 or newer, then open a terminal in the project folder.
- Create a virtual environment:

  ```bash
  python -m venv .venv
  ```

- Activate it:
  - macOS/Linux: `source .venv/bin/activate`
  - Windows PowerShell: `.venv\Scripts\Activate.ps1`
- Install the packages and start JupyterLab:

  ```bash
  python -m pip install -r requirements.txt
  jupyter lab
  ```

- Open `CyberDefenseLab.ipynb` in the browser tab that JupyterLab opens.
- The notebook’s live web check and optional dataset download are off by default.

## Deployment

- The website is hosted on Vercel: [https://cyber-defense-lab-site.vercel.app/](https://cyber-defense-lab-site.vercel.app/ ).
- To publish the source on GitHub, create a repository and upload the four project files listed above plus this README.
- To connect GitHub updates to the existing Vercel project, open **Vercel → cyber-defense-lab-site → Settings → Git** and connect the repository.
- For the website to open at the main Vercel address, the deployed site needs an `index.html` homepage. If required, copy `CyberDefenseLab.html` to `index.html` after extracting the files.
- Vercel and GitHub host the website; they do not run the notebook.

## Safety Notes

- Scan only websites you own or have permission to check.
- Browser checks may not be able to read every security header; an unreadable setting is not proof that it is missing.
- Review notebook-generated CSV files before sharing them.
- Never upload passwords, access keys, or confidential information.

## Author

- **Vaishnavi** — creator of Cyber Defense Lab.
- **Live project:** [Open the website](https://cyber-defense-lab-site.vercel.app/ )


