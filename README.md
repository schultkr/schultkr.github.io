# Maintenance Guide: Christoph Schult Website
**Academic Portfolio for Macroeconomics, Energy Markets, and Climate Change Research.**

This website is hosted via GitHub Pages at [schultkr.github.io](https://schultkr.github.io) and powered by the Academic Pages Jekyll template.

## Quick Content Updates
Most day-to-day updates involve editing Markdown files in specific directories:

* **Biography & Sidebar:** Edit `_config.yml` to update your role at IWH, contact info, or social links.
* **Research/Publications:** Add new `.md` files to the `_publications/` folder.
* **Teaching:** Update course info in the `_teaching/` folder.
* **Talks:** Add presentation details to the `_talks/` folder.
* **Files:** Upload PDFs or CVs to the `files/` directory to link them in your pages.

## Triggering Website Updates
The deployment process is automated through **GitHub Actions**:
1.  **Commit** your changes to the `master` branch.
2.  Navigate to the **Actions** tab in this repository.
3.  Monitor the "Automated update" workflow. Once it shows a green checkmark, your changes are live.

## Local Development & Preview
To preview changes before they go live, you can run the site locally.

### Using VS Code (Recommended)
This repository includes a **Dev Container** for easy setup:
1.  Open the folder in **VS Code**.
2.  When prompted, click **"Reopen in Container"**.
3.  The site will automatically host at `http://localhost:4000` with live-reload enabled.

### Using Docker
If you have Docker installed, run:
```bash
chmod -R 777 .
docker compose up
