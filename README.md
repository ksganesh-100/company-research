# 🔍 Company Research Agent

A web-based tool that generates a comprehensive company research report using AI and financial data APIs. Designed for consultants, analysts, and business professionals, this tool provides a structured, insight-rich profile of any publicly traded company.

---

## 🚀 Features

- Clean, responsive UI with modern styling
- AI-generated company research report using Gemini API
- Financial summary table (Revenue, Net Income, EBITDA for last 5 years)
- Markdown and HTML rendering with support for tables
- Easy-to-use input and one-click report generation

---

## 🛠️ Setup Instructions

1. Clone the repository:
   git clone https://github.com/your-username/company-research-agent.git
   cd company-research-agent

2. Open `index.html` in your browser.

---

## 📌 Usage Guide

1. Enter the name of a publicly traded company (e.g., "Apple", "Tesla").
2. Click "Generate Report".
3. The tool will:
   - Resolve the company ticker using Financial Modeling Prep API
   - Fetch the last 5 years of financial data
   - Generate a detailed company profile using Gemini AI
   - Render the output with Markdown and HTML (including tables)

---

## 🔑 Required API Keys

You will need the following API keys:

- Gemini API Key (Google Generative Language API)
- Financial Modeling Prep API Key (https://financialmodelingprep.com)

Replace the placeholders in the script:
const geminiApiKey = "YOUR_GEMINI_API_KEY";
const fmpApiKey = "YOUR_FMP_API_KEY";

---

## 🧩 Customization Notes

- Modify the prompt in `fetchCompanyInfo()` to tailor the report.
- The financial summary is injected as raw HTML to preserve table formatting.
- Styling is handled via embedded CSS in the `<head>` section of the HTML file.

---

## 📄 License

This project is open-source and available under the MIT License.
