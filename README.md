🚭 Assist-You (Smoke Timer)
Assist-You is a lightweight, privacy-focused Progressive Web App (PWA) designed as a harm-reduction tool. It helps users gain control over smoking habits by enforcing "cooldown" periods between cigarettes, tracking daily intake, and visualizing long-term progress.

✨ Key Features
⏱️ Cooldown Timer: A circular countdown visualizer that encourages users to increase the gap between cigarettes.

📊 Comprehensive Analytics:

Daily Metrics: Track cigarettes smoked, money spent, and life-time saved.

Urge Tracking: Log the intensity and triggers (e.g., Stress, Coffee, Social) of cravings.

Insights: Identifies your "Risky Hour" and "Urge Pressure" patterns.

🏆 Achievement System: Visual progress bars and milestones for 3, 7, 14, and 30-day streaks.

🌙 Adaptive UI: Automatic Night Mode based on the time of day, with a clean "Inter" font interface.

☁️ Data Sovereignty: * Manual JSON export/import.

Google Drive integration for cloud backups.

All core logic runs locally in the browser via localStorage.

🛠️ Technical Architecture
This project is a "Vanilla" powerhouse—built purely on web standards without heavy frameworks, ensuring it is fast and works offline.

Frontend: HTML5, CSS3 (Modular CSS files for layout, components, and tabs).

Logic: Vanilla JavaScript (ES6+).

PWA: manifest.json and Service Worker support for "Add to Home Screen" functionality.

Icons: Bootstrap Icons.

Storage: Browser localStorage for instant persistence and Google Drive API for remote backup.

📂 Project Structure
Plaintext

assist-you/
├── index.html          # Core application structure
├── app.js              # Main application logic & state management
├── drive.js            # Google Drive API integration
├── manifest.json       # PWA configuration
└── style/              # Modular stylesheet system
    ├── base.css        # Resets and variables
    ├── timer.css       # SVG Ring and timer animations
    ├── analytics.css   # Progress charts and metrics
    └── ...             # Component-specific styles
🚀 Installation & Local Development
Since this is a static PWA, you don't need a complex build process:

Clone the repo:

Bash

git clone https://github.com/Shreesha99/assist-you.git
Open in Browser: Simply open index.html in any modern browser.

Deployment: Host it on GitHub Pages, Vercel, or Netlify by simply connecting the repository.

⚙️ Configuration
Users can customize their experience through the Settings Tab:

Set a Daily Limit to calculate streak health.

Define Price per pack and Cigs per pack for accurate financial tracking.

Add custom Cooldown Presets (e.g., 45m, 60m, 90m).

Select notification sounds (Ding, Soft, or Off).

⚠️ Disclaimer
This app is a harm-reduction tool intended to help users cut down or quit. It is not medical advice. The goal is to build self-control by increasing the time between logs.

Created by Shreesha | One cooldown at a time.
