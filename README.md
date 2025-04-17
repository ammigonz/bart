# 🚇 BART API Travel Kit 
### Real-Time Bay Area Transit Insights with Python

## 📌 Overview

This project is a real-time transit data tool built using the **Bay Area Rapid Transit (BART) API**. It pulls live train arrival times, route information, and station data to help riders, commuters, and data enthusiasts explore the Bay Area's subway system through an interactive interface.

Whether you're checking how late your train is or learning about station traffic patterns, this app offers a clean, Python-powered interface to interact with BART data.

---

## 🔧 Features

- 🔍 Search by **station** to get live departure times  
- 📍 View details for **all BART stations**  
- 🚉 Explore **routes** and their respective stops  
- 🌉 Get suggested attractions alongside BART stations for a full travel kit experience
- ⏱️ Fetch **real-time ETD (estimated time of departure)** data  
- 📦 Clean, modular code structure using `requests`, `pandas`, and `Streamlit`

---

## 🚀 Setup Instructions

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/bart-api-explorer.git
cd bart-api-explorer
```

2. **(Optional) Add your BART API key**

If required, store your API key in a `.env` file:

```
BART_API_KEY=your_key_here
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the app**

```bash
streamlit run app.py
```

---

## 📡 API Reference

This app uses the [official BART API](https://api.bart.gov/docs/overview/index.aspx), which supports:

- **`etd`**: Real-time train departure estimates  
- **`stninfo`**: Station information  
- **`routeinfo`**: Route names, colors, and stops  
- **`sched`**: Train schedule information  

All API responses are returned in XML or JSON format and are parsed and displayed in a user-friendly format in the app.

---

## 🛠️ Tech Stack

- Python 3.8+
- `requests`
- `pandas`
- `Streamlit`
- `python-dotenv` (for environment variable management)

---

## 📊 Future Improvements

- Add map visualizations using `folium` or `PyDeck`
- Display real-time service alerts or delays
- Mobile UI optimization for Streamlit layout
- Schedule-based suggestions (e.g., best train times for commuters)
- Save favorite stations for quick access

---

## 🧠 Why I Built This

As a frequent BART rider and Bay Area local, I wanted to better understand the flow of public transit and use it as a playground to work with live APIs. This project helped me sharpen my skills in:

- RESTful API integration
- Data parsing and transformation
- Interactive web app development with Streamlit

It also gave me a practical way to stay connected with my local community through transit data.

---

## 🙋‍♀️ Author

**Amber Gonzalez-Pacheco**  
🚇 Public transit nerd & data scientist  
📫 [LinkedIn](https://www.linkedin.com/in/amber-gonzalez-pacheco)

---

## 📝 License

MIT License — feel free to fork, share, and build on this project!
