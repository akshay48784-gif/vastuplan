# 🏛️ VastuPlan AI

🌟 **Live Demo:** [https://akshay48784-gif.github.io/](https://akshay48784-gif.github.io/)

**VastuPlan AI** is an intelligent, web-based architectural floor plan generator that leverages the Google Gemini API to design residential layouts. It balances modern space utilization with traditional Vastu Shastra principles, generating proportional, data-driven blueprints directly in the browser.

## ✨ Features

* **AI-Driven Generation:** Uses Google Gemini (1.5 Flash / 2.0 Flash) to process spatial constraints and output structured floor plan data (JSON).
* **Vastu Compliance Engine:** Automatically scores and validates room placements (e.g., Kitchen in SE, Master Bedroom in SW) based on user-defined strictness levels.
* **Dynamic Blueprint Canvas:** Renders the AI-generated JSON into a visual floor plan using the HTML5 `<canvas>` API, complete with accurate scaling, room labels, and wall thickness representations.
* **Comprehensive Reporting:** Generates detailed room area tables, Vastu compliance scores, and space utilization summaries.
* **One-Click PDF Export:** Uses `jsPDF` to compile the visual blueprint and tabular data into a professional, downloadable report.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Modern Dark UI), Vanilla JavaScript
* **AI Engine:** Google Gemini API (`gemini-1.5-flash` / `gemini-2.0-flash`)
* **Libraries:** `jsPDF` (for report generation)
* **Hosting:** GitHub Pages

## 🚀 Getting Started

### Try it Online
The easiest way to use VastuPlan AI is through the live web version:
👉 **[Open VastuPlan AI](https://akshay48784-gif.github.io/)**

**Prerequisites to use the app:**
You will need a **Google Gemini API Key**.
1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Sign in with your Google account.
3. Click **Create API Key** and copy the generated key.

### Local Installation (For Developers)
If you want to modify the code or run it locally:

1. Clone the repository:
   ```bash
   git clone [https://github.com/akshay48784-gif/akshay48784-gif.github.io.git](https://github.com/akshay48784-gif/akshay48784-gif.github.io.git)
