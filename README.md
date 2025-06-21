# Life Area Analysis 📊

[**▶️ Try it out on GitHub Pages**](https://sibartel.github.io/life-area-analysis/)

A modern web application for tracking, visualizing, and analyzing different areas of your life. This tool helps you understand and improve your life balance by visualizing importance, satisfaction, and time investment across various life domains.

> **Disclaimer:** This app was created using a "vibe coding" approach, with the primary goal of experimenting and exploring what is possible (as of June 2025). It is a personal project and may not follow all best practices or be production-ready.

## Features

- **Comprehensive Life Area Tracking**: Monitor 16 key life areas across categories like:
  - Relationships (Partner, Family, Friends)
  - Body & Health (Physical Health, Mental Health, Spirituality)
  - Community (Community Involvement, Social Engagement)
  - Career & Development (Job/Career, Education, Finances)
  - Interests (Hobbies, Online/Offline Entertainment)
  - Physiological (Basic Needs, Daily Activities)

- **Rich Data Visualization**
  - Interactive scatter plot visualization
  - Size-coded bubbles representing time investment
  - Color-coded categories for easy identification
  - Dynamic filtering by life area categories

- **Multiple Report Management**
  - Create and manage multiple reports
  - Track changes over time
  - Compare reports to identify trends
  - Export and import functionality for data backup

- **AI-Powered Insights** (requires Gemini API key)
  - Get personalized analysis of your life areas
  - Receive actionable recommendations
  - Compare reports with AI-generated progress insights
  - Context-aware suggestions based on your data

- **Advanced Features**
  - Detailed category filtering
  - Notes for each life area
  - Random data generation for testing
  - Responsive design for all devices

## Getting Started

1. Head over to [the on github hosted version](https://sibartel.github.io/life-area-analysis/) or download the project and open `index.html` in a modern web browser
2. Click "Create New Report" to start a new analysis
3. Rate each life area on three dimensions:
   - Importance (0-10)
   - Satisfaction (0-10)
   - Time Spent (0-10)
4. Add optional notes for context
5. View the visualization and insights

## AI Features Setup

To enable AI-powered insights:

1. Click the Settings (⚙️) button
2. Enter your Gemini API key
3. Save settings
4. Use the "Get Insights ✨" button for analysis

## Data Management

- **Export**: Click the download button to save all your reports
- **Import**: Use the upload button to restore previously exported data
- **Compare**: Select two reports to analyze changes over time

## Privacy

All data is stored locally in your browser's localStorage. No data is sent to any server except when requesting AI insights (if configured).

## License

MIT License - See [LICENSE](LICENSE) file for details

## Tech Stack

- Pure JavaScript (No framework dependencies)
- Chart.js for visualizations
- Tailwind CSS for styling
- Google Material Icons
- Marked.js for Markdown rendering
- Google Gemini API for AI insights

## Contributing

Feel free to fork this project and submit pull requests with improvements. Please follow existing code style and document any changes.
