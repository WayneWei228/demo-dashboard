# 🏠 Fallyx Dashboard Development

Welcome to the **Fallyx Dashboard**! This project includes two types of dashboards designed to improve safety and management in retirement homes:

- **Management Dashboard**: Enables managers to monitor falls, compliance, and other critical metrics across multiple homes.
- **Individual Dashboard**: Provides residents and their caretakers with a personalized view to track and update resident-specific data.

---

## 🌟 Features Implemented

### 🎨 Frontend Development

- Built an **intuitive and user-friendly interface** with dynamic data visualizations.
- Designed two main views:
  - **Management Dashboard**: Displays global metrics, graphs, and aggregated data (e.g., falls, injuries, non-compliance incidents).
  - **Individual Dashboard**: Offers a personalized table for tracking and updating fall-related incidents.

### 🔗 Backend Integration

- Connected the dashboard to **Firebase** for secure storage and real-time data retrieval.
- Ensured robust handling of sensitive **resident and management data**.

### 💅 CSS Optimization

- Applied detailed CSS styling to create a **responsive and visually appealing design**.
- Ensured layouts are optimized for **readability and accessibility** on all devices.

### 🔒 User Login and Authentication

- Implemented a **secure login system** to restrict access to authorized users only.
- **Role-based access control**:
  - **Management-level**: Access to aggregated data and analytics.
  - **Individual-level**: Access to specific resident information.

### 🔐 Security

- Followed **industry standards** for securing data transmission and storage.
- Used **authentication tokens** for user sessions.
- Ensured compliance with **data privacy regulations** for sensitive resident information.

---

## 🛠️ Developer Notes

- The dashboard **dynamically pulls data** from Firebase in real-time, updating metrics and charts without page reloads.
- The **management dashboard** allows administrators to:
  - Download data as **CSV or PDF** for further analysis. 📄
- The **individual dashboard** features:
  - Editable tables for tracking falls, with seamless synchronization to Firebase. ✍️

---

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed ✅
- Firebase project set up and configured 🔥

### Installation

1. Clone the repository:

```bash
   git clone https://github.com/WayneWei228/demo-dashboard.git
   cd fallyx-dashboard
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

4. Open your browser and navigate to:

```bash
http://localhost:3000
```

## 💡 Future Enhancements

- 🌍 **Add multi-language support**: Accommodate diverse user groups with multilingual options.
- 🔔 **Implement notifications and alerts**: Provide real-time updates and critical event alerts.
- 📊 **Integrate AI-powered analytics**: Offer predictive insights on fall incidents.
- 📱 **Develop mobile-friendly enhancements**: Improve accessibility and usability on small screens.
- 📑 **Enable custom reporting**: Add advanced filtering and export options for management dashboards.

---

## 📄 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this software as long as proper credit is given.
