# 🛠️ INJAAZ Report Dashboard System

[![Deployment Status](https://img.shields.io/static/v1?label=Render&message=LIVE&color=success)](https://[YOUR-RENDER-SERVICE-NAME].onrender.com)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A modern, vertical sidebar dashboard and field reporting system built using **Flask** (Python) and **Bootstrap 5**. The application allows field technicians to generate standardized Site Visit (HVAC/MEP) and Site Assessment (Cleaning) reports via a user-friendly web interface.

## 🚀 Live Application

The dashboard is hosted using **Render's Free Tier**, which automatically builds the Docker image and scales down to zero when idle for optimal cost savings.

* **Live URL:** `https://[YOUR-RENDER-SERVICE-NAME].onrender.com` (Update this placeholder after deployment)

---

## ✨ Features

* **Modular Reporting:** Dedicated Blueprints for two distinct report types: Site Visit (HVAC/MEP) and Site Assessment (Cleaning).
* **Intuitive Dashboard:** Quick access to all available forms via a vertical sidebar navigation.
* **Custom Branding:** Includes the INJAAZ logo prominently in the sidebar.
* **Production Ready:** Deployed using **Gunicorn** and containerized with **Docker** for a stable production environment.
* **Secure File Serving:** Dedicated route for secure download of generated report files (e.g., PDFs).

---

## 💻 Local Setup & Development

To run this application on your local machine for development or testing, follow these steps:

### 1. Prerequisites

You must have **Python 3.11+** installed on your system.

### 2. Clone the Repository

```bash
git clone [https://github.com/](https://github.com/)[YOUR-GITHUB-USERNAME]/injaaz-reports-system.git
cd injaaz-reports-system
