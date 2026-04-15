# Macroeconomic Trend & Analysis Dashboard 📊

A high-performance analytics platform designed to visualize and track national economic indicators. This dashboard synthesizes complex macroeconomic datasets—including GDP growth trends, fiscal deficits, and unemployment metrics—to provide actionable financial insights.

[![GitHub Repo](https://img.shields.io/badge/GitHub-Economic--Dashboard-blue?logo=github)](https://github.com/rohitsangwan2003-bit/Economic-Dashboard-with-Analysis)
[![Tech Stack](https://img.shields.io/badge/Stack-TS%20%7C%20Vite%20%7C%20Python-orange)](#-tech-stack)

## 🚀 Overview

Built with an **"AI-First"** and **"Data-Led"** approach, this project bridges the gap between raw economic data and fundamental analysis. It features a robust Python backend to automate data engineering and a modern TypeScript frontend for interactive, real-time visualization.

## ✨ Key Features

- **Automated Data Pipeline:** Engineered a **Python engine** to clean, transform, and synthesize raw `.xlsx` macroeconomic records into optimized JSON.
- **Real-Time Visualization:** Interactive dashboard featuring **Radial Perspective Charts**, Metric Cards, and World Maps for intuitive trend analysis.
- **Fundamental Analysis Focus:** Designed specifically to track core metrics like **GDP growth** and **Fiscal Deficits** to evaluate long-term market health.
- **Responsive Architecture:** Developed with **Vite** and **Tailwind CSS** for ultra-fast load times and a pixel-perfect mobile/desktop experience.

## 🛠️ Tech Stack

- **Frontend:** TypeScript, JavaScript, Vite, Tailwind CSS
- **Data Engineering:** Python (Pandas, OpenPyXL)
- **Visuals:** Custom SVG/CSS components & Charting logic
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
