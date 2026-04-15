# Macroeconomic Trend & Analysis Dashboard (World in Perspective) 📊

A high-performance analytics platform designed to visualize and track national economic indicators. This dashboard synthesizes complex macroeconomic datasets—including GDP growth trends, fiscal deficits, and unemployment metrics—to provide actionable financial insights.

**🔗 [Live Demo: world-in-perspective.netlify.app](https://world-in-perspective.netlify.app/)**

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=netlify)](https://world-in-perspective.netlify.app/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github)](https://github.com/rohitsangwan2003-bit/Economic-Dashboard-with-Analysis)

## 🚀 Overview

Built with an **"AI-First"** and **"Data-Led"** approach, this project bridges the gap between raw economic data and fundamental analysis. It features a robust **Python engine** to automate data engineering and a modern **TypeScript** frontend for interactive, real-time visualization.

## ✨ Key Features

- **Live Interactive Deployment:** Fully responsive dashboard hosted on Netlify, providing real-time access to macroeconomic trends.
- **Automated Data Pipeline:** Engineered a Python engine to clean, transform, and synthesize raw `.xlsx` macroeconomic records into optimized JSON.
- **Advanced Visualizations:** Features **Radial Perspective Charts**, Metric Cards, and World Maps for intuitive trend analysis.
- **Fundamental Analysis Focus:** Designed specifically to track core metrics like **GDP growth** and **Fiscal Deficits** to evaluate long-term market health.
- **Optimized Performance:** Developed with **Vite** and **Tailwind CSS** for ultra-fast load times and a pixel-perfect user experience.

## 🛠️ Tech Stack

- **Frontend:** TypeScript, JavaScript, Vite, Tailwind CSS
- **Data Engineering:** Python (Pandas, OpenPyXL)
- **Deployment:** Netlify (CI/CD)
- **Infrastructure:** Git, PostCSS, ESLint, npm

## 📂 Project Structure

```text
├── src/                    # Core Dashboard Logic
│   ├── components/         # Modular UI (AICards, Charts, Layouts)
│   ├── data/               # Processed economics.ts and JSON datasets
│   ├── utils/              # AI logic and data transformation helpers
│   └── types/              # TypeScript interfaces for economic perspectives
├── generate_data.py        # Main Python pipeline for dataset synthesis
├── inspect_excel.py        # Data validation and cleaning script
├── convert_data.py         # Utility script for raw XLSX to JSON conversion
├── tailwind.config.js      # Styling configuration
└── vite.config.ts          # Build and optimization settings
