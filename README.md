# ✈ SmartTour — AI-Powered Travel Planner

## Setup Instructions

### 1. Install Node.js
Download from https://nodejs.org (LTS version recommended)

### 2. Get your Anthropic API Key
Go to https://console.anthropic.com → API Keys → Create Key

### 3. Add your API key
Open `server.js` and replace `YOUR_API_KEY_HERE` with your actual key:
```js
'x-api-key': 'sk-ant-xxxxxxxxxx'
```
OR create a `.env` file (copy `.env.example` to `.env`):
```
ANTHROPIC_API_KEY=sk-ant-xxxxxxxxxx
```

### 4. Install dependencies
Open terminal in this folder and run:
```bash
npm install
```

### 5. Start the server
```bash
npm start
```

### 6. Open in browser
Go to: **http://localhost:3000**

---

## Login Credentials
- Email: any valid email (e.g. `test@gmail.com`)
- Password: any 4+ characters

## Features
- 🗺️ Browse destinations (Agra, Mumbai, Goa, Kerala, Jaipur)
- 📊 Platform price comparison
- 🚆 AI transport chooser (Trains / Buses / Flights)
- ⚠️ Budget sufficiency check
- 📅 AI day-by-day itinerary
- 🏨 Hotel recommendations
- 🍽️ Food guide
- 💰 Budget breakdown
- 🗒️ Trip Summary card
