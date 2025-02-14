# chrome-extension-reactjs
COMPANY: CODITECH SOLUTIONS
NAME: MOHAMED MUFLIH
INTERN ID:CT08NLU
DOMAIN:REACT
BATCH DURATION:january 15th/2025 to february 15th/2025
Here's a detailed explanation of the Chrome extension:

### **Overview**
This Chrome extension is designed to help users track their time spent on websites, set daily productivity goals, and visualize productivity trends. The core components of the extension include:

1. **Manifest File (`manifest.json`)**  
   This file defines essential metadata and permissions for the extension, such as storage access, active tab monitoring, and background scripting.

2. **Background Script (`background.js`)**  
   The background script is responsible for tracking time spent on active tabs. When a user switches tabs or closes a tab, the script calculates the time spent on the site and stores it in Chrome's local storage.

3. **Content Script (`content.js`)**  
   The content script currently logs a message to indicate that the extension is running. It can be expanded to include additional functionalities, such as highlighting distractions.

4. **Popup UI (`Popup.js`)**  
   The popup UI is built using React and serves as the primary user interface. It includes components for setting goals and viewing productivity statistics.

5. **Goal Setter (`GoalSetter.js`)**  
   This component allows users to input a daily productivity goal (in minutes) and save it to Chrome's local storage.

6. **Stats Chart (`StatsChart.js`)**  
   The stats chart visualizes the time spent on different websites using Chart.js, helping users analyze their online activity.

7. **Index File (`index.js`)**  
   The index file initializes the React app and renders the popup UI.

### **How It Works**
- When a user activates a tab, the background script records the start time.
- Upon tab closure or switching, the script calculates the time spent and updates Chrome storage.
- The popup UI fetches stored time data and displays it in a bar chart.
- Users can set daily goals and track their progress over time.

This extension provides a simple yet effective way to boost productivity by monitoring online habits. 🚀 Let me know if you need modifications!
