# Sales Dashboard

An interactive dashboard built with Dash to visualize sales data from Google Sheets.

## Setup Instructions

1. **Google Sheets API Setup:**
   - Go to the [Google Cloud Console](https://console.cloud.google.com/)
   - Create a new project or select an existing one
   - Enable the Google Sheets API and Google Drive API
   - Create credentials (Service Account Key)
   - Download the JSON key file and rename it to `credentials.json`
   - Place the `credentials.json` file in the project root directory
   - Share your Google Sheet with the email address from the service account

2. **Install Dependencies:**
   ```bash
   pip install dash pandas plotly gspread oauth2client
   ```

3. **Configure the Application:**
   - Open `sales_dashboard.py`
   - Replace 'YOUR_GOOGLE_SHEET_URL' with your actual Google Sheets URL

4. **Run the Application:**
   ```bash
   python sales_dashboard.py
   ```
   The dashboard will be available at `http://localhost:8050`

## Features

- Real-time data synchronization with Google Sheets
- Interactive pie chart showing sales distribution
- Detailed sales table with sorting and filtering
- Key metrics display (Total Sales, Accumulated Service, Conversion Rate, Total Appointments)
- Dark theme with modern UI

## Project Structure

```
sales_dashboard/
├── sales_dashboard.py    # Main application file
├── assets/
│   └── styles.css       # CSS styles for the dashboard
├── credentials.json     # Google Sheets API credentials
└── README.md           # Project documentation
```
# nexas-ml
