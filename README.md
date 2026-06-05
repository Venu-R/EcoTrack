# 🌱 EcoTrack - Carbon Emission Tracker

## 📖 Overview

EcoTrack is a web-based carbon emission tracking platform designed to help users understand and reduce their environmental impact. The application calculates CO₂ emissions generated from daily travel activities, provides detailed analytics, and offers personalized suggestions for adopting more sustainable transportation habits.

By converting travel data into meaningful insights, EcoTrack enables users to make informed decisions that contribute to a greener future.

---

## ✨ Features

### 🚗 Travel Tracking

* Record daily travel activities
* Support for multiple transportation modes
* Track distance traveled per trip

### 🌍 Carbon Footprint Calculation

* Automatic CO₂ emission calculation
* Uses standard emission factors for different transport modes
* Accurate trip-wise emission reporting

### 📊 Analytics Dashboard

* Visualize emission trends over time
* View historical travel records
* Monitor personal carbon footprint growth or reduction

### 💡 Personalized Recommendations

* Suggestions to reduce emissions
* Sustainable travel alternatives
* Environment-friendly habit recommendations

### 🗄 Data Management

* Store travel records securely
* Retrieve and analyze historical data efficiently

---

## 🏗 System Architecture

```text
Frontend (HTML/CSS/JavaScript)
            │
            ▼
      FastAPI Backend
            │
            ▼
      MySQL Database
```

The frontend collects user travel information, the FastAPI backend processes and calculates emissions, and MySQL stores travel records and analytics data.

---

## ⚙️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Python
* FastAPI

### Database

* MySQL

---

## 🔄 Workflow

1. User enters travel details.
2. Travel distance and transportation mode are processed.
3. Standard emission factors are applied.
4. CO₂ emissions are calculated.
5. Results are stored in MySQL.
6. Analytics are generated and displayed.
7. Users receive personalized reduction suggestions.

---

## 📈 Carbon Emission Calculation

The platform estimates emissions using:

```text
Carbon Emission = Distance Travelled × Emission Factor
```

Where:

* Distance Travelled = Total kilometers traveled
* Emission Factor = CO₂ emitted per kilometer for the selected transport mode

---

## 🎯 Objectives

* Promote environmental awareness
* Encourage sustainable transportation choices
* Provide actionable carbon footprint insights
* Help users reduce their environmental impact

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/Venu-R/EcoTrack.git
cd EcoTrack
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Database

Update your database credentials:

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=ecotrack
```

### Run the Application

```bash
uvicorn main:app --reload
```

Open:

```text
http://localhost:8000
```

---

## 🔮 Future Enhancements

* User authentication and profiles
* Carbon footprint comparison system
* Public transport recommendations
* Route optimization
* Mobile application support
* AI-powered sustainability suggestions
* Real-time emission forecasting

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

---
## 👨‍💻 Author
**Venu R**
