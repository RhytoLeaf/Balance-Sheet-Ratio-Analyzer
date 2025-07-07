### Balance Sheet Ratios Analyzer

This is a web-based tool designed to help individuals, especially those new to investing, understand the financial health of public companies by analyzing key balance sheet ratios. It provides clear, concise explanations and actionable insights to promote financial literacy.

## Features
Company Financial Analysis: Input a company's ticker symbol (e.g., AAPL, TSLA) to retrieve and display its most recent balance sheet ratios.

# Key Ratios Calculated:

Current Ratio: Assesses short-term liquidity.

Quick Ratio (Acid-Test Ratio): A more stringent liquidity test, excluding inventory.

Debt-to-Equity Ratio: Indicates financial leverage and reliance on debt.

Goodwill to Total Assets Ratio: Shows the proportion of intangible assets from acquisitions.

Ratio Status Indicators: Each ratio is assigned a status (Fragile, Robust, Antifragile) with color-coded indicators for quick comprehension.

AI-Powered Financial Summary: Utilizes the Gemini API (LLM) to generate a brief (max 80 words), easy-to-understand summary of the company's financial health, explaining what each calculated metric means in simple terms. Includes recent news headlines with publication dates.

# AI-Powered Actionable Insights: 
Provides 2-3 concise, actionable takeaways based on the overall financial ratios, helping users understand practical implications.

# Text-to-Speech (TTS): 
"Listen" buttons are available for both the Financial Summary and Actionable Insights, allowing users to hear the generated content.

# User-Friendly Interface: 
Built with a clean, responsive design using Tailwind CSS for optimal viewing on various devices.

# Educational Focus: 
Explicitly designed as an educational tool to demystify financial jargon for a broader audience.

## How It Works
The application fetches real-time financial data using the Financial Modeling Prep (FMP) API. Once the data is retrieved, it calculates the specified balance sheet ratios. For the financial summary and actionable insights, the application makes calls to the Gemini API (LLM), passing the calculated ratios and recent news (also from FMP) to generate human-readable explanations and insights tailored for a novice audience.

## Technologies Used
# HTML5: Structure of the web application.

# Tailwind CSS: For responsive and modern styling.

# jQuery: Simplifies DOM manipulation and AJAX requests.

# Financial Modeling Prep (FMP) API: Source for company balance sheet data and recent news.

# Gemini API (LLM): Powers the financial summary and actionable insights generation.

# Web Speech API: For text-to-speech functionality.

## Usage
Enter a company's stock ticker symbol (e.g., AAPL, TSLA, MSFT) into the input field.

Click the "Analyze Ratios" button to fetch and display the balance sheet ratios.

Click "✨ Get Financial Summary" to receive a concise overview of the company's financial standing.

Click "✨ Get Actionable Insights" for practical takeaways based on the analysis.

Use the "🔊 Listen" buttons to hear the generated summaries and insights.

Disclaimer
This tool is for educational purposes only and should not be considered professional financial advice. Always consult with a qualified financial advisor before making any investment decisions.

© RhytoLeaf Inc. 2025