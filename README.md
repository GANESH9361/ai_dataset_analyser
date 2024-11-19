# Flask-Based CSV Content Generator with Gemini API

This repository hosts a **Flask** web application that allows users to upload CSV files, generate content using **Google Gemini API**, and download processed results in Markdown or CSV format.

---

## Key Features
- **Upload CSV**: Securely upload CSV files up to 16MB.
- **Column Selection**: Choose the primary column to base content generation on.
- **Custom Prompt Integration**: Define prompts for AI-based content generation.
- **Markdown Output**: Generate markdown files with responses categorized by entities.
- **Google Sheets Support**: Preview and process Google Sheets via a shared URL.
- **Dynamic Previews**: Visualize processed files and responses directly in the web interface.
- **Responsive UI**: Aesthetic and mobile-friendly design for seamless user experience.

---

## Tech Stack
- **Frontend**: HTML, CSS (custom styles with gradient effects), and JavaScript.
- **Backend**: Python (Flask framework).
- **AI Integration**: Google Generative AI Gemini API for generating responses.
- **Libraries Used**:
  - `pandas`: Data manipulation and processing.
  - `requests`: Handling HTTP requests for Google Sheets integration.
  - `markdown`: Rendering Markdown files in the application.
  - `flask` and `werkzeug`: Web framework and utility tools.

---

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
